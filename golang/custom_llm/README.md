# 🌟 Custom LLM Sample Code for Golang

> The Agora Conversational AI Engine supports custom large language model (LLM) functionality. You can refer to this project code to implement custom large language model functionality.

This document provides Golang sample code for implementing custom large language model functionality.

## 🚀 Quick Start

### Environment Preparation

- Golang 1.21+

### Install Dependencies

```bash
go mod tidy
```

### Run Sample Code

```bash
go run custom_llm.go
```

## 📖 Function Description

### Basic Custom Large Language Model

> To successfully integrate with the Agora Conversational AI Engine, your custom large model service must provide an interface compatible with the OpenAI Chat Completions API.

Refer to the `handleChatCompletion` function for implementation logic.

### Implementing Retrieval-Augmented Custom Large Language Model

> If you want to improve the accuracy and relevance of the agent's responses, you can use the Retrieval-Augmented Generation (RAG) feature. This allows your custom large model to retrieve information from a specific knowledge base and provide the retrieval results as context for the large model to generate answers.

Refer to the `handleRAGChatCompletion` function for implementation logic.

### Implementing Multimodal Custom Large Language Model

Preparation:
 - Place a `file.pcm` file in the current directory with a sample rate of 16000, 16-bit, mono, and PCM format.
 - Place a `file.txt` file in the current directory containing the text transcription of the above audio file.

Refer to the `handleAudioChatCompletion` function for implementation logic.

## 📚 Resources

- 📖 Check out our [Conversational AI Engine Documentation](https://doc.agora.io/doc/convoai/restful/landing-page) for more details
- 🧩 Visit [Agora SDK Examples](https://github.com/AgoraIO) for more tutorials and example code
- 👥 Explore high-quality repositories managed by the developer community in the [Agora Developer Community](https://github.com/AgoraIO-Community)
- 💬 If you have any questions, feel free to ask on [Stack Overflow](https://stackoverflow.com/questions/tagged/agora.io)

## 💡 Feedback

- 🤖 If you have any problems or suggestions regarding the sample projects, we welcome you to file an issue.

## 📜 License

This project is licensed under the MIT License.