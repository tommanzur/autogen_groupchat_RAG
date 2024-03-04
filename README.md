# Group Chat with Retrieval Augmented Generation (RAG)

## Overview

This project demonstrates a group chat system powered by Retrieval Augmented Generation (RAG), utilizing the `autogen` library. It showcases how conversational agents, powered by large language models, tools, or human inputs, can perform tasks collectively through automated chat. The framework facilitates tool use and human participation in multi-agent conversations, offering a dynamic and flexible approach to interactive tasks.

## Features

- Multi-agent conversation system with support for automated agents and human input.
- Integration of retrieval-augmented generation for enriched conversation responses.
- Flexible agent configuration, including support for custom termination conditions and auto-replies.
- Extensible architecture for adding new agents or modifying existing ones.

## Installation

Before you can run this project, you need to install some dependencies. You can install the required packages via pip:

```bash
pip install pyautogen
```
## Configuration

Set up your API endpoint by using the config_list_from_json function. This function loads a list of configurations from an environment variable or a json file.
Configure your agents and their interactions within the group chat system. Refer to the notebook for detailed examples on setting up agents like "Boss" and "Boss_Assistant".

## Usage

To start using this group chat system, follow the instructions laid out in the notebook:

- Configure the agents and their roles within the conversation.
- Initialize the group chat and define the conversation logic.
- Start the chat and interact with the system through the predefined agents.
