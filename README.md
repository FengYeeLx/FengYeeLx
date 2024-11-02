<div id="title" align="center" style="padding: 20px; transition: background-color 1s;">

  <h1>Hello, FengYeeLxQwQ! 👋</h1>
  
  ![Visitor Count](https://profile-counter.glitch.me/FengYeeLx/count.svg)

  [![GitHub Stats](https://github-readme-stats.vercel.app/api?username=FengYeeLx&show_icons=true&theme=tokyonight)](https://b23.tv/iEJTnPp)

  <hr style="border: none; height: 2px; background-color: #ccc; margin: 20px 0;">

  <h3>Connect With Me</h3>
  [![Bilibili](https://img.shields.io/badge/Bilibili-FengYeeLx-pink)](https://space.bilibili.com/259185875)

  <hr style="border: none; height: 2px; background-color: #ccc; margin: 20px 0;">

  <h3>Coding with Passion</h3>
  [![Modern C++](https://img.shields.io/badge/Code-Modern%20C++-blue)](https://learn.microsoft.com/zh-cn/cpp/cpp/welcome-back-to-cpp-modern-cpp) 
  [![C](https://img.shields.io/badge/Code-C-lightgrey)](https://en.cppreference.com/w/c) 
  [![Python](https://img.shields.io/badge/Code-Python-yellowgreen)](https://docs.python.org/3/) 
  [![Rust](https://img.shields.io/badge/Code-Rust-orange)](https://doc.rust-lang.org/book/) 
  [![Go](https://img.shields.io/badge/Code-Go-blue)](https://go.dev/doc/) 
  [![Java](https://img.shields.io/badge/Code-Java-red)](https://docs.oracle.com/en/java/)

  <hr style="border: none; height: 2px; background-color: #ccc; margin: 20px 0;">

  <h3>About Me</h3>
  ![](https://img.shields.io/badge/Love-Studying-green) 
  ![](https://img.shields.io/badge/Tips-SurpassYourself-white)

  <div id="time" style="margin-top: 10px; font-size: 1.2em; color: #666;">Current Time: --:--:--</div>

</div>

<script>
// Function to update background color
function changeBackgroundColor() {
  const colors = ["#ffcccc", "#cceeff", "#ccffcc", "#ffebcc", "#e6ccff"];
  document.getElementById("title").style.backgroundColor = colors[Math.floor(Math.random() * colors.length)];
}

// Function to update current time
function updateTime() {
  const now = new Date();
  const formattedTime = now.toLocaleTimeString();
  document.getElementById("time").innerText = `Current Time: ${formattedTime}`;
}

// Update background every 5 seconds and time every second
setInterval(changeBackgroundColor, 5000);
setInterval(updateTime, 1000);

// Initial calls to set time and background
changeBackgroundColor();
updateTime();
</script>