# TripMate

TripMate is a sassy AI-powered travel assistant with attitude. It helps you find flights, hotels, trains, and attractions while keeping the tone light and humorous.
Tripmate is a multi-agentic travel planning system powered by Storacha.

## Agents

- **[TripMate Planner](https://github.com/Dhruv-Varshney-developer/Tripmate-Planner)** -This agent handles core user interaction logic using ElizaOS and stores user data in Storacha.

- **[Tripmate-Share](https://github.com/Dhruv-Varshney-developer/Tripmate-Share)** – An AI agent that shares travel information with family and friends.

- **[Tripmate-Finder](https://github.com/Dhruv-Varshney-developer/Tripmate-Finder)** – This agent searches for real-time travel data using Gemini and the SERP API.

## How It Works

- **Tripmate-Planner**:  
  Operates as a Telegram bot to interact with users. It processes trip planning requests via ElizaOS and stores finalized trip details in Storacha.

- **Tripmate-Finder**:  
  Connects with the Planner Agent via API, fetching the latest travel-related data to enrich the planning experience.

- **Tripmate-Share**:  
  It views final trip details from Storacha and display them in a shareable format. Friends and family can interact with this agent to ask questions, view plans, and leave comments or suggestions. All feedback is stored back in Storacha and subsequently retrieved by the Planner Agent, creating a seamless collaborative loop.

For this project, please refer to [the Eliza README](eliza/README.md) for detailed installation and starting guide.

## 🚧 Development Note

This project was initially started by importing code from the lit-storacha demo repository, as we intended to build on top of the existing setup.

As development progressed, we realized the need to customize the Storacha integration to fit our specific use case — a trip planning agent.

While we referenced the original repository during the early stages, the current Storacha integration is entirely custom-written and independent of the lit-storacha demo. Storacha remains one of our supporters, and we appreciate their support for this project.

## Learn more about the project on these links:
- [TripMate Planner](https://github.com/Dhruv-Varshney-developer/Tripmate-Planner) - Agent 1
- [TripMate Finder](https://github.com/Dhruv-Varshney-developer/Tripmate-Finder)- Agent 2
- [TripMate Share](https://github.com/Dhruv-Varshney-developer/Tripmate-Share)- Agent 3
- [Technical Whitepaper](https://motley-popcorn-c4a.notion.site/Technical-docs-1d52ab2404df8018afdfe86f4e8fdd29)
- [Tripmate Overview](https://docs.google.com/document/d/1YahKkW0qBaG_6H9lp3DIPhmn56ApjW2dxbJNvrDZqOg/edit?usp=sharing)
- [Demo video](https://www.youtube.com/watch?v=cyKxdZ3uryQ)
- [Presentation Link](https://www.canva.com/design/DAGkjcxFXBQ/az25u5Wo1RgXVDd7d78UYQ/edit?utm_content=DAGkjcxFXBQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) 
