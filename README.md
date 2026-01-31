# Architecture MCP

An open source tool that summarizes repos contents using LLMs so that you can ask questions about a companies software architecture.

## How it works

Architecture MCP is a two part system with the following componenets

Repo summarizer - This is a CI tool that analyzes a codebase and summarizes its contents in a way that provides high level overview of the applications architecture.

Arrhitecture MCP - This is a hosted MCP server that recieves information from the Repo summarizer as well as has access to Observability tools and cloud apis(AWS)

# What it does

This provides an interface that knows about high level architecture. For example you could ask different models with different variations of "Can you find an issue within my system".

This interface is powerful because it can enable other things to be built that would depend on a systems architecture.
