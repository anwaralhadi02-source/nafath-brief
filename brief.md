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
IPv4 uses 32-bit addresses, while IPv6 uses 128-bit addresses. This gives IPv6 a much larger address space to support the growing number of connected devices. IPv4 address availability is limited, making it harder to assign unique public addresses as internet use grows. IPv6 helps provide many more addresses and supports a scalable internet infrastructure for future devices and services.

Resource: RFC 8200: Internet Protocol, Version 6 (IPv6) Specification - https://www.rfc-editor.org/rfc/rfc8200/
## Cybersecurity
Prompt injection occurs when malicious instructions manipulate an AI assistant. Direct prompt injection comes from a user’s input, while indirect prompt injection is hidden in external content, such as a webpage or file that the AI reads. Two ways to reduce risk are to separate untrusted content from system instructions and restrict the AI’s permissions using the principle of least privilege. These controls reduce risk but cannot guarantee complete prevention.

Resource: LLM01: Prompt Injection - OWASP Gen AI Security Project - https://genai.owasp.org/llmrisk2023-24/llm01-24-prompt-injection/
## Data
Anonymization removes identifying links so people are no longer identifiable from the data, considering the risk of re-identification. Pseudonymization replaces direct identifiers, such as names, with codes while keeping additional information that may reconnect the data to a person. Under UK GDPR, effectively anonymized information falls outside data protection law, while pseudonymized information remains personal data and is still covered by the law. Chat logs should be protected carefully to reduce privacy risks.

Resource: Anonymisation - Information Commissioner’s Office - https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/data-sharing/anonymisation/
## Misconception in My Track

## Open Question
