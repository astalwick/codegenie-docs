---
title: "Install CodeGenie"
date: 2023-05-31T21:29:03-04:00
draft: false
weight: 10
summary: CodeGenie is available in the [VSCode Extension Marketplace](https://marketplace.visualstudio.com/items?itemName=astalwick.codegenie), or in VSCode's extension panel itself. Once installed, just paste in your OpenAI API key and you're good to go.
---

## 1. Install CodeGenie

Installing CodeGenie is simple. Visit the [VSCode Extension Marketplace](https://marketplace.visualstudio.com/items?itemName=astalwick.codegenie) and click the 'install' button, or else search for 'CodeGenie' in VSCode's extension panel.

{{< centerimage src="/images/docs/extension-marketplace.png" alt="Description of your image" >}}


## 2. Get an OpenAI API token

CodeGenie requires a valid OpenAI API token. If you haven't already got an OpenAI platform account, you'll want to create one here: [OpenAI Platform](https://platform.openai.com).

Once you've created your account, you need to also create an API token for CodeGenie to use. Navigate to the [View API Keys](https://platform.openai.com/account/api-keys) page, and then create yourself a new API key. Copy that to the clipboard and hop over to VSCode.

With your new API key in hand, hit Ctrl/Cmd-Shift-P to bring up the Command Palette. From there, search for 'CodeGenie: Set OpenAI API Key' and select that. CodeGenie will prompt you to input your API key, and will validate that it is active.

Once your API key has been confirmed, you're all set: CodeGenie is ready to help accelerate your development.

 **IMPORTANT: Your API key never leaves your computer (except to communicate with OpenAI), it is stored directly in VSCode's secure [secret storage](https://code.visualstudio.com/api/references/vscode-api#SecretStorage)**. You can see more about our commitment to privacy in the [Security & Privacy](https://codegenie.nsono.net/docs/security-privacy) page.
