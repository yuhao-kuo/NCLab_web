---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: 謝師宴.jpg
widget1:
  title: "朱紹儀 教授"
  url: "http://www.ec.kuas.edu.tw/staff/朱紹儀/5/"
  image: "朱紹儀snap0143.jpg"
  text: 電子郵件：erwinchu@nkust.edu.tw<br>分機：15661<br>學歷：台灣大學 電機工程 博士<br>領域：<br>計算機網路<br>通訊系統<br>編碼理論<br>FPGA演算法實作
widget2:
  title: "劉炳宏 教授"
  url: "http://www.ec.kuas.edu.tw/staff/劉炳宏/"
  image: "劉炳宏1.jpg"
  text: 電子郵件：bhliu@nkust.edu.tw<br>分機：15610<br>學歷：清華大學 資訊工程 博士<br>領域：<br>無線感測網路<br>行動隨意網路<br>行動計算<br>分散式計算<br>演算法分析與設計

widget3:
  title: "謝慶發 助理教授"
  url: "http://www.ec.kuas.edu.tw/staff/謝慶發chin-fa-hsieh/"
  image: "Chin-Fa-Hsieh-e1508811950459.jpg"
  text: 電子郵件：cfhsieh@nkust.edu.tw<br>分機：15672<br>學歷：中央大學 電機工程 博士<br>領域：<br>FPGA電路設計<br>數位IC設計<br>嵌入式系統<br>影像處理與視訊壓縮

#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: '/info'
  text: More about our Network Computer Lab >
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
