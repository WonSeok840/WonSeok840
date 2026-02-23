<p align="left">
{ONE_LINE_PITCH}
</p>

### About Me
* {CURRENT_STATUS}  
* Interests: LLM fine tuning, PEFT, LoRA, Computer Vision, Recommendation  
* I enjoy building practical AI features for real world products  
* Contact: {EMAIL}  

---

### Featured Projects
#### 1) {PROJECT_NAME_1}  Smart Fishing Assistant
* Goal: Improve fishing domain understanding and generate reasoned recommendations  
* Key feature: Water color based egi color recommendation with justification  
* Tech: sLLM fine tuning with LoRA, instruction tuning

**Fine tuning details**
* Base model: polyglot ko 1.3b  
* Dataset: 1,000 instruction pairs  
  * Format: water color condition, egi color, expert Q and A  
* Method: LoRA based PEFT  
  * Rank r: 16  
  * LoRA alpha: 32  
  * Dropout: 0.05  
  * Epochs: 512  

**Trouble shooting**
* Initial base model: meta llama Llama 3.2 3B instruct  
  * Issue: multilingual tendency caused mixed language outputs when trained with Korean data  
  * Constraint: 3B size increased memory usage in deployment environment  
* Solution: switched to polyglot ko 1.3b  
  * Result: improved Korean response quality and reduced memory pressure

Link: {PROJECT_LINK_1}

#### 2) {PROJECT_NAME_2}  {SHORT_DESCRIPTION}
* What I did: {YOUR_ROLE_SUMMARY}
* Tech: {TECH_STACK_SUMMARY}
Link: {PROJECT_LINK_2}

---

### Tech Stack
**Languages**
* Python, {OTHER_LANGS}

**LLM and ML**
* PyTorch, Transformers, PEFT, LoRA, {LIBS}

**Computer Vision**
* Ultralytics YOLO, OpenCV, {CV_TOOLS}

**Data and Tools**
* GitHub, Docker, {TOOLS}

---

### GitHub Analytics
<p align="center">
  <a href="https://github.com/{GITHUB_USERNAME}">
    <img height="180em" src="https://github-readme-stats.vercel.app/api?username={GITHUB_USERNAME}&show_icons=true&hide_border=true"/>
  </a>
  <a href="https://github.com/{GITHUB_USERNAME}">
    <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username={GITHUB_USERNAME}&layout=compact&hide_border=true"/>
  </a>
</p>

---

### Links
<p align="left">
  <a href="{LINKEDIN_URL}">LinkedIn</a>  
  <a href="{PORTFOLIO_URL}">Portfolio</a>  
  <a href="mailto:{EMAIL}">Email</a>  
</p>

<!-- Optional: Snake commits -->
<!--
<p align="center">
  <img src="https://github.com/{GITHUB_USERNAME}/{GITHUB_USERNAME}/blob/output/github-contribution-grid-snake.svg" alt="snake"/>
</p>
-->
