<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>宽石网 | 以 AI 定义视觉极限</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;700;900&display=swap');
        
        :root {
            --primary-blue: #3b82f6;
            --deep-black: #020617;
            --electric-blue: #60a5fa;
        }

        body {
            background-color: var(--deep-black);
            color: white;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            scroll-behavior: smooth;
        }

        .blue-gradient-text {
            background: linear-gradient(90deg, #3b82f6 0%, #93c5fd 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .glass-panel {
            background: rgba(15, 23, 42, 0.6);
            backdrop-filter: blur(20px);
            border: 1px solid rgba(59, 130, 246, 0.2);
            box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.37);
        }

        .neon-border {
            position: relative;
            overflow: hidden;
        }
        .neon-border::after {
            content: '';
            position: absolute;
            bottom: 0; left: 0; width: 100%; height: 2px;
            background: linear-gradient(90deg, transparent, var(--primary-blue), transparent);
            animation: flow 3s linear infinite;
        }
        @keyframes flow {
            0% { transform: translateX(-100%); }
            100% { transform: translateX(100%); }
        }

        .hero-glow {
            position: absolute;
            width: 800px;
            height: 800px;
            background: radial-gradient(circle, rgba(59, 130, 246, 0.15) 0%, rgba(0,0,0,0) 70%);
            z-index: -1;
            filter: blur(80px);
        }

        .btn-premium {
            background: linear-gradient(135deg, #2563eb 0%, #1d4ed8 100%);
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }
        .btn-premium:hover {
            transform: scale(1.05) translateY(-2px);
            box-shadow: 0 0 30px rgba(59, 130, 246, 0.5);
        }

        /* 模拟 AI 对比滑块 */
        .compare-container {
            position: relative;
            width: 100%;
            height: 400px;
            overflow: hidden;
            border-radius: 2rem;
        }
        .compare-after {
            position: absolute;
            top: 0; left: 0; width: 100%; height: 100%;
            background-image: url('https://images.unsplash.com/photo-1611162617213-6d562f266557?auto=format&fit=crop&w=800&q=80');
            background-size: cover;
        }
        .compare-before {
            position: absolute;
            top: 0; left: 0; width: 50%; height: 100%;
            background-image: url('https://images.unsplash.com/photo-1611162617213-6d562f266557?auto=format&fit=crop&w=800&q=10'); /* 模拟低画质 */
            background-size: cover;
            border-right: 4px solid white;
            z-index: 10;
        }
    </style>
</head>
<body class="overflow-x-hidden">

    <!-- 极简导航 -->
    <nav class="fixed top-0 w-full z-50 px-8 py-6 flex justify-between items-center glass-panel border-none">
        <div class="text-2xl font-black tracking-tighter blue-gradient-text uppercase">宽石网 KUANSHI</div>
        <div class="hidden md:flex space-x-12 text-xs font-bold uppercase tracking-widest text-gray-400">
            <a href="#vision" class="hover:text-blue-400 transition">Vision</a>
            <a href="#ai-power" class="hover:text-blue-400 transition">AI Power</a>
            <a href="#social" class="hover:text-blue-400 transition">Ecosystem</a>
        </div>
        <a href="#waitlist" class="px-6 py-2 rounded-full btn-premium text-xs font-bold">预约内测</a>
    </nav>

    <!-- 第一屏：极致视觉 (Hero) -->
    <section class="relative h-screen flex flex-col justify-center items-center text-center px-4">
        <div class="hero-glow top-[-20%] left-[-20%]"></div>
        <div class="hero-glow bottom-[-20%] right-[-20%]"></div>
        
        <h1 class="animate__animated animate__fadeInDown text-6xl md:text-9xl font-black tracking-tighter mb-8 leading-tight">
            以 <span class="blue-gradient-text">AI</span> 定义<br>视觉极限
        </h1>
        <p class="animate__animated animate__fadeInUp animate__delay-1s text-gray-400 text-lg md:text-2xl max-w-3xl mb-12 font-light leading-relaxed">
            宽石网：将 8K 工业级画质与神经元级 AI 剪辑深度融合。<br>
            在数字化维度中，重塑短视频的创作逻辑。
        </p>
        <div class="animate__animated animate__fadeInUp animate__delay-2s flex flex-col md:flex-row space-y-4 md:space-y-0 md:space-x-6">
            <a href="#waitlist" class="px-12 py-5 rounded-full btn-premium text-lg font-bold">申请内测资格</a>
            <a href="#ai-power" class="px-12 py-5 rounded-full glass-panel text-lg font-bold hover:bg-white/10 transition">探索 AI 引擎</a>
        </div>
    </section>

    <!-- 第二屏：AI 视觉对比 (The Magic) -->
    <section id="ai-power" class="py-32 px-6 max-w-7xl mx-auto">
        <div class="text-center mb-20">
            <h2 class="text-4xl md:text-6xl font-black mb-6">从 <span class="text-gray-500">平凡</span> 到 <span class="blue-gradient-text">巅峰</span></h2>
            <p class="text-gray-400 text-lg">无需专业设备，AI 瞬间将你的画面提升至 8K 工业标准。</p>
        </div>

        <div class="compare-container group cursor-ew-resize">
            <div class="compare-after"></div>
            <div class="compare-before transition-all duration-300 group-hover:width-[20%]"></div>
            <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 z-20 bg-white text-black px-4 py-2 rounded-full font-bold text-xs shadow-xl">
                滑动查看 AI 增强
            </div>
        </div>
        <div class="flex justify-between mt-4 text-xs font-bold text-gray-500 tracking-widest uppercase">
            <span>Original Raw</span>
            <span>Kuanshi AI Enhanced</span>
        </div>
    </section>

    <!-- 第三屏：核心能力 (Features) -->
    <section class="py-32 px-6 max-w-7xl mx-auto">
        <div class="grid grid-cols-1 md:grid-cols-3 gap-12">
            <div class="p-12 rounded-[3rem] glass-panel group neon-border">
                <div class="w-16 h-16 bg-blue-600 rounded-2xl mb-8 flex items-center justify-center text-3xl group-hover:rotate-12 transition duration-500">⚡</div>
                <h3 class="text-2xl font-bold mb-6">神经元剪辑</h3>
                <p class="text-gray-400 leading-relaxed">AI 自动分析情绪波段，精准捕捉瞬间，一键生成具有电影感节奏的视觉作品。</p>
            </div>
            <div class="p-12 rounded-[3rem] glass-panel group neon-border">
                <div class="w-16 h-16 bg-blue-600 rounded-2xl mb-8 flex items-center justify-center text-3xl group-hover:rotate-12 transition duration-500">💎</div>
                <h3 class="text-2xl font-bold mb-6">像素级增强</h3>
                <p class="text-gray-400 leading-relaxed">突破硬件限制，实时将 1080P 视频重构为 8K 纯净画质，每一帧都是壁纸。</p>
            </div>
            <div class="p-12 rounded-[3rem] glass-panel group neon-border">
                <div class="w-16 h-16 bg-blue-600 rounded-2xl mb-8 flex items-center justify-center text-3xl group-hover:rotate-12 transition duration-500">🌐</div>
                <h3 class="text-2xl font-bold mb-6">全域社交</h3>
                <p class="text-gray-400 leading-relaxed">深度集成的实时社交协议，让创作者与观众在同一视觉维度内无缝共鸣。</p>
            </div>
        </div>
    </section>

    <!-- 第四屏：拟真交互 (Social Ecosystem) -->
    <section id="social" class="py-32 px-6 bg-slate-900/30">
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row items-center gap-20">
            <div class="flex-1 text-left">
                <h2 class="text-4xl md:text-6xl font-black mb-8 leading-tight">打破观看边界<br><span class="blue-gradient-text">重建社交链接</span></h2>
                <p class="text-gray-400 text-xl mb-12 font-light">
                    宽石网不仅是内容的承载，更是灵感的交换站。通过端到端的实时交互，让每一次评论都成为创作的起点。
                </p>
            </div>
            <div class="flex-1 relative">
                <div class="absolute -inset-10 bg-blue-600/20 blur-3xl rounded-full"></div>
                <div class="relative glass-panel p-4 rounded-[2.5rem] shadow-2xl w-full max-w-sm border-blue-500/30">
                    <div class="bg-black/40 rounded-[2rem] p-4 space-y-4">
                        <div class="flex items-center space-x-3 p-3 bg-blue-500/10 rounded-2xl border border-blue-500/20">
                            <div class="w-8 h-8 rounded-full bg-gradient-to-tr from-blue-400 to-purple-500"></div>
                            <p class="text-xs"><b class="text-blue-300">AI_Master:</b> 这段画质太惊人了！🚀</p>
                        </div>
                        <div class="flex items-center space-x-3 p-3 bg-white/5 rounded-2xl text-right justify-end">
                            <p class="text-xs"><b>你:</b> 宽石网的 8K 增强太稳了 🔥</p>
                            <div class="w-8 h-8 rounded-full bg-blue-600"></div>
                        </div>
                        <div class="flex items-center space-x-3 p-3 bg-blue-500/10 rounded-2xl border border-blue-500/20">
                            <div class="w-8 h-8 rounded-full bg-gray-600"></div>
                            <p class="text-xs"><b class="text-blue-300">Visionary:</b> 申请内测的入口在哪？</p>
                        </div>
                    </div>
                    <div class="mt-4 p-4 bg-blue-600 rounded-full text-center text-xs font-bold cursor-pointer hover:bg-blue-500 transition">
                        进入宽石社交空间
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 第五屏：转化模块 (Waitlist) -->
    <section id="waitlist" class="py-32 px-6 text-center max-w-4xl mx-auto">
        <div class="p-20 rounded-[4rem] glass-panel relative overflow-hidden border-2 border-blue-500/40">
            <div class="absolute top-0 left-0 w-full h-full bg-blue-600/5 animate-pulse"></div>
            <h2 class="text-4xl md:text-6xl font-black mb-8">加入 <span class="blue-gradient-text">内测名单</span></h2>
            <p class="text-gray-400 text-lg mb-12 max-w-xl mx-auto font-light">
                我们目前仅向受邀创作者开放。留下你的联系方式，我们将优先通知你进入 8K AI 视觉世界。
            </p>
            <form class="flex flex-col md:flex-row gap-4 justify-center items-center">
                <input type="email" placeholder="输入你的邮箱地址" class="w-full md:w-96 px-6 py-4 rounded-full bg-slate-800 border border-blue-500/30 text-white focus:outline-none focus:ring-2 focus:ring-blue-500 transition">
                <button type="button" class="w-full md:w-auto px-10 py-4 rounded-full btn-premium text-lg font-bold">
                    立即申请
                </button>
            </form>
            <p class="mt-6 text-gray-500 text-xs uppercase tracking-widest">Limited Access • By Invitation Only</p>
        </div>
    </section>

    <!-- 底部 -->
    <footer class="py-20 text-center text-gray-600 text-sm border-t border-slate-800">
        <div class="text-xl font-black blue-gradient-text mb-6">KUANSHI NET</div>
        <p class="mb-4">&copy; 2026 宽石网 Inc. 定义视觉极限</p>
        <div class="flex justify-center space-x-6 text-xs font-medium uppercase">
            <a href="#" class="hover:text-white transition">Privacy</a>
            <a href="#" class="hover:text-white transition">Terms</a>
            <a href="#" class="hover:text-white transition">Contact</a>
        </div>
    </footer>

</body>
</html>
