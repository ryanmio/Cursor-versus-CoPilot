## Introduction

This document provides a comparison between two AI pair programming tools: Cursor and GitHub Copilot.

## Category Comparison

| Category | Winner | Notes |
|----------|--------|-------|
| Chat | Cursor | Cursor's chat sidebar has a number of unique features: GPT model selection, more commands, create documentation from urls, deep linking to files and functions. |
| Code Generation | Copilot | GitHub Copilot is faster and generally more accurate in real-time code generation and suggestions. |
| Codebase RAG | Tie | Both are very good at understanding your codebase using RAG. Co-pilot supports '@workspace' while Cursor supports "chat with codebase". Cursor's RAG algorithms seem to be better at finding and including relevant code/files in the context and you can add specific files/folders to the scope manually. Copilot seems to rely on filenames while cursor will find the context in a file even with a misleading name. |
| Context Length | Cursor | Cursor supports longer messages and allows including additional files, folders, etc., in the context using @. |
| Cost | Copilot | Cursor's monthly cost is $20, while GitHub Copilot is $10 for individuals. Cursor offers a full-featured free option with limited usage, and GitHub Copilot has a full-featured limited-time free trial. |
| Customizability | Cursor | Cursor allows more customization options for the AI functionality |
| GitHub Integration | Cursor | Cursor enables referencing specific Git commits and PRs directly in chat. |
| Learning Curve | Copilot | GitHub Copilot, being an extension to VS Code and other IDEs, is easier to adopt and integrate. |
| Multimodality | Cursor | Cursor uses GPT-4V integration for drag-and-drop image support. |
| Reliability | Copilot | GitHub Copilot offers more consistent performance. Cursor has connectivity issues. |
| Security and Privacy | Copilot | GitHub Copilot benefits from the robust security infrastructure of a major multinational corporation, though Cursor offers a local mode. |
| Speed of Operation | Copilot | GitHub Copilot responds faster in coding workflow. The real-time suggestions make for a lightning fast experience and keep you in the flow. |
| User Experience and Interface | Cursor | Cursor, as a standalone VS Code fork, provides a more comprehensive UI experience. |
| Direct Code Editing | Cursor | Cursor's '/Edit' and 'Apply to Current File' features allows for direct application of code edits from the chat window. |
| Terminal | Cursor | Cursor supports AI features in the terminal panel allowing it to generate terminal commands for you or auto-debug terminal errors. |

 :drum: :drum: :drum: And the overall winner is... :drum: :drum: :drum: |
 :---:|
 <p align="center" style="font-size:2em;">Cursor!</p>

## A Non-Traditional Coder's Perspective on AI Pair Programming

First, I want to acknowledge that my perspective as a beginner might differ vastly from that of a seasoned developer. I stumbled into AI-assisted coding out of curiosity. With no background in traditional programming, I made my first commit shortly after the launch of GPT-4. Since then I've developed a few React/NextJS apps, a website, a Slack integration, and helped my hackathon team take home the grand prize.

I started using Cursor in August 2023 and GitHub Copilot in November 2023. Each tool has its strengths, but Cursor, in particular, has become indispensable in my coding workflow. GitHub Copilot is evolving and shows promise, but in my experience, it hasn't quite reached the utility level of Cursor yet.

More generally, the evolution and similarities between Cursor and Co-Pilot hint at a profound change coming, not just for programmers but all computer-interfacing creative roles.

In the immediate future I think it’s pretty likely that AI systems will have more direct control over the IDE. Cursor’s most popular and effective features come from its deep integration and control within the IDE, a path GitHub Copilot seems to be emulating.

Then the AI's role in pair programming is going to quickly transition beyond suggesting code and chatting in the sidebar. It will evolve into a much more active participant, with the programmer’s role becoming more supervisory.

With the current state-of-the-art foundational models, there’s ample scope for enhancing these tools to become much more effective pair programming agents. Any next-generation language models will only accelerate this transition.

The programmer of the future might be more like an architect than a craftsman. Their focus will be high-level design, problem-solving, and ensuring that AI tools are aligned with project objectives and creative vision. Programming will be more about guiding and less about crafting every line of code.


*Note: This document was written using Cursor with assistance from GPT-4.*


