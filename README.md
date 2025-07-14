# COCODEAR
<html lang="zh-CN">
  <head>
    <meta charset="utf-8" />
    <meta content="width=device-width, initial-scale=1.0" name="viewport" />
    <title>珂珂黛（广州）稀有皮具潮玩工作室</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link
      href="https://cdn.bootcdn.net/ajax/libs/font-awesome/6.4.0/css/all.min.css"
      rel="stylesheet"
    />
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Ma+Shan+Zheng&display=swap'); /* 引入毛笔书法字体 */
      body {
          font-family: 'Ma Shan Zheng', cursive; /* 应用毛笔书法字体 */
          background-color: #000; /* 黑色背景 */
          color: #fff; /* 白色文字 */
          overflow-x: hidden; /* 防止水平滚动 */
      }
      .text-stroke {
          -webkit-text-stroke: 1px #fff; /* 描边效果 */
          color: transparent; /* 字体透明 */
      }
      .video-container {
          position: relative;
          padding-bottom: 56.25%; /* 16:9 宽高比 */
          height: 0;
          overflow: hidden;
          max-width: 100%;
          background: #000;
      }
      .video-container iframe,
      .video-container video {
          position: absolute;
          top: 0;
          left: 0;
          width: 100%;
          height: 100%;
      }
      .gradient-overlay {
          background: linear-gradient(to bottom, rgba(0,0,0,0.8) 0%, rgba(0,0,0,0) 50%, rgba(0,0,0,0.8) 100%);
      }
      .hover-effect:hover {
          transform: scale(1.05);
          transition: transform 0.3s ease-in-out;
      }
      .button-glow {
          box-shadow: 0 0 10px rgba(255, 255, 255, 0.6), 0 0 20px rgba(255, 255, 255, 0.4), 0 0 30px rgba(255, 255, 255, 0.2);
          transition: box-shadow 0.3s ease-in-out;
      }
      .button-glow:hover {
          box-shadow: 0 0 15px rgba(255, 255, 255, 0.8), 0 0 25px rgba(255, 255, 255, 0.6), 0 0 35px rgba(255, 255, 255, 0.4);
      }
    </style>
  </head>
  <body class="bg-black text-white">
    <!-- 导航栏 -->
    <nav
      class="fixed top-0 left-0 right-0 z-50 bg-black bg-opacity-80 p-4 shadow-lg"
    >
      <div class="container mx-auto flex justify-between items-center">
        <a
          class="text-2xl font-bold text-white hover:text-gray-300 transition-colors duration-300"
          href="javascript:void(0);"
        >
          珂珂黛
        </a>
        <div class="hidden md:flex space-x-6">
          <!-- 原有导航链接，在桌面端隐藏 -->
        </div>
        <div class="md:hidden flex items-center">
          <button
            class="text-white text-2xl focus:outline-none"
            id="mobile-menu-button"
          >
            <i class="fas fa-bars"> </i>
          </button>
        </div>
      </div>
    </nav>
    <!-- 移动端侧边栏菜单 -->
    <div
      class="fixed top-0 right-0 w-64 h-full bg-gray-900 bg-opacity-95 backdrop-blur-md z-50 transform translate-x-full transition-transform duration-300 ease-in-out p-4 pt-20 overflow-y-auto"
      id="mobile-menu"
    >
      <button
        class="absolute top-4 right-4 text-white text-3xl focus:outline-none"
        id="close-menu-button"
      >
        <i class="fas fa-times"> </i>
      </button>
      <nav class="flex flex-col space-y-4">
        <a
          class="text-white text-lg hover:text-gray-300 transition-colors duration-300 py-2"
          href="#brand-concept"
        >
          品牌理念
        </a>
        <a
          class="text-white text-lg hover:text-gray-300 transition-colors duration-300 py-2"
          href="#brand-story"
        >
          品牌故事
        </a>
        <a
          class="text-white text-lg hover:text-gray-300 transition-colors duration-300 py-2"
          href="#core-values"
        >
          核心价值
        </a>
        <!-- 更多内容下拉菜单 -->
        <div class="relative">
          <button
            class="w-full text-left text-white text-lg hover:text-gray-300 transition-colors duration-300 py-2 flex justify-between items-center"
            id="more-content-toggle"
          >
            更多内容
            <i class="fas fa-chevron-down ml-1 text-xs"> </i>
          </button>
          <div
            class="hidden flex-col space-y-2 pl-4 mt-2"
            id="more-content-dropdown"
          >
            <a
              class="block px-4 py-2 text-white hover:bg-gray-700 rounded-md"
              href="#video-section"
            >
              包包制作视频
            </a>
            <a
              class="block px-4 py-2 text-white hover:bg-gray-700 rounded-md"
              href="#contact-us"
            >
              联系我们
            </a>
          </div>
        </div>
      </nav>
    </div>
    <!-- 品牌理念海报 -->
    <section
      class="relative h-screen flex items-center justify-center overflow-hidden"
      data-ytextravalue="extra-kh8jgfhjo"
      id="brand-concept"
    >
      <img
        alt="品牌理念海报"
        class="absolute inset-0 w-full h-full object-cover opacity-70"
        data-ytindex="0"
        data-ytoriginindex="0"
        src="https://design.gemcoder.com/staticResource/echoAiSystemImages/4782acdab8bbd3bd570c6c43a80a562d.png"
      />
      <div
        class="absolute inset-0 bg-gradient-to-t from-black via-transparent to-black opacity-80"
        data-ytindex="1"
        data-ytoriginindex="1"
        data-ytparentvalue="extra-kh8jgfhjo"
      ></div>
      <div
        class="relative z-10 text-center p-4"
        data-ytindex="2"
        data-ytoriginindex="2"
      >
        <h1
          class="text-5xl md:text-7xl lg:text-8xl font-extrabold text-white text-stroke mb-4 leading-tight"
          style='font-family: "Ma Shan Zheng", cursive;'
          data-yteditvalue="时光作刃  琢物成珂"
        >
          时光作刃  琢物成珂
        </h1>
        <p
          class="text-2xl md:text-3xl lg:text-4xl font-semibold text-white drop-shadow-lg"
        >
          「宠你的爱，珂珂黛！」
        </p>
        <a
          class="mt-8 inline-block bg-white text-black px-8 py-4 rounded-full text-lg font-bold uppercase tracking-wider hover:bg-gray-300 transition-all duration-300 button-glow"
          href="#brand-story"
        >
          探索更多
          <i class="fas fa-arrow-down ml-2"> </i>
        </a>
      </div>
    </section>
    <!-- 品牌故事区 -->
    <section class="py-16 md:py-24 bg-black relative z-20" id="brand-story">
      <div
        class="container mx-auto px-4 md:px-8 lg:px-16 flex flex-col md:flex-row items-center"
      >
        <div class="md:w-1/2 mb-8 md:mb-0 md:pr-12">
          <h2
            class="text-4xl md:text-5xl font-bold mb-6 text-center md:text-left"
          >
            品牌故事
          </h2>
          <p
            class="text-lg md:text-xl leading-relaxed text-gray-300 text-justify"
          >
            珂珂黛，源自对稀有皮具工艺的极致追求。我们以专业匠心和创新设计，将顶级鳄鱼皮、蜥蜴皮等稀有皮料，融入潮玩箱包与皮具创作中，让每一件作品不仅是实用之选，更是承载情感的艺术品
          </p>
        </div>
        <div class="md:w-1/2">
          <img
            alt="皮具制作细节"
            class="w-full h-auto rounded-lg shadow-2xl hover-effect"
            src="https://design.gemcoder.com/staticResource/echoAiSystemImages/4f29717b248fb3f54020abf2e0f29cb5.png"
          />
        </div>
      </div>
    </section>
    <!-- 核心价值展示区 -->
    <section class="py-8 md:py-12 bg-gray-900 relative z-20" id="core-values">
      <div class="container mx-auto px-4 md:px-8 lg:px-16">
        <h2 class="text-4xl md:text-5xl font-bold mb-12 text-center">
          核心价值
        </h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <div
            class="bg-gray-800 p-8 rounded-lg shadow-xl text-center hover-effect border border-gray-700"
          >
            <i class="fas fa-gem text-5xl text-yellow-400 mb-4"> </i>
            <h3 class="text-2xl font-semibold mb-4">稀有工艺</h3>
            <p class="text-gray-300">
              32年传承稀有皮具制造技术，打造独一无二的质感与触感。
            </p>
          </div>
          <div
            class="bg-gray-800 p-8 rounded-lg shadow-xl text-center hover-effect border border-gray-700"
          >
            <i class="fas fa-dice-d6 text-5xl text-purple-400 mb-4"> </i>
            <h3 class="text-2xl font-semibold mb-4">潮玩基因</h3>
            <p class="text-gray-300">
              结合盲盒、IP联名等潮流玩法，让皮具成为收藏级潮物。
            </p>
          </div>
          <div
            class="bg-gray-800 p-8 rounded-lg shadow-xl text-center hover-effect border border-gray-700"
          >
            <i class="fas fa-heart text-5xl text-red-400 mb-4"> </i>
            <h3 class="text-2xl font-semibold mb-4">情绪陪伴</h3>
            <p class="text-gray-300">
              不止于功能，更赋予每一件皮具故事与温度，成为你的生活挚友。
            </p>
          </div>
        </div>
        <div class="mt-12 text-center">
          <h3 class="text-3xl font-bold mb-4">品牌承诺</h3>
          <p class="text-xl text-gray-300">
            用专业心，做专业事——让稀有皮具走进你的日常，宠你所爱！
          </p>
        </div>
      </div>
    </section>
    <!-- 视频播放区域 -->
    <section class="py-16 md:py-24 bg-black relative z-20" id="video-section">
      <div class="container mx-auto px-4 md:px-8 lg:px-16">
        <h2 class="text-4xl md:text-5xl font-bold mb-12 text-center">
          皮具制作与品牌故事
        </h2>
        <div
          class="relative w-full max-w-4xl mx-auto rounded-xl overflow-hidden shadow-2xl border-4 border-white transform rotate-3 hover:rotate-0 transition-transform duration-500"
        >
          <div class="video-container">
            <!-- 示例视频，请替换为实际视频链接 -->
            <iframe
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
              frameborder="0"
              src="https://www.youtube.com/embed/o_Q_4wagJ0Q?autoplay=0&controls=1&modestbranding=1&rel=0"
            >
            </iframe>
          </div>
          <div
            class="absolute inset-0 gradient-overlay pointer-events-none"
          ></div>
        </div>
        <p class="text-center text-lg md:text-xl mt-8 text-gray-300">
          探索珂珂黛皮具背后的精湛工艺与匠心精神。
        </p>
      </div>
    </section>
    <!-- 联系我们区域 -->
    <section
      class="py-12 bg-gray-900 text-center relative z-20"
      id="contact-us"
    >
      <div class="container mx-auto px-4">
        <h2 class="text-4xl md:text-5xl font-bold mb-8 text-center">
          联系我们
        </h2>
        <div
          class="flex justify-center space-x-4 md:space-x-8"
          id="social-media-links"
        >
          <!-- 社交媒体链接将由 JavaScript 动态加载 -->
        </div>
      </div>
    </section>
    <!-- 品牌宣言（底部居中） -->
    <footer class="py-12 bg-gray-900 text-center relative z-20">
      <div class="container mx-auto px-4">
        <p class="text-2xl md:text-3xl font-bold text-white drop-shadow-lg">
          珂珂黛——背得起山高水长，放得下诗与远方
        </p>
        <div class="mt-6 text-gray-400 text-sm">
          © 2023 珂珂黛（广州）稀有皮具潮玩工作室. All rights reserved.
        </div>
      </div>
    </footer>
    <script>
      // 定义要劫持的属性
      var ytCustomProperties = ['textContent', 'innerText'];
      ytCustomProperties.forEach(function (prop) {
        var descriptor = Object.getOwnPropertyDescriptor(Element.prototype, prop) || Object.getOwnPropertyDescriptor(Node.prototype, prop);
        if (descriptor && descriptor.set && descriptor.get) {
          var originalGet = descriptor.get; // 保存原生 getter
          var originalSet = descriptor.set;
          Object.defineProperty(Element.prototype, prop, {
            get: function get() {
              return originalGet.call(this); // 保持原生 getter 逻辑
            },
            set: function set(value) {
              // 优先取 data-yteditvalue，否则用传入的 value
              var finalValue = this.dataset.yteditvalue ?? value;
              originalSet.call(this, finalValue);
            },
            configurable: true
          });
        }
      });
      // 保存原生方法
      var nativeElementQuerySelector = Element.prototype.querySelector;
      var nativeDocumentQuerySelector = Document.prototype.querySelector;
      function ytCustomQuerySelector(selector) {
        // 第二步：尝试用选择器获取DOM元素
        // 执行原生选择器查询
        var foundElement = this === document ? nativeDocumentQuerySelector.call(this, selector) : nativeElementQuerySelector.call(this, selector);
        if (foundElement) {
          // 设置属性
          if (!foundElement.hasAttribute('data-selectorname')) {
            foundElement.setAttribute('data-selectorname', selector);
          }
          // 第三步：直接返回找到的元素
          return foundElement;
        }
        // 如果通过选择器没找到，尝试通过data-selectorName属性查找
        var allElements = document.querySelectorAll('[data-selectorname]');
        for (var i = 0; i < allElements.length; i++) {
          if (allElements[i].getAttribute('data-selectorname') === selector) {
            return allElements[i];
          }
        }
        // 如果都没找到，返回null
        return null;
      }
      // 如果需要也重写querySelectorAll，可以类似实现
      // 重写原生的querySelector
      Document.prototype.querySelector = ytCustomQuerySelector;
      Element.prototype.querySelector = ytCustomQuerySelector;
      var nativeElementInsertBefore = Element.prototype.insertBefore;
      function ytCustomInsertBefore(newNode, referenceNode) {
        // 当前元素作为默认父元素
        var defaultParentNode = this;
        // 检查参考节点是否存在
        if (!referenceNode) {
          // 如果没有提供参考节点，直接添加到末尾
          return nativeElementInsertBefore.call(defaultParentNode, newNode, null);
        }
        // 检查参考节点是否仍然是父节点的直接子节点
        if (referenceNode.parentNode === defaultParentNode) {
          // 正常情况：参考节点仍在父节点下，直接插入
          return nativeElementInsertBefore.call(defaultParentNode, newNode, referenceNode);
        }
        // 检查参考节点是否有 data-ytparentvalue 属性（被移动出去的节点）
        var referenceParentValue = referenceNode.getAttribute('data-ytparentvalue');
        if (referenceParentValue) {
          // 查找具有匹配 data-ytextravalue 的父元素
          var actualParentNode = document.querySelector('[data-ytextravalue="' + referenceParentValue + '"]');
          if (actualParentNode) {
            // 获取参考节点原来的索引位置
            var originalIndex = referenceNode.getAttribute('data-ytoriginindex');
            if (originalIndex !== null && !isNaN(originalIndex)) {
              // 获取实际父节点当前的所有子节点
              var children = Array.from(actualParentNode.children);
              // 查找应该插入的位置
              for (var i = 0; i < children.length; i++) {
                var child = children[i];
                var childOriginalIndex = child.getAttribute('data-ytoriginindex');
                // 如果子节点有原始索引，并且比参考节点的原始索引大
                if (childOriginalIndex !== null && !isNaN(childOriginalIndex)) {
                  if (parseInt(childOriginalIndex) > parseInt(originalIndex)) {
                    // 找到第一个索引更大的节点，插入到它前面
                    return nativeElementInsertBefore.call(actualParentNode, newNode, child);
                  }
                }
              }
              // 如果没有找到更大的索引，插入到最后
              return nativeElementInsertBefore.call(actualParentNode, newNode, null);
            }
            // 没有原始索引信息，插入到实际父元素的最后
            return nativeElementInsertBefore.call(actualParentNode, newNode, null);
          }
        }
        // 默认情况：插入到当前父元素的最后
        return nativeElementInsertBefore.call(defaultParentNode, newNode, null);
      }
      // 重写原生 insertBefore 方法
      Element.prototype.insertBefore = ytCustomInsertBefore;
      // 需要给新添加的a标签跳转链接加入一些必要的样式 保证加入后不影响原来的布局
      function addUniqueStyle(cssText) {
        var id = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : 'custom-style';
        var targetDom = document.getElementById(id);
        if (targetDom && targetDom.tagName === 'STYLE') return; // 已存在则跳过
        var style = document.createElement('style');
        style.id = id;
        style.innerHTML = cssText;
        document.head.appendChild(style);
      }
      addUniqueStyle('.yt-a-defalut-link[custom-a="true"] > * { margin:0;flex:1; }');
      // 平滑滚动到锚点
      document.querySelectorAll('a[href^="#"]').forEach(function (anchor) {
        anchor.addEventListener('click', function (e) {
          e.preventDefault();
          document.querySelector(this.getAttribute('href')).scrollIntoView({
            behavior: 'smooth'
          });
        });
      });
      // 页面加载时初始化渲染
      document.addEventListener('DOMContentLoaded', function () {
        // 可以在这里添加其他初始化逻辑，例如动画效果等
        console.log('页面加载完成，珂珂黛欢迎您！');
        loadSocialMediaLinks();
        var mobileMenuButton = document.getElementById('mobile-menu-button');
        var closeMenuButton = document.getElementById('close-menu-button');
        var mobileMenu = document.getElementById('mobile-menu');
        var moreContentToggle = document.getElementById('more-content-toggle');
        var moreContentDropdown = document.getElementById('more-content-dropdown');
        var mobileMenuLinks = mobileMenu.querySelectorAll('a[href^="#"]'); // 获取所有锚点链接
        // 打开移动菜单
        if (mobileMenuButton) {
          mobileMenuButton.addEventListener('click', function () {
            mobileMenu.classList.remove('translate-x-full');
            mobileMenu.classList.add('translate-x-0');
          });
        }
        // 关闭移动菜单
        if (closeMenuButton) {
          closeMenuButton.addEventListener('click', function () {
            mobileMenu.classList.remove('translate-x-0');
            mobileMenu.classList.add('translate-x-full');
          });
        }
        // 切换“更多内容”下拉菜单
        if (moreContentToggle) {
          moreContentToggle.addEventListener('click', function () {
            moreContentDropdown.classList.toggle('hidden');
            moreContentToggle.querySelector('i').classList.toggle('fa-chevron-down');
            moreContentToggle.querySelector('i').classList.toggle('fa-chevron-up');
          });
        }
        // 点击菜单链接后关闭菜单
        mobileMenuLinks.forEach(function (link) {
          link.addEventListener('click', function () {
            mobileMenu.classList.remove('translate-x-0');
            mobileMenu.classList.add('translate-x-full');
            // 如果是“更多内容”的子链接，确保下拉菜单收起
            if (!moreContentDropdown.classList.contains('hidden')) {
              moreContentDropdown.classList.add('hidden');
              moreContentToggle.querySelector('i').classList.remove('fa-chevron-up');
              moreContentToggle.querySelector('i').classList.add('fa-chevron-down');
            }
          });
        });
      });
      function loadSocialMediaLinks() {
        var socialMediaData = [{
          iconClass: "fab fa-tiktok",
          colorClass: "text-white",
          name: "抖音"
        }, {
          iconClass: "fab fa-weixin",
          colorClass: "text-green-400",
          name: "微信"
        }, {
          iconClass: "fab fa-qq",
          colorClass: "text-blue-400",
          name: "QQ"
        }, {
          iconClass: "fas fa-phone",
          colorClass: "text-yellow-400",
          name: "手机"
        }, {
          iconClass: "fas fa-envelope",
          colorClass: "text-red-400",
          name: "邮箱"
        }];
        var container = document.getElementById('social-media-links');
        if (container) {
          container.innerHTML = ''; // 清空现有内容
          socialMediaData.forEach(function (item) {
            var div = document.createElement('div');
            div.className = 'flex flex-col items-center p-2 hover-effect'; // 调整 padding
            div.innerHTML = "\n        <i class=\"".concat(item.iconClass, " text-3xl md:text-4xl ").concat(item.colorClass, "\"></i>\n        <p class=\"text-gray-300 text-sm md:text-base mt-2\">").concat(item.name, "</p>\n      ");
            container.appendChild(div);
          });
        }
      }
    </script>
  </body>
</html>
