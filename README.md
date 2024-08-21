# 🌐 CyberScraper 2077

<p align="center">
  <img src="https://i.postimg.cc/j5b7QSzg/scraper.png" alt="CyberScraper 2077 Logo">
</p>

<p align="center">
  <img src="https://i.postimg.cc/9MKqtn2g/68747470733a2f2f692e706f7374696d672e63632f74346d64347a74762f6379626572736372617065722d323037372e6a70.jpg">
</p>

[![Python](https://img.shields.io/badge/Python-blue)](https://www.python.org/downloads/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B)](https://streamlit.io/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

> Rip data from the net, leaving no trace. Welcome to the future of web scraping.

## 🔍 About

CyberScraper 2077 is not just another web scraping tool – it's a glimpse into the future of data extraction. Born from the neon-lit streets of a cyberpunk world, this AI-powered scraper uses OpenAI to slice through the web's defenses, extracting the data you need with unparalleled precision and style.

Whether you're a corpo data analyst, a street-smart netrunner, or just someone looking to pull information from the digital realm, CyberScraper 2077 has got you covered.

<p align="center">
  <img src="https://i.postimg.cc/3NHb15wq/20240821-074556.gif">
</p>

## ✨ Features

- 🤖 **AI-Powered Extraction**: Utilizes cutting-edge AI models to understand and parse web content intelligently.
- 💻 **Sleek Streamlit Interface**: User-friendly GUI that even a chrome-armed street samurai could navigate.
- 🔄 **Multi-Format Support**: Export your data in JSON, CSV, HTML, SQL or Excel – whatever fits your cyberdeck.
- 🌐 **Stealth Mode**: Implemented stealth mode parameters that helps it from getting detected as bot.
- 🤖 **Ollama Support**: Use a huge libarary of open source LLMs.
- 🚀 **Async Operations**: Lightning-fast scraping that would make a Trauma Team jealous.
- 🧠 **Smart Parsing**: Structures scraped content as if it was extracted straight from the engram of a master netrunner.
- 🛡️ **Ethical Scraping**: Respects robots.txt and site policies. We may be in 2077, but we still have standards.
- 🌐 **Proxy Mode (Coming Soon)**: Built-in proxy support to keep you ghosting through the net.
- 🛡️ **Navigate through the Pages (Coming Soon)**: Navigate through the webpage and scrap the data from different pages. 

## 🎥 Demo

Check out our [YouTube video](https://www.youtube.com/watch?v=iATSd5Ijl4M) for a full walkthrough of CyberScraper 2077's capabilities.

## 🪟 For Windows Users (hotfix)

You may encounter issues while using the Windows version as I ported it in a few minutes.

**Steps to follow:**
  
1. First type: ```git checkout windows-hotfix```
2. Then Follow the same steps as below.

## 🛠 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/itsOwen/CyberScraper-2077.git
   cd CyberScraper-2077
   ```

2. Create and activate a virtual environment:
   ```bash
   virtualenv even
   source venv/bin/activate  # Optional
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Install the playwright:
   ```bash
   playwright install
   ```

5. Set OpenAI Key in your enviornment:

   Linux/Mac:
   ```bash
   export OPENAI_API_KEY='your-api-key-here'
   ```
   For Windows:
   ```bash
   set OPENAI_API_KEY=your-api-key-here
   ```
6. If you want to use the Ollama:

Note: I only recommend using OpenAI API as GPT4o-mini is really good at following instructions, If you are using open-source LLMs make sure you have a good system as the speed of the data generation/presentation depends on how good your system is in running the LLM and also you may have to fine-tune the prompt and add some additional filters yourself.
   ```bash
   1. Setup Ollama using `pip install ollama`
   2. Download the Ollama from the official website: https://ollama.com/download
   3. Now type: ollama pull llama3.1 or whatever LLM you want to use.
   4. Now follow the rest of the steps below.
   ```

## 🚀 Usage

1. Fire up the Streamlit app:
   ```bash
   streamlit run main.py
   ```

2. Open your browser and navigate to `http://localhost:8501`.

3. Enter the URL of the site you want to scrape or ask a question about the data you need.

4. Ask the chatbot to extract the data in any format, Select whatever data you want to export or even everything from the webpage.

4. Watch as CyberScraper 2077 tears through the net, extracting your data faster than you can say "flatline"!

## Adjusting PlaywrightScraper Settings (optional)

Customize the `PlaywrightScraper` settings to fit your scraping needs:

- **Browser Launch Options**: Modify `headless` mode and `args` in `launch_browser` to control browser visibility and behavior.
- **Browser Context**: Adjust viewport size and `user_agent` in `create_context` to suit your scraping requirements.
- **Page Features**: Update HTTP headers and `navigator.webdriver` in `set_browser_features` for better mimicry of real users.
- **Cloudflare Bypass**: Configure retry attempts and delays in `bypass_cloudflare` to handle Cloudflare protections.
- **Human Behavior Simulation**: Customize scrolling and mouse movements in `simulate_human_behavior` to simulate realistic user interactions.

So you can disable or remove the Human Behaviour simulation option as it currently mimics human behaviour, stuff like scrolling and more to prevent it from getting blocked. So it does take a few extra seconds when you send the link at the start which slows the process a little bit.

Adjust these settings based on your target website and environment for optimal results.

## 🤝 Contributing

We welcome all cyberpunks, netrunners, and code samurais to contribute to CyberScraper 2077!

## 🔧 Troubleshooting

Ran into a glitch in the matrix? Let me know by adding the issue to this repo so that we can fix it together.

## ❓ FAQ

**Q: Is CyberScraper 2077 legal to use?**
A: CyberScraper 2077 is designed for ethical web scraping. Always ensure you have the right to scrape a website and respect their robots.txt file.

**Q: Can I use this for commercial purposes?**
A: Yes, under the terms of the MIT License. But remember, in Night City, there's always a price to pay, Just kidding!

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. Use it, mod it, sell it – just don't blame us if you end up flatlined.

## 📞 Contact

Got questions? Need support? Want to hire me for a gig?

- 📧 Email: owensingh72@gmail.com
- 🐦 Twitter: [@_owensingh](https://x.com/_owensingh)
- 💬 Website: [Portfolio](https://www.owensingh.com)

## 🚨 Disclaimer

Listen up, choombas! Before you jack into this code, you better understand the risks. Here's the lowdown in plain language:

1. This software is provided "as is", without warranty of any kind, express or implied.

2. The authors are not liable for any damages or losses resulting from the use of this software.

3. This tool is intended for educational and research purposes only. Any illegal use is strictly prohibited.

4. We do not guarantee the accuracy, completeness, or reliability of any data obtained through this tool.

5. By using this software, you acknowledge that you are doing so at your own risk.

6. You are responsible for complying with all applicable laws and regulations in your use of this software.

7. We reserve the right to modify or discontinue the software at any time without notice.

Remember, samurai: In the dark future of the NET, knowledge is power, but it's also a double-edged sword. Use this tool wisely, and may your connection always be strong and your firewalls impenetrable. Stay frosty out there in the digital frontier.

---

<p align="center">
  <strong>CyberScraper 2077 – Because in 2077, what makes someone a criminal? Getting caught.</strong>
</p>

<p align="center">
  Built with ❤️ and chrome by the streets of Night City | © 2077 Owen Singh
</p>
