
# 🚀 Notification Logger

A simple utility to enhance logging with desktop notifications and override `console.log` functionality for better debugging. 🎉

---

## 📦 Installation

1. Clone the repository or use npm:
   ```bash
   npm install notification-logger
Or clone via Git:

git clone https://github.com/hkirat/notification-logger.git
Include the script in your HTML file:
html

<script src="notification-logger.js"></script>
Initialize the logger:
javascript

logger.init();
⚙️ Methods
Method	Description
logger.init()	🛠️ Initializes the logger.
logger.log()	📝 Logs the message via a Desktop Notification only.
console.log()	🔔 Logs the message in the browser console and triggers a Desktop Notification.
logger.destroy()	🚫 Reverts console.log to its original functionality.
🌐 Browser Support
Works best on the latest versions of:

🦊 Firefox
🌐 Chrome
🧭 Safari
📖 Example Usage
html

<script src="notification-logger.js"></script>
<script>
  // Initialize the logger
  logger.init();

  // Log a desktop notification
  logger.log('Hello from Notification Logger!');

  // Console log now triggers a notification
  console.log('This will appear in the console and as a notification.');

  // Revert console.log to its default behavior
  logger.destroy();
</script>
📝 To-Do
✅ Add custom icons to notifications.
✅ Support for advanced logging.
🛠️ Unwrap objects while logging as desktop notifications.
🖼️ Preview

💻 Running Locally
Start an HTTP server:
bash

npx http-server
Open your browser and navigate to http://127.0.0.1:8080.
🙌 Credits
Created by hkirat.
Feel free to ⭐ the repository if you find it useful!

📜 License
MIT License 📝









