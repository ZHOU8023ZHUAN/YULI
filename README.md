# <!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>大足石刻 - 2025妇女节女性免票活动</title>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+SC:wght@400;500;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#FF6B8B',
                        secondary: '#FF8E9E',
                        accent: '#FFD1DC',
                        dark: '#5E2D3A',
                    },
                    fontFamily: {
                        sans: ['Noto Sans SC', 'sans-serif'],
                        display: ['Playfair Display', 'serif'],
                    },
                    boxShadow: {
                        'glass': '0 4px 30px rgba(0, 0, 0, 0.1)',
                    },
                    backdropBlur: {
                        'glass': '8px',
                    },
                }
            }
        }
    </script>
    <style>
        .glass-effect {
            background: rgba(255, 255, 255, 0.7);
            backdrop-filter: blur(8px);
            -webkit-backdrop-filter: blur(8px);
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
        }
        .hero-image {
            background-image: linear-gradient(to bottom, rgba(255, 214, 220, 0.3), rgba(255, 214, 220, 0.7)), url('https://images.unsplash.com/photo-1596422846543-75c6fc197f07?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2560&q=80');
            background-size: cover;
            background-position: center;
        }
        .qr-code {
            transition: all 0.3s ease;
        }
        .qr-code:hover {
            transform: scale(1.05);
        }
        .feature-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body class="font-sans bg-gradient-to-b from-accent to-white text-dark">
    <!-- 导航栏 -->
    <nav class="glass-effect fixed w-full z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16 items-center">
                <div class="flex items-center">
                    <div class="flex-shrink-0 flex items-center">
                        <i class="fas fa-landmark text-primary text-2xl mr-2"></i>
                        <span class="text-xl font-bold text-dark">大足石刻</span>
                    </div>
                </div>
                <div class="hidden md:block">
                    <div class="ml-10 flex items-center space-x-4">
                        <a href="#" class="px-3 py-2 rounded-md text-sm font-medium hover:bg-primary hover:text-white transition">首页</a>
                        <a href="#" class="px-3 py-2 rounded-md text-sm font-medium hover:bg-primary hover:text-white transition">景点介绍</a>
                        <a href="#" class="px-3 py-2 rounded-md text-sm font-medium hover:bg-primary hover:text-white transition">活动详情</a>
                        <a href="#" class="px-3 py-2 rounded-md text-sm font-medium hover:bg-primary hover:text-white transition">交通指南</a>
                        <a href="#" class="px-3 py-2 rounded-md text-sm font-medium bg-primary text-white rounded-full px-4">立即预约</a>
                    </div>
                </div>
                <div class="md:hidden">
                    <button class="inline-flex items-center justify-center p-2 rounded-md text-dark">
                        <i class="fas fa-bars"></i>
                    </button>
                </div>
            </div>
        </div>
    </nav>

    <!-- 英雄区域 -->
    <div class="hero-image pt-24 pb-32 relative overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="glass-effect rounded-xl p-8 max-w-2xl">
                <h1 class="text-4xl md:text-5xl font-display font-bold mb-4">2025妇女节特别活动</h1>
                <p class="text-xl mb-6">3月8日当天，所有女性游客可享受大足石刻免门票优惠</p>
                <div class="flex flex-wrap gap-4">
                    <a href="#" class="bg-primary hover:bg-secondary text-white font-bold py-3 px-6 rounded-full transition transform hover:scale-105">立即预约</a>
                    <a href="#" class="border-2 border-primary text-primary hover:bg-primary hover:text-white font-bold py-3 px-6 rounded-full transition transform hover:scale-105">了解更多</a>
                </div>
            </div>
        </div>
    </div>

    <!-- 介绍模块 -->
    <section class="py-16 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-display font-bold mb-4">世界文化遗产 · 大足石刻</h2>
                <div class="w-20 h-1 bg-primary mx-auto mb-6"></div>
                <p class="max-w-3xl mx-auto text-lg">大足石刻位于重庆市大足区，是唐、宋时期石窟造像艺术的代表作，1999年被联合国教科文组织列入《世界遗产名录》。其中以宝顶山、北山、南山、石门山、石篆山"五山"为代表。</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <div class="feature-card bg-white rounded-xl p-8 shadow-lg transition duration-300">
                    <div class="text-primary text-4xl mb-4">
                        <i class="fas fa-hands-praying"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">千手观音</h3>
                    <p class="text-gray-600">宝顶山第8号龛的千手观音造像，是中国最大的集雕刻、彩绘、贴金于一体的摩崖石刻造像，被誉为"国宝中的国宝"。</p>
                </div>
                
                <div class="feature-card bg-white rounded-xl p-8 shadow-lg transition duration-300">
                    <div class="text-primary text-4xl mb-4">
                        <i class="fas fa-yin-yang"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">佛教艺术</h3>
                    <p class="text-gray-600">大足石刻以佛教题材为主，儒、道教造像并陈，展示了中国晚期石窟艺术风格及民间宗教信仰的发展变化。</p>
                </div>
                
                <div class="feature-card bg-white rounded-xl p-8 shadow-lg transition duration-300">
                    <div class="text-primary text-4xl mb-4">
                        <i class="fas fa-history"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">千年历史</h3>
                    <p class="text-gray-600">大足石刻始凿于初唐，历经五代，盛于两宋，延续至明清，历时千余载，是中国石窟艺术史上的最后一座丰碑。</p>
                </div>
            </div>
        </div>
    </section>

    <!-- 活动详情 -->
    <section class="py-16 bg-gradient-to-b from-white to-accent">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="glass-effect rounded-xl overflow-hidden shadow-lg">
                <div class="md:flex">
                    <div class="md:w-1/2 p-8 md:p-12 bg-primary text-white">
                        <h2 class="text-3xl font-display font-bold mb-6">妇女节特别活动</h2>
                        <ul class="space-y-4">
                            <li class="flex items-start">
                                <i class="fas fa-calendar-check text-2xl mr-4 mt-1"></i>
                                <div>
                                    <h3 class="font-bold text-lg">活动时间</h3>
                                    <p>2025年3月8日（全天）</p>
                                </div>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-ticket-alt text-2xl mr-4 mt-1"></i>
                                <div>
                                    <h3 class="font-bold text-lg">优惠内容</h3>
                                    <p>所有女性游客免门票（原价120元）</p>
                                </div>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-map-marked-alt text-2xl mr-4 mt-1"></i>
                                <div>
                                    <h3 class="font-bold text-lg">参观范围</h3>
                                    <p>宝顶山石刻景区、北山石刻景区</p>
                                </div>
                            </li>
                        </ul>
                    </div>
                    <div class="md:w-1/2 p-8 md:p-12 bg-white">
                        <h2 class="text-3xl font-display font-bold mb-6 text-dark">参观须知</h2>
                        <div class="space-y-4 text-gray-700">
                            <div class="flex items-start">
                                <i class="fas fa-info-circle text-primary text-xl mr-4 mt-1"></i>
                                <p>请携带有效身份证件（女性游客需验证性别）</p>
                            </div>
                            <div class="flex items-start">
                                <i class="fas fa-clock text-primary text-xl mr-4 mt-1"></i>
                                <p>开放时间：8:30-17:00（16:30停止入园）</p>
                            </div>
                            <div class="flex items-start">
                                <i class="fas fa-route text-primary text-xl mr-4 mt-1"></i>
                                <p>建议游览时间：3-4小时</p>
                            </div>
                            <div class="flex items-start">
                                <i class="fas fa-car text-primary text-xl mr-4 mt-1"></i>
                                <p>景区停车场收费：10元/车/天</p>
                            </div>
                        </div>
                        <div class="mt-8">
                            <a href="#" class="inline-block bg-primary hover:bg-secondary text-white font-bold py-3 px-8 rounded-full transition transform hover:scale-105">立即预约</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 图片展示 -->
    <section class="py-16 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-display font-bold mb-4">艺术瑰宝 · 精彩瞬间</h2>
                <div class="w-20 h-1 bg-primary mx-auto"></div>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="rounded-xl overflow-hidden shadow-lg">
                    <img src="https://images.unsplash.com/photo-1596422846543-75c6fc197f07?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="千手观音" class="w-full h-64 object-cover">
                    <div class="p-6">
                        <h3 class="font-bold text-xl mb-2">千手观音</h3>
                        <p class="text-gray-600">宝顶山第8号龛，南宋作品，中国最大的千手观音造像。</p>
                    </div>
                </div>
                
                <div class="rounded-xl overflow-hidden shadow-lg">
                    <img src="https://images.unsplash.com/photo-1533856493584-0c6ca8c9d87e?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="卧佛" class="w-full h-64 object-cover">
                    <div class="p-6">
                        <h3 class="font-bold text-xl mb-2">卧佛</h3>
                        <p class="text-gray-600">宝顶山第11号龛，全长31米，中国最大的半身卧佛。</p>
                    </div>
                </div>
                
                <div class="rounded-xl overflow-hidden shadow-lg">
                    <img src="https://images.unsplash.com/photo-1603468623306-2b4295b1a0a5?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="六道轮回" class="w-full h-64 object-cover">
                    <div class="p-6">
                        <h3 class="font-bold text-xl mb-2">六道轮回</h3>
                        <p class="text-gray-600">宝顶山第3号龛，佛教轮回思想的立体图解。</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA区域 -->
    <section class="py-20 bg-gradient-to-r from-primary to-secondary">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-3xl md:text-4xl font-display font-bold text-white mb-6">2025年3月8日，邀您共赏千年石刻艺术</h2>
            <p class="text-xl text-white mb-8 max-w-3xl mx-auto">在这个特别的妇女节，我们诚邀所有女性朋友免费参观大足石刻，感受世界文化遗产的魅力。</p>
            <a href="#" class="inline-block bg-white hover:bg-gray-100 text-primary font-bold py-4 px-12 rounded-full text-lg transition transform hover:scale-105">立即预约免费门票</a>
        </div>
    </section>

    <!-- 页脚 -->
    <footer class="bg-dark text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <div class="flex items-center mb-4">
                        <i class="fas fa-landmark text-primary text-2xl mr-2"></i>
                        <span class="text-xl font-bold">大足石刻</span>
                    </div>
                    <p class="text-gray-300">世界文化遗产 · 国家5A级旅游景区</p>
                </div>
                
                <div>
                    <h3 class="text-lg font-bold mb-4">快速链接</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-300 hover:text-primary transition">景区介绍</a></li>
                        <li><a href="#" class="text-gray-300 hover:text-primary transition">参观指南</a></li>
                        <li><a href="#" class="text-gray-300 hover:text-primary transition">交通路线</a></li>
                        <li><a href="#" class="text-gray-300 hover:text-primary transition">常见问题</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-lg font-bold mb-4">联系我们</h3>
                    <ul class="space-y-2 text-gray-300">
                        <li class="flex items-start">
                            <i class="fas fa-map-marker-alt mt-1 mr-2 text-primary"></i>
                            <span>重庆市大足区宝顶镇</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-phone-alt mt-1 mr-2 text-primary"></i>
                            <span>023-43722268</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-envelope mt-1 mr-2 text-primary"></i>
                            <span>info@dazushike.com</span>
                        </li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-lg font-bold mb-4">关注我们</h3>
                    <div class="flex space-x-4 mb-4">
                        <a href="#" class="text-gray-300 hover:text-primary transition"><i class="fab fa-weixin text-2xl"></i></a>
                        <a href="#" class="text-gray-300 hover:text-primary transition"><i class="fab fa-weibo text-2xl"></i></a>
                        <a href="#" class="text-gray-300 hover:text-primary transition"><i class="fab fa-douyin text-2xl"></i></a>
                        <a href="#" class="text-gray-300 hover:text-primary transition"><i class="fab fa-qq text-2xl"></i></a>
                    </div>
                    <div class="text-sm text-gray-400">
                        <p>© 2024 大足石刻景区 版权所有</p>
                    </div>
                </div>
            </div>
        </div>
    </footer>

    <!-- 浮动二维码 -->
    <div class="fixed bottom-6 right-6 z-50 qr-code">
        <div class="bg-white p-3 rounded-lg shadow-xl">
            <img src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://dazushike.com/2025-women-day" alt="扫码关注" class="w-24 h-24">
            <p class="text-xs text-center mt-1 text-gray-600">扫码预约/分享</p>
        </div>
    </div>
</body>
</html>
