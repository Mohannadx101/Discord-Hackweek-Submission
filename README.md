# Discord Hackweek Project  
🚀 A custom Discord bot built for Discord Hackweek, featuring moderation, fun commands, and automation tools to enhance the server experience.  

## 📌 Features  
✅ Custom moderation commands (Kick, Ban, Mute, Warnings)  
✅ Fun & utility commands (Memes, Trivia, Mini-Games)  
✅ Logging system for tracking server activity  
✅ Automated role management and reaction roles  

## 🛠️ Tech Stack  
- **Programming Language:** JavaScript (Node.js)  
- **Library:** Discord.js  
- **Database:** JSON-based storage (`log.json`, `profile.json`)  

## 🚀 Installation & Setup  
### Clone the Repository  
```bash
git clone https://github.com/Mohannadx101/Discord-Hackweek-Submission.git
cd Discord-Hackweek-Submission
```
### Install Dependencies  
```bash
npm install
```
This will install all required packages from `package.json`.  
### Set Up Your Environment Variables  
Create a `.env` file in the root folder and add:  
```ini
DISCORD_TOKEN=your-bot-token
```
### Run the Bot  
```bash
node index.js
```
## 💡 Usage  
- Use `/help` to view all available commands.  
- Set up automatic role assignments with reaction roles.  
- Keep track of moderation actions with logging features (`log.json`).  
## 📜 License  
This project is **Open Source** – feel free to use, modify, and contribute!  
