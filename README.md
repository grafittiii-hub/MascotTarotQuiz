+   1 # ✦ 邂逅心靈 ✦ 你的塔羅啟示
+   2 
+   3 A beautiful, mystical tarot card quiz application that guides users through a personalized journey to discover their spiritual revelation from the 22 Major Arcana cards.
+   4 
+   5 ![Tarot Quiz Preview](https://pfst.cf2.poecdn.net/base/image/1baebbfe40cc9da5b4e45eb79ed19ffe08c766f37c81e1caacb265d1a7c2b13d?w=4096&h=4096)
+   6 
+   7 ## ✨ Features
+   8 
+   9 - 🌍 **Bilingual Support** - Seamlessly switch between Chinese (Traditional) and English
+  10 - 📱 **Responsive Design** - Beautiful experience on both mobile and desktop devices
+  11 - 🌙 **Dark Mode** - Automatic dark/light mode based on system preferences
+  12 - 🎴 **Card Collection** - Unlock and collect all 22 Major Arcana cards
+  13 - 🖼️ **Image Generation** - Save and share your tarot results as images
+  14 - ⚡ **Optimized Loading** - Fast loading with progress tracking and image preloading
+  15 - ✨ **Mystical UI** - Cosmic starfield background with glowing animations
+  16 
+  17 ## 🎮 How to Play
+  18 
+  19 1. Click **"開始探索"** (Start Exploring) to begin your journey
+  20 2. Answer 4 mystical questions that resonate with your current state
+  21 3. Discover your personalized tarot card from the Major Arcana
+  22 4. Save your result, share it, or explore your card collection gallery
+  23 
+  24 ## 🚀 Quick Start
+  25 
+  26 ### Option 1: Direct Use
+  27 Simply open `index.html` in a modern web browser. No build process or dependencies required!
+  28 
+  29 ### Option 2: GitHub Pages (Recommended for Sharing)
+  30 1. Fork this repository
+  31 2. Go to Settings → Pages
+  32 3. Select "main" branch and save
+  33 4. Your quiz will be live at `https://[your-username].github.io/[repo-name]/`
+  34 
+  35 ### Option 3: Local Server
+  36 ```bash
+  37 # Using Python 3
+  38 python -m http.server 8000
+  39 
+  40 # Using Node.js
+  41 npx serve
+  42 
+  43 # Then open http://localhost:8000 in your browser
+  44 ```
+  45 
+  46 ## 🔧 Customization
+  47 
+  48 ### Update Share Link
+  49 Before deploying, update the share link in `index.html`:
+  50 
+  51 ```javascript
+  52 // Find this section around line 3235
+  53 // ========== INSERT YOUR SHARE LINK HERE ==========
+  54 const SHARE_LINK = 'https://your-domain.com/your-quiz-link';
+  55 // ==================================================
+  56 ```
+  57 
+  58 ### Update GitHub Link
+  59 Update the GitHub repository link in the header comment:
+  60 
+  61 ```javascript
+  62 // Around line 1797
+  63 * GitHub: https://github.com/[YOUR_USERNAME]/[YOUR_REPO]
+  64 ```
+  65 
+  66 ### Customize Meta Tags
+  67 Update Open Graph meta tags for better social sharing (lines 13-23):
+  68 
+  69 ```html
+  70 <meta property="og:url" content="https://your-domain.com">
+  71 <meta property="og:image" content="your-preview-image-url">
+  72 ```
+  73 
+  74 ## 📋 Browser Support
+  75 
+  76 - ✅ Chrome/Edge (v90+)
+  77 - ✅ Firefox (v88+)
+  78 - ✅ Safari (v14+)
+  79 - ✅ Mobile browsers (iOS Safari, Chrome Mobile)
+  80 
+  81 ## 🎨 Technologies Used
+  82 
+  83 - **HTML5** - Semantic structure
+  84 - **CSS3** - Custom properties, animations, gradients
+  85 - **Vanilla JavaScript** - No frameworks, pure performance
+  86 - **Google Fonts** - Cinzel Decorative, Philosopher, Noto Serif TC
+  87 - **html2canvas** - Image generation for sharing
+  88 - **QRCode.js** - QR code generation for collection images
+  89 
+  90 ## 📱 Mobile Optimization
+  91 
+  92 - Touch-friendly button sizes (minimum 44x44px)
+  93 - Optimized font sizes (16px+ to prevent zoom)
+  94 - Responsive layout with flexbox
+  95 - Haptic feedback on supported devices
+  96 - Disabled image long-press save
+  97 
+  98 ## 🌟 Card Collection System
+  99 
+ 100 Unlock all 22 Major Arcana cards by completing the quiz multiple times:
+ 101 
+ 102 - 0 The Fool
+ 103 - I The Magician
+ 104 - II The High Priestess
+ 105 - III The Empress
+ 106 - IV The Emperor
+ 107 - V The Hierophant
+ 108 - VI The Lovers
+ 109 - VII The Chariot
+ 110 - VIII Strength
+ 111 - IX The Hermit
+ 112 - X Wheel of Fortune
+ 113 - XI Justice
+ 114 - XII The Hanged Man
+ 115 - XIII Death
+ 116 - XIV Temperance
+ 117 - XV The Devil
+ 118 - XVI The Tower
+ 119 - XVII The Star
+ 120 - XVIII The Moon
+ 121 - XIX The Sun
+ 122 - XX Judgement
+ 123 - XXI The World
+ 124 
+ 125 ## 🎯 Performance Features
+ 126 
+ 127 - **Image Compression** - Automatic compression to 400px width at 75% quality
+ 128 - **Lazy Loading** - Images load in the background without blocking UI
+ 129 - **Memory Management** - Efficient caching system for repeated plays
+ 130 - **Optimized Animations** - CSS-only animations for 60fps performance
+ 131 - **Preload Critical Fonts** - Google Fonts with `display=block`
+ 132 
+ 133 ## 📄 License
+ 134 
+ 135 This project is created for the **孫孫暉日塔羅牌組** (SunSun Tarot Deck).
+ 136 
+ 137 Feel free to use this code for personal or educational purposes. If you use it for your own project, please give credit and link back to the original.
+ 138 
+ 139 ## 🙏 Credits
+ 140 
+ 141 - **Tarot Card Art**: 孫孫暉日塔羅牌組 by @grafittiii_uru
+ 142 - **Design & Development**: Created with Claude and AI
+ 143 - **Inspiration**: The mystical wisdom of the Major Arcana
+ 144 
+ 145 ## 📞 Contact & Social
+ 146 
+ 147 - **Instagram/Threads**: [@grafittiii_uru](https://www.threads.com/@grafittiii_uru)
+ 148 - **Pre-order Deck**: [Google Form](https://forms.gle/ZErmb74tu3KrbiEY9)
+ 149 - **Demo Video**: [Threads Post](https://www.threads.com/@grafittiii_uru/post/DQ8z1FUEYiO)
+ 150 
+ 151 ---
+ 152 
+ 153 Made with ✨ and cosmic energy ☽ ✦ ☾
