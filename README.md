
<p align="center">
  <img src =https://user-images.githubusercontent.com/67901472/147389469-276b1429-11c8-4bca-a37c-f926ad75e4d4.gif>
</p>


<html>
  <head>
    <style>
      
      html {
  height: 100%;
}
body {
  display: flex;
  height: 100%;
  background-color: #333;
}
.word {
  margin: auto;
  color: white;
  font: 700 normal 2.5em 'tahoma';
  text-shadow: 5px 2px #222324, 2px 4px #222324, 3px 5px #222324;
}
      
    </style>
    
   </head>
  <body>
    <div class="word"></div>
  </body>
  <script>
   var words = ['Hi i like HTML', 'I also like css', 'Lorem ipsum dolor sit amet', ' consectetur adipiscing elit', 'sed do eiusmod tempor incididunt'],
    part,
    i = 0,
    offset = 0,
    len = words.length,
    forwards = true,
    skip_count = 0,
    skip_delay = 15,
    speed = 70;
var wordflick = function () {
  setInterval(function () {
    if (forwards) {
      if (offset >= words[i].length) {
        ++skip_count;
        if (skip_count == skip_delay) {
          forwards = false;
          skip_count = 0;
        }
      }
    }
    else {
      if (offset == 0) {
        forwards = true;
        i++;
        offset = 0;
        if (i >= len) {
          i = 0;
        }
      }
    }
    part = words[i].substr(0, offset);
    if (skip_count == 0) {
      if (forwards) {
        offset++;
      }
      else {
        offset--;
      }
    }
    $('.word').text(part);
  },speed);
};

$(document).ready(function () {
  wordflick();
});
  </script>
</html>



- 🔭 I’m currently working on web application with machine learning analysis
- 🌱 I’m currently learning Deep Neural Networks
- 👯 I’m looking to collaborate on Machine Learning Projects
- 🤔 I’m looking for help with Time Series struggles
- 💬 Ask me about GARCH Model
- 😄 Pronouns: He/His
- ⚡ Fun fact: I do Blog Posts

<p align="center">
  <a href= https://www.linkedin.com/in/manuel-hupperich-36448b13a/>
  <img src = https://user-images.githubusercontent.com/67901472/147413769-fe54afb6-30c6-489c-8d08-8b0ea0ec44bb.jpg width=40 height=40>
  </a>
  <a>
  <img src = https://user-images.githubusercontent.com/67901472/147413766-27402f32-f918-412c-8701-23d8aa143135.jpg width=40 height=40>
  </a>
  <a href = https://twitter.com/HupperichManuel>
  <img src = https://user-images.githubusercontent.com/67901472/147413745-c57ca67a-e58c-4d04-be2f-8d0e403fd451.jpg width=40 height=40>
  </a>
</p>

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![Windows](https://svgshare.com/i/ZhY.svg)](https://svgshare.com/i/ZhY.svg)


<img src = 'https://github-readme-stats.vercel.app/api?username=Hupperich-Manuel&&show_icons=true&title_color=ffffff&icon_color=bb2acf&text_color=daf7dc&bg_color=181919'>

