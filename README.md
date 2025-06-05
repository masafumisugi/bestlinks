// スマートフォン用追加機能
document.addEventListener('DOMContentLoaded', function() {
    // タッチデバイス検出
    const isTouchDevice = 'ontouchstart' in window || navigator.maxTouchPoints > 0;
    
    if (isTouchDevice) {
        document.body.classList.add('touch-device');
    }
    
    // iOS Safari特有の100vh問題対応
    const setVH = () => {
        const vh = window.innerHeight * 0.01;
        document.documentElement.style.setProperty('--vh', `${vh}px`);
    };
    
    setVH();
    window.addEventListener('resize', setVH);
    window.addEventListener('orientationchange', setVH);
    
    // スマートフォンでのスクロール改善
    if (window.innerWidth <= 768) {
        // パフォーマンス向上のためアニメーションを簡略化
        const style = document.createElement('style');
        style.textContent = `
            * {
                -webkit-transform: translate3d(0, 0, 0);
                transform: translate3d(0, 0, 0);
            }
        `;
        document.head.appendChild(style);
    }
    
    // フォーム送信時のダブルタップ防止
    const forms = document.querySelectorAll('form');
    forms.forEach(form => {
        form.addEventListener('submit', function(e) {
            const submitBtn = form.querySelector('button[type="submit"], input[type="submit"]');
            if (submitBtn) {
                submitBtn.disabled = true;
                setTimeout(() => {
                    submitBtn.disabled = false;
                }, 3000);
            }
        });
    });
    
    // 診断ボタンのダブルタップ防止
    const diagnosisBtn = document.querySelector('.diagnosis-btn');
    if (diagnosisBtn) {
        let isCalculating = false;
        
        diagnosisBtn.addEventListener('click', function(e) {
            if (isCalculating) {
                e.preventDefault();
                return false;
            }
            
            isCalculating = true;
            setTimeout(() => {
                isCalculating = false;
            }, 2000);
        });
    }
});

// 診断計算機能の改善（スマートフォン用）
function calculateDiagnosis() {
    // 既存の計算処理...
    
    // スマートフォンでの結果表示改善
    if (window.innerWidth <= 768) {
        const resultDiv = document.getElementById('diagnosisResult');
        resultDiv.classList.add('show');
        
        // スムーズスクロールの改善
        setTimeout(() => {
            const elementPosition = resultDiv.getBoundingClientRect().top;
            const offsetPosition = elementPosition + window.pageYOffset - 100;
            
            window.scrollTo({
                top: offsetPosition,
                behavior: 'smooth'
            });
        }, 300);
    }
}
