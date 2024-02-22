<div align="center">
    <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Logo">
    <h1>Revolutionize Your Workflow with Real-Time Notifications</h1>
    <p align="center">
    Supercharge your productivity with customizable Telegram & SMS notifications.
    <br />
    <a href="https://empress.eco/">Explore the Docs</a>
    ·
    <a href="https://github.com/empress-eco/telegram/issues">Report Bug</a>
    ·
    <a href="https://github.com/empress-eco/telegram/issues">Request Feature</a>
    </p>
</div>

## About The Project

Empress Telegram & SMS Notifications is designed to augment your productivity by integrating custom notifications into your workflow. This tool is perfect for users, employees, customers, suppliers, or students, keeping you informed about crucial updates and dates.

### Key Features
- Custom Telegram Notifications
- Direct messaging from any form view
- Support for multiple Telegram Bot channels
- SMS Notifications
- Date Notifications

## Technical Stack and Setup Instructions

This project uses Python 3+ and the [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot) library. 

### Installation
Follow these steps to set up your development environment:

1. Ensure you have Python version 3+ installed on your device.
2. Clone the repository: `git clone https://github.com/empress-eco/telegram.git`
3. Install python-telegram-bot: `./env/bin/pip install python-telegram-bot --upgrade`
4. Get the app: `bench get-app Empress_telegram_integration https://github.com/yrestom/Empress_telegram.git`
5. Install the app: `bench --site [your.site.name] install-app Empress_telegram_integration`
6. Build the project: `bench build`
7. Restart the bench: `bench restart`
8. Create a new Telegram bot in `BotFather` and obtain the Telegram Bot Token.

### Usage

After installation, navigate to Telegram Settings to enter the Telegram Bot Token. Set up new user settings under Telegram User Settings. You can configure various notifications to remind you of important activities. Send direct Telegram messages from any form view. When a Telegram Notification is sent, a new log entry will be created in Extra Notifications.

## Contribution Guidelines
We welcome and appreciate your contributions! To contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License and Acknowledgements
This project is licensed under the MIT License. Your contributions are also licensed under the same.

We extend our heartfelt thanks to the Empress Community for their foundational contributions to this project. Their innovation and commitment have been instrumental in building the essential tools that power this project, and we are profoundly grateful for their pioneering work and ongoing support. 

Visit us on [GitHub](https://github.com/empress-eco/).

For more information about the project and to explore more features, visit our [Documentation](https://grow.empress.eco/).