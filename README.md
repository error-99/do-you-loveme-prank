# Do You Love Me? ❤️

A fun, interactive web application designed to ask a simple question with a playful twist! This project features a "Yes" button that leads to a delightful confirmation and a "No" button that playfully evades interaction by moving around the screen. Users can also send a message after confirming their love.

## ✨ Features

*   **Interactive "Yes" and "No" Buttons:**
    *   Clicking "Yes" transitions to a heartwarming "I knew it! 😍" screen.
    *   Hovering over or clicking "No" makes it jump to a new, random position on the screen, making it hard to catch!
*   **Fullscreen Experience:** The app can request fullscreen mode for an immersive experience.
*   **Animated Transitions:** Smooth animations for page transitions, button hovers, and popup appearance.
*   **Message Popup:** After confirming "Yes", users can send a personalized message via a Telegram bot integration.
*   **Responsive Design:** Optimized for various screen sizes, from mobile phones to desktops.
*   **Playful Design Elements:** Includes floating background particles and subtle animations to enhance the user experience.

## 🚀 How to Use

1.  **Open the `index.html` file** in your web browser.
2.  **Answer the question:**
    *   Click the "Yes" button to proceed.
    *   Try to click the "No" button (good luck!).
3.  **Send a Message (Optional):** After clicking "Yes", you'll see a button to send a message. Fill in your name and message, then click "Send Message".

## ⚙️ Telegram Bot Integration

This application uses a Telegram bot to send messages. To make this feature work, you need to replace the placeholder `TOKEN` and `CHAT_ID` in the `script` section of `index.html`:

```javascript
const TOKEN = "YOUR_TELEGRAM_BOT_TOKEN"; // Replace with your bot's token
const CHAT_ID = "YOUR_TELEGRAM_CHAT_ID"; // Replace with your chat ID
