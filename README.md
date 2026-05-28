<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VibeStream | 定义灵感新维度</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css" rel="stylesheet">
    <style>
        body {
            background-color: #050505;
            color: white;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
        }
        .gradient-text {
            background: linear-gradient(45deg, #00f2fe 0%, #4facfe 100%, #f093fb 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .glass {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        .hero-glow {
            position: absolute;
            width: 500px;
            height: 500px;
            background: radial-gradient(circle, rgba(79, 172, 254, 0.15) 0%, rgba(0,0,0,0) 70%);
            z-index: -1;
        }
    </style>
</head>
<body class="overflow-x-hidden">

    <!-- 导航栏 -->
    <nav class="fixed top-0 w-full z-50 px-6 py-4 flex justify-between items-center glass">
        <div class="text-2xl font-bold tracking-tighter gradient-text">VibeStream</div>
        <div class="hidden md:flex space-x-8 text-sm font-medium text-gray-400">
            <a href="#" class="hover:text-white transition">产品特性</a>
            <a href="#" class="hover:text-white transition">创作者中心</a>
            <a href="#" class="hover:text-white transition">关于我们</a>
        </div>
        <button class="px-5 py-2 rounded-full bg-white text-black text-sm font-bold hover:bg-gray-200 transition">
            立即下载
        </button>
    </nav>

    <!-- Hero Section -->
    <section class="relative h-screen flex flex-col justify-center items-center text-center px-4">
        <div class="hero-glow top-1/4 -left-20"></div>
        <div class="hero-glow bottom-1/4 -right-20"></div>
        
        <h1 class="animate__animated animate__fadeInUp text-6xl md:text-8xl font-extrabold tracking-tight mb-6">
            定义<span class="gradient-text">未来</span>短视频
        </h1>
        <p class="animate__animated animate__fadeInUp animate__delay-1s text-gray-400 text-lg md:text-xl max-w-2xl mb-10">
            不仅仅是短视频，更是全球创意的实时同步。用 AI 驱动的精准推荐，发现你真正热爱的内容。
        </p>
        <div class="animate__animated animate__fadeInUp animate__delay-2s flex space-x-4">
            <button class="px-8 py-4 rounded-full bg-gradient-to-r from-blue-500 to-purple-600 font-bold hover:scale-105 transition-transform">
                开始探索
            </button>
            <button class="px-8 py-4 rounded-full glass font-bold hover:bg-white/10 transition">
                观看演示
            </button>
        </div>

        <!-- 模拟手机界面 (简易版) -->
        <div class="mt-20 relative animate__animated animate__zoomIn animate__delay-2s">
            <div class="w-64 h-[500px] border-8 border-gray-800 rounded-[3rem] overflow-hidden shadow-2xl relative">
                <div class="absolute inset-0 bg-gradient-to-b from-transparent to-black/60 z-10"></div>
                <img src="https://images.unsplash.com/photo-1611162617213-6d562f266557?auto=format&fit=crop&w=400&q=80" class="w-full h-full object-cover" alt="video preview">
                <div class="absolute bottom-6 left-6 z-20 text-left">
                    <p class="text-xs font-bold">@CreativeMind</p>
                    <p class="text-[10px] text-gray-300">#未来科技 #极简主义</p>
                </div>
            </div>
        </div>
    </section>

    <!-- 特性模块 -->
    <section class="py-24 px-6 max-w-7xl mx-auto">
        <h2 class="text-center text-4xl font-bold mb-16">为什么选择 <span class="gradient-text">VibeStream</span>?</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <div class="p-8 rounded-3xl glass hover:border-blue-500 transition group">
                <div class="w-12 h-12 bg-blue-500 rounded-2xl mb-6 group-hover:rotate-12 transition"></div>
                <h3 class="text-xl font-bold mb-4">AI 智能推荐</h3>
                <p class="text-gray-400">毫秒级响应的算法，精准捕捉你的每一次心跳，推送你真正感兴趣的内容。</p>
            </div>
            <div class="p-8 rounded-3xl glass hover:border-purple-500 transition group">
                <div class="w-12 h-12 bg-purple-500 rounded-2xl mb-6 group-hover:rotate-12 transition"></div>
                <h3 class="text-xl font-bold mb-4">极致创作工具</h3>
                <p class="text-gray-400">无需专业知识，通过强大的内置 AI 编辑器，让每个人都能拍出电影级大片。</p>
            </div>
            <div class="p-8 rounded-3xl glass hover:border-pink-500 transition group">
                <div class="w-12 h-12 bg-pink-500 rounded-2xl mb-6 group-hover:rotate-12 transition"></div>
                <h3 class="text-xl font-bold mb-4">全球社区生态</h3>
                <p class="text-gray-400">打破地域壁垒，与全球数百万创作者实时互动，分享每一个瞬间。</p>
            </div>
        </div>
    </section>

</body>
</html>
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>宽视 | 以 AI 拓宽视觉疆域</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900&display=swap');
        
        body {
            background-color: #020617; /* 极深蓝色调黑 */
            color: white;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            scroll-behavior: smooth;
        }
        .blue-gradient-text {
            background: linear-gradient(90deg, #3b82f6 0%, #60a5fa 50%, #93c5fd 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .glass-card {
            background: rgba(30, 41, 59, 0.4);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(59, 130, 246, 0.2);
            transition: all 0.3s ease;
        }
        .glass-card:hover {
            border-color: #3b82f6;
            box-shadow: 0 0 20px rgba(59, 130, 246, 0.3);
            transform: translateY(-5px);
        }
        .neon-blue-glow {
            position: absolute;
            width: 600px;
            height: 600px;
            background: radial-gradient(circle, rgba(37, 99, 235, 0.2) 0%, rgba(0,0,0,0) 70%);
            z-index: -1;
            filter: blur(60px);
        }
        .btn-primary {
            background: linear-gradient(90deg, #2563eb, #3b82f6);
            transition: all 0.3s ease;
        }
        .btn-primary:hover {
            box-shadow: 0 0 25px rgba(59, 130, 246, 0.6);
            transform: scale(1.05);
        }
    </style>
</head>
<body class="overflow-x-hidden">

    <!-- 导航栏 -->
    <nav class="fixed top-0 w-full z-50 px-8 py-5 flex justify-between items-center glass-card border-none bg-slate-900/80">
        <div class="text-3xl font-black tracking-tighter blue-gradient-text">宽视 KUANSHI</div>
        <div class="hidden md:flex space-x-10 text-sm font-medium text-gray-300">
            <a href="#features" class="hover:text-blue-400 transition">核心特性</a>
            <a href="#social" class="hover:text-blue-400 transition">社交生态</a>
            <a href="#creator" class="hover:text-blue-400 transition">创作者计划</a>
        </div>
        <a href="#download" class="px-6 py-2 rounded-full btn-primary text-sm font-bold">
            立即下载
        </a>
    </nav>

    <!-- 第一屏：Hero Section -->
    <section class="relative h-screen flex flex-col justify-center items-center text-center px-4 overflow-hidden">
        <div class="neon-blue-glow top-[-10%] left-[-10%]"></div>
        <div class="neon-blue-glow bottom-[-10%] right-[-10%]"></div>
        
        <h1 class="animate__animated animate__fadeInDown text-6xl md:text-9xl font-black tracking-tighter mb-8 leading-tight">
            以 <span class="blue-gradient-text">AI</span> 拓宽<br>视觉疆域
        </h1>
        <p class="animate__animated animate__fadeInUp animate__delay-1s text-gray-400 text-lg md:text-2xl max-w-3xl mb-12 font-light">
            宽视不仅仅是一个短视频平台。它是 AI 自动剪辑、极致 8K 画质与实时深度社交的完美共生。
        </p>
        <div class="animate__animated animate__fadeInUp animate__delay-2s flex flex-col md:flex-row space-y-4 md:space-y-0 md:space-x-6">
            <a href="#download" class="px-10 py-4 rounded-full btn-primary text-lg font-bold">
                开启宽视之旅
            </a>
            <a href="#features" class="px-10 py-4 rounded-full glass-card text-lg font-bold hover:bg-white/10 transition">
                探索 AI 核心
            </a>
        </div>

        <!-- 手机模型预览 -->
        <div class="mt-20 relative animate__animated animate__zoomIn animate__delay-2s">
            <div class="w-72 h-[580px] border-[12px] border-slate-800 rounded-[3rem] overflow-hidden shadow-[0_0_50px_rgba(59,130,246,0.4)] relative">
                <div class="absolute inset-0 bg-gradient-to-t from-blue-900/80 to-transparent z-10"></div>
                <img src="https://images.unsplash.com/photo-1611162617213-6d562f266557?auto=format&fit=crop&w=500&q=80" class="w-full h-full object-cover" alt="Preview">
                <div class="absolute bottom-10 left-6 z-20 text-left">
                    <div class="flex items-center space-x-2 mb-2">
                        <div class="w-8 h-8 rounded-full bg-blue-500 border-2 border-white"></div>
                        <p class="text-sm font-bold">@AI_Visionary</p>
                    </div>
                    <p class="text-xs text-gray-200 opacity-80"># 8K画质 # AI自动剪辑 # 视觉艺术</p>
                </div>
            </div>
        </div>
    </section>

    <!-- 第二屏：产品特性 (Features) -->
    <section id="features" class="py-32 px-6 max-w-7xl mx-auto">
        <div class="text-center mb-20">
            <h2 class="text-4xl md:text-6xl font-black mb-6">重新定义<span class="blue-gradient-text">创作效率</span></h2>
            <p class="text-gray-400 text-lg">将繁琐的后期交给 AI，将灵感留给自我。</p>
        </div>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-10">
            <div class="p-10 rounded-3xl glass-card group">
                <div class="w-16 h-16 bg-blue-600 rounded-2xl mb-8 flex items-center justify-center text-3xl group-hover:scale-110 transition">🪄</div>
                <h3 class="text-2xl font-bold mb-4">AI 自动剪辑</h3>
                <p class="text-gray-400 leading-relaxed">无需手动拖拽。宽视 AI 自动分析视频节奏，智能匹配卡点，一键生成电影级大片。</p>
            </div>
            <div class="p-10 rounded-3xl glass-card group">
                <div class="w-16 h-16 bg-blue-600 rounded-2xl mb-8 flex items-center justify-center text-3xl group-hover:scale-110 transition">💎</div>
                <h3 class="text-2xl font-bold mb-4">巅峰画质</h3>
                <p class="text-gray-400 leading-relaxed">支持超高码率上传与实时 AI 增强，让每一帧画面都达到 8K 工业级清晰度，定义视觉天花板。</p>
            </div>
            <div class="p-10 rounded-3xl glass-card group">
                <div class="w-16 h-16 bg-blue-600 rounded-2xl mb-8 flex items-center justify-center text-3xl group-hover:scale-110 transition">☁️</div>
                <h3 class="text-2xl font-bold mb-4">极速云上传</h3>
                <p class="text-gray-400 leading-relaxed">基于分布式存储技术，海量超高清视频秒级上传，无需等待，灵感即刻同步。</p>
            </div>
        </div>
    </section>

    <!-- 第三屏：社交生态 (Social) -->
    <section id="social" class="py-32 px-6 bg-slate-900/50">
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row items-center gap-20">
            <div class="flex-1 text-left">
                <h2 class="text-4xl md:text-6xl font-black mb-8 leading-tight">不只是观看<br><span class="blue-gradient-text">更是深度的共鸣</span></h2>
                <div class="space-y-6">
                    <div class="flex items-start space-x-4 p-4 rounded-2xl glass-card">
                        <div class="text-blue-400 font-bold text-xl">💬</div>
                        <div>
                            <h4 class="font-bold text-lg">实时智能聊天</h4>
                            <p class="text-gray-400">在视频流中无缝切换至私聊，与志同道合的创作者即时交流。</p>
                        </div>
                    </div>
                    <div class="flex items-start space-x-4 p-4 rounded-2xl glass-card">
                        <div class="text-blue-400 font-bold text-xl">🗨️</div>
                        <div>
                            <h4 class="font-bold text-lg">多维度评论区</h4>
                            <p class="text-gray-400">支持富媒体评论，让互动不仅是文字，更是灵感的碰撞。</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="flex-1 relative">
                <div class="absolute -inset-10 bg-blue-600/20 blur-3xl rounded-full"></div>
                <div class="relative glass-card p-6 rounded-[2rem] shadow-2xl w-full max-w-md">
                    <div class="space-y-4">
                        <div class="flex items-center space-x-3 p-3 bg-blue-500/20 rounded-xl border border-blue-500/30">
                            <div class="w-8 h-8 rounded-full bg-gray-600"></div>
                            <p class="text-xs"><b>张三:</b> 这段 AI 剪辑太震撼了！🔥</p>
                        </div>
                        <div class="flex items-center space-x-3 p-3 bg-white/10 rounded-xl text-right justify-end">
                            <p class="text-xs"><b>你:</b> 确实，宽视的画质无敌了 🚀</p>
                            <div class="w-8 h-8 rounded-full bg-blue-500"></div>
                        </div>
                        <div class="flex items-center space-x-3 p-3 bg-blue-500/20 rounded-xl border border-blue-500/30">
                            <div class="w-8 h-8 rounded-full bg-gray-600"></div>
                            <p class="text-xs"><b>李四:</b> 怎么申请创作者计划？</p>
                        </div>
                    </div>
                    <div class="mt-6 p-3 bg-slate-800 rounded-full text-center text-xs text-gray-400 border border-slate-700">
                        正在加载更多实时对话...
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 第四屏：创作者计划 (Creator) -->
    <section id="creator" class="py-32 px-6 text-center max-w-5xl mx-auto">
        <div class="p-20 rounded-[4rem] bg-gradient-to-br from-blue-900 via-slate-900 to-black border border-blue-500/30 relative overflow-hidden">
            <div class="absolute top-0 right-0 w-64 h-64 bg-blue-500/10 blur-3xl"></div>
            <h2 class="text-4xl md:text-6xl font-black mb-8">加入 <span class="blue-gradient-text">宽视创作者</span></h2>
            <p class="text-gray-400 text-lg mb-12 max-w-2xl mx-auto">
                我们正在寻找全球最具视觉前瞻性的创作者。提供顶级 AI 算力支持，让你的想象力在 8K 世界中肆意生长。
            </p>
            <button class="px-12 py-5 rounded-full btn-primary text-xl font-bold">
                申请入驻计划
            </button>
        </div>
    </section>

    <!-- 第五屏：下载中心 (Download) -->
    <section id="download" class="py-32 px-6 text-center">
        <h2 class="text-5xl font-black mb-16">准备好 <span class="blue-gradient-text">宽视</span> 你的世界了吗？</h2>
        <div class="flex flex-col md:flex-row justify-center items-center space-y-6 md:space-y-0 md:space-x-8">
            <div class="p-6 rounded-3xl glass-card w-64 cursor-pointer group">
                <div class="text-3xl mb-4 group-hover:scale-110 transition">🍎</div>
                <div class="text-sm text-gray-400 mb-1">Download on the</div>
                <div class="text-xl font-bold">App Store</div>
            </div>
            <div class="p-6 rounded-3xl glass-card w-64 cursor-pointer group">
                <div class="text-3xl mb-4 group-hover:scale-110 transition">🤖</div>
                <div class="text-sm text-gray-400 mb-1">Get it on</div>
                <div class="text-xl font-bold">Google Play</div>
            </div>
        </div>
    </section>

    <footer class="py-10 text-center text-gray-600 text-sm border-t border-slate-800">
        &copy; 2023 宽视 KUANSHI Inc. All rights reserved.
    </footer>

</body>
</html>
