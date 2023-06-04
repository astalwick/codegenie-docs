---
title: 'Security & Privacy'
date: 2023-05-31T21:39:27-04:00
draft: false
weight: 200
---

Security and Privacy are incredibly important. There are a ton of ChatGPT-related extensions in the VSCode marketplace, and it's definitely worth giving them a look. Be sure, however, to take their security and treatment of your API key into consideration.

## CodeGenie Security/Privacy Pledge

CodeGenie promises:

1. We will respect your API key and store it securely. Other extensions make use VSCode's extension settings to store the API key. This is not a secure place to store secrets because it is not encrypted and third-party extensions can gain access to your key. CodeGenie uses VSCode's [Secret Storage](https://code.visualstudio.com/api/references/vscode-api#SecretStorage) to keep your API key secure.
2. We will never send your API key to any other server or system than OpenAI itself. Your API key is given to CodeGenie _only_ in order to enable CodeGenie to make requests of OpenAI; there is no reason to send it anywhere else.
3. We will not store or send your chat history, requests or responses anywhere. We store chat history on disk; there is no need to persist to a server.

It is possible that we may add features that require the use of a server: for example, synchronizing chat histories from one machine to another. To that end, we also pledge:

4. If ever CodeGenie introduces a feature that requires a server, we will make that feature fully opt-in.

## Security or Privacy Issues?

If you do find a bug or are concerned about a security or privacy related issue, please feel free to reach out:
- [Github](https://github.com/astalwick/codegenie-docs/issues)
- arlen@nsono.net

