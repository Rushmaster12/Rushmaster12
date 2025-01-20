![My card name](https://cardivo.vercel.app/api?name=RUSH-MASTER%20&description=Hi,%20Welcome%20To%20My%20Profile&image=https://avatars.githubusercontent.com/u/160727728?s=400&u=30b71fc499af61141695baec7d4171bd87dd2f69&v=4&backgroundColor=%23e4f2f6&instagram=hrutik_official_12&github=Rushmaster12&)
</p>

<div align="center"> 
  
  <a href="https://wa.me/917020728211" target="_blank">
    <img src="https://img.shields.io/badge/whatsapp-008000?style=for-the-badge&logo=whatsapp&logoColor=white" target="_blank" />
  </a>
  <a href="https://instagram.com/hrutik_official_12" target="_blank">
     <img src="https://img.shields.io/badge/instagram-E1306C?style=for-the-badge&logo=instagram&logoColor=white" target="_blank" /> <!-- sqlite, safari, google-chrome are other good icon options -->
  </a>
</div>

  




![Typing SVG](https://readme-typing-svg.demolab.com?font=Ribeye&size=50&pause=1000&color=3F00FF&center=true&width=900&height=100&lines=𝗜𝗧𝗦%20𝞒𝙐𝙎𝞖-𝞛𝞓𝙎𝙏𝞢𝞒-𝗕𝗢𝗧;%20𝗠𝗨𝗟𝗧𝗜-𝗗𝗘𝗩𝗜𝗖𝗘%20𝗪𝗛𝗔𝗧𝗦𝗔𝗣𝗣%20𝗕𝗢𝗧;%20𝗗𝗘𝗩𝗘𝗟𝗢𝗣𝗘𝗗%20𝗕𝗬%20𝗥𝐔𝐒𝐇%20𝐌𝐀𝐒𝐓𝐄𝐑)
<p align="center">


<a href="https://wa.me//+917020728211?text=__𝑯𝑬𝒀★𝚪𝐔𝐒𝚮-𝚳𝚫𝐒𝚻𝚵𝚪_☯️_𝗪𝗛𝗔𝗧'𝗦_𝗨𝗣_𝗕𝗥𝗢🥰_𝐇𝐄𝐋𝐏_𝐌𝐄_𝐏𝐋𝐄𝐀𝐒𝐄_𝐒𝐈𝐑🙏🏻" target="_blank">
    <img alt="whatsapp" src="https://img.shields.io/badge/ Whatsapp -25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
</a>

[![ROMEK-XD-BOT](https://telegra.ph/file/81726c676f1cf11c917c1.jpg)]





const container = document.getElementById("animation-container");

// Generate random bubbles
function createBubble() {
  const bubble = document.createElement("div");
  bubble.classList.add("bubble");
  
  // Random size
  const size = Math.random() * 50 + 20; // 20px to 70px
  bubble.style.width = `${size}px`;
  bubble.style.height = `${size}px`;
  
  // Random position
  bubble.style.left = `${Math.random() * 100}vw`;
  bubble.style.bottom = `-10%`;
  
  // Random color
  bubble.style.background = `rgba(${Math.random() * 255}, ${Math.random() * 255}, ${Math.random() * 255}, 0.5)`;
  
  // Random animation duration
  const duration = Math.random() * 5 + 5; // 5s to 10s
  bubble.style.animationDuration = `${duration}s`;
  
  container.appendChild(bubble);
  
  // Remove bubble after animation ends
  setTimeout(() => {
    bubble.remove();
  }, duration * 1000);
}

// Create bubbles at regular intervals
setInterval(createBubble, 500);
