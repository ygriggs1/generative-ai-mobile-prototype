# Generative AI Mobile Prototype

> Mobile-native prototype demonstrating on-device and cloud-hybrid generative AI interaction patterns.

## Overview

This prototype explores human-AI interaction design for mobile contexts — specifically the trade-offs between on-device inference (low latency, privacy-preserving), streaming cloud inference (higher capability), and hybrid approaches. It implements conversational and generative use cases optimized for touch-first interfaces and intermittent connectivity conditions.

## Architecture

- **Inference layer**: Configurable backend supporting local model endpoints and cloud API calls
- **UI layer**: Mobile-optimized interaction components for conversational and generative tasks
- **State management**: Session-scoped context handling for multi-turn agent interactions

## Key Technical Highlights

- Streaming response rendering for perceived low latency on cloud inference
- Graceful degradation to on-device models under poor network conditions
- Privacy-aware data handling — user inputs processed locally by default

## Stack

React Native / mobile framework, Generative AI APIs, local inference support

## Getting Started

```bash
git clone https://github.com/ygriggs1/generative-ai-mobile-prototype.git
cd generative-ai-mobile-prototype

npm install
cp .env.example .env
# Add your API keys to .env
```

## Author

**Yurick "Yg" Griggs** — AI Systems Researcher & Agentic Infrastructure Architect

- [GitHub](https://github.com/ygriggs1)
- [LinkedIn](https://linkedin.com/in/yurick-griggs)
- [Speaker Portfolio](https://sites.google.com/view/yurick-griggs-speaker)
