Version: NAFATH-V3
Track: AI

## Overview
This brief explains how six IT fields work together to build a trustworthy AI assistant for a public service. Software engineering uses versioning to manage changes safely. Artificial intelligence helps the assistant understand questions and find relevant information. Mobile security protects communication between the application and its services. Networking supports reliable connections and communication between devices. Cybersecurity reduces risks such as prompt injection and unauthorized access. Data protection helps keep citizens’ chat information safe through appropriate anonymization or pseudonymization. These fields depend on each other: a secure mobile application needs reliable networking, while an accurate AI assistant needs trusted information and careful data handling. By combining these practices, a government service can provide helpful answers while protecting citizens’ privacy and maintaining public trust.
## Software
Under Semantic Versioning, a MAJOR version change is required when the public API changes in a way that is not backward compatible. A MINOR version change is used when new functionality is added in a backward-compatible way. A PATCH version change is used for backward-compatible bug fixes. For example, removing a public API function requires a MAJOR update, while fixing a bug without changing the API requires a PATCH update.

Resource: Semantic Versioning 2.0.0 - https://semver.org/
## AI
Retrieval-Augmented Generation (RAG) is a method that combines information retrieval with a large language model. When a user asks a question, the system searches trusted information sources and provides relevant passages to the model. The model then uses this evidence to generate an answer. RAG can reduce incorrect answers by grounding responses in retrieved information, but it cannot guarantee that every answer will be correct.

Resource: Retrieval augmented generation (RAG) and indexes - https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/retrieval-augmented-generation
## Mobile
App Transport Security (ATS) is an Apple security feature that protects privacy and data integrity by requiring secure network connections. When an app uses the standard URL Loading System, ATS requires HTTP connections to use HTTPS and checks that connections meet security requirements. If the app tries to connect to a plain HTTP endpoint, ATS normally blocks the connection. The recommended solution is to secure the server and use HTTPS rather than weaken ATS protections.

Resource: Preventing Insecure Network Connections - https://developer.apple.com/documentation/security/preventing-insecure-network-connections
## Networking

## Cybersecurity

## Data

## Misconception in My Track

## Open Question
