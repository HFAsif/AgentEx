# Privacy Policy for AgentEx.Demo

**Last updated:** October 5, 2026

This Privacy Policy explains how **AgentEx.Demo** (`com.hfasif.exagent`) handles information when you use the app.

## Information the app processes

When you send a chat message, the message and the conversation context needed to answer it are transmitted securely to the configured AgentEx backend so Qwen 2.5 Coder can generate a response.

Conversation history may be stored locally on your device so you can reopen previous chats. The current app does not intentionally collect contacts, precise location, photos, microphone recordings, financial information, or advertising identifiers as part of the chat feature.

## Backend and network processing

Public chat traffic uses HTTPS/WSS through a Tailscale Funnel to a private LlamaCrossNet backend. The backend processes chat content to generate replies. It also processes limited technical information needed for security and service operation, such as connection information, rate-limit state, and short-lived session authentication data.

Short-lived public chat session tokens expire automatically. The current AgentEx backend is not designed to persist public chat content as a server-side conversation archive; chat history used by the app is stored on the user's device.

## How information is used

Information is used only to:

- provide AI chat responses;
- maintain conversation history on the user's device;
- protect the public chat service from abuse and excessive requests; and
- diagnose service availability and technical problems.

## Sharing and sale of data

AgentEx.Demo does not sell personal information and does not use chat content for third-party advertising. Information may be processed by infrastructure providers required to deliver the network connection, including Tailscale. Their handling of infrastructure data is governed by their own privacy terms.

## Security

Public chat connections use encrypted HTTPS/WSS transport. Public chat access uses short-lived session authentication. Private backend credentials, model paths, and permanent server secrets are not included in the public app.

## Children

AgentEx.Demo is intended for adults and is not specifically designed for children.

## Your choices

You can stop using the service at any time. Local conversation history can be removed using the app's conversation controls or by clearing/uninstalling the app, subject to the features available in the installed version.

## Changes to this policy

This policy may be updated when AgentEx.Demo features, providers, or data practices change. The latest version will be published at this page.

## Contact

For privacy questions about AgentEx.Demo, contact **hfasif7@gmail.com**.
