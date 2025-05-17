# LLM-based-web-agent

## Browser-Use
### Demo
<img src="https://github.com/user-attachments/assets/787d497a-a94b-46fa-a481-76ef87c53949" alt="gif demo" width="50%">

### Function
A self-hosted, open-source AI platform designed to run language models offline. It supports various LLM runners like Ollama and OpenAI-compatible APIs, providing an extensible and feature-rich interface. Users can interact with language models through a user-friendly interface, and the platform is designed to operate entirely offline, ensuring privacy and control.
### Some trial 
- Although I select deepseek as LLM,cmd bash keep tapping:OPENAI-API-KEY failed.Then I searched a tutorial on Youtube and the blogger told me to close "Use-Vision" button on web-ui because it will use chatgpt4 as defalt LLM.
- Firstly I used edge to open web-ui,but it will include some chrome tasks automatically,so I always fail to connect to Chrome.Then I switch to Firefox,then it works.

## Open Operator
### Function
An AI agent that automates web-based tasks by interacting with websites through a browser interface. It can perform actions such as filling out forms, placing online orders, scheduling appointments, and other repetitive browser tasks. Operator operates autonomously, mimicking human actions like clicking, typing, and scrolling. It is available to ChatGPT Pro subscribers in the U.S. at a monthly fee of $200.

## Hugging Face Open Computer Agent
### Demo

👉 [Watch my demo video](https://youtu.be/KW3Evgwh1WY)

### Function
It's like an online virtual machine,it allows you to interact with an AI agent that can perform tasks on the web like searching the web, using apps, and more.
### Some Trial
- The speed is relatively slow compared to web-ui(the demo is 4 times quicker).
- When I use its default browser chrome,it can't pass human-machine detection(demo:https://youtu.be/I0nhggQ6ofk?si=Q2tJerGxH61vQ2nF).And then I input:Use Bing as browser and search "Newton",then I got the demo above.

## OpenManus
### Demo
👉 [Watch my demo video](https://youtu.be/NSEL5TXv-Yw)

### Function
An open-source framework that lets you spin up autonomous AI agents—able to plan, use tools, and execute multi-step tasks—without the closed, wait-listed restrictions of Manus AI.It installs locally (or in Docker), exposes a simple REST/CLI interface, and can pair with any OpenAI-compatible LLM back-end such as GPT-4o or DeepSeek to automate workflows for scraping, coding, or data analysis.

### Some trial 
- Its speed is amazing.I think it ranks first in these 15 models.
- I use cmd to input the prompt,and I'll try use playwright afterwards.
