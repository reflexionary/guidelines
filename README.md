# Reflexionary: Your AI Financial Co-Pilot

Let AI Speak to Your Money

Reflexionary is your super-smart AI financial co-pilot, designed to turn your money worries into crystal-clear financial clarity. Our main motto: reducing your financial anxiety.

## The Core Idea: Augmenting Financial Cognition

Reflexionary transcends generic financial advice by establishing a dynamic, intelligent layer that fundamentally augments individual financial cognition. We provide a personal financial assistant built to understand you better than your own wallet, making managing your money and portfolio genuinely engaging.

At its heart, Reflexionary is powered by Google Gemini, enabling human-like conversation and advanced reasoning. This sophisticated integration allows for:

### Rock-Solid Memory Management Layer
Think of it as a super-powered financial diary. This layer, utilizing sentence-transformers for semantic embeddings, Annoy for lightning-fast vector indexing, and Firebase Firestore for secure, persistent storage, remembers every dream, preference, and penny's journey. It provides Google Gemini with a rich, user-specific context, overcoming the inherent statelessness of LLMs.

### Fi-MCP Data Stream Integration (Simulated)
This acts as a direct, secure line to your financial world. For the hackathon, we simulate this stream with comprehensive mock data, representing a consolidated view of your income, investments, liabilities, and market trends. This structured data is crucial for grounding our AI's insights in real-world financial context.

### Mathematical Intelligence Layer
This is where the numbers come alive. Fueled by PyPortfolioOpt for advanced optimization, Pandas for robust data manipulation, and NumPy for high-performance numerical computation, this layer crunches complex financial figures to give you advice that's not just smart, but quant-level precise.

Reflexionary is built with privacy-by-design at its heart. Your sensitive financial data stays your data, securely tucked away in your personal AI memory vault. It's about giving you unparalleled clarity, control, and confidence, turning financial stress into financial zen.

## Unique Selling Proposition (USP)

Reflexionary: Your Financial Intuition, Amplified.

We fuse Google Gemini's advanced cognition with a user-sovereign, dynamically-indexed financial memory and algorithmic quant strategies. This empowers you with proactive, optimized, and privacy-assured financial actions, tailored to your unique context. We don't just advise; we cognitively augment your financial self.

## Key Features

### Goal-Based Planning: Your Personal Dream Weaver
- Functionality: Users express financial aspirations (e.g., "retire by 50," "afford a house"). Reflexionary's Google Gemini parses intent and extracts key parameters. It then runs detailed future simulations, projecting net worth, savings, and affordability based on current data and user-defined variables.
- Impact: Combats temporal discounting and the planning fallacy by providing clear, data-driven roadmaps and visual progress tracking, making abstract goals tangible and achievable.

### Anomaly Detection & Smart Alerts: Your Vigilant Guardian
- Functionality: Reflexionary continuously monitors simulated Fi-MCP financial data. It employs lightweight unsupervised ML models to learn individual baseline patterns and proactively identify statistically significant deviations (e.g., unexpected spending spikes, investment underperformance).
- Impact: Acts as an external attentional system, mitigating attentional bias and decision fatigue. Alerts are conversational and psychologically framed by Google Gemini to prompt action without inducing anxiety.

### Memory Management: The Digital Financial Autobiography
- Functionality: This layer implements a robust Retrieval Augmented Generation (RAG) architecture. User goals, preferences, prior queries, and Tacit's responses are captured, converted into vector embeddings, and indexed in Annoy for rapid semantic retrieval. The original content and metadata are securely stored in a user-isolated Firebase Firestore instance.
- Impact: Overcomes LLM statelessness and context limitations, providing Google Gemini with a persistent, evolving, and highly personalized financial context. This combats recency bias and ensures consistent, context-aware advice.

### Mathematical Intelligence: Your Personal Quant Strategist
- Functionality: This layer performs precise, data-backed financial analysis. It leverages PyPortfolioOpt for sophisticated portfolio optimization and Pandas / NumPy for robust data preparation and simulation.
- Impact: Google Gemini's Function Calling dynamically invokes these quant engines, translating complex numerical outputs into clear, actionable financial strategies. This directly addresses math anxiety and counteracts emotional biases with objective, optimized recommendations.

## Technology Stack: A Robust, Google-Powered Foundation

Our architecture is built on a powerful, modern, and open-source stack, designed for performance, scalability, and security:

- AI Core: Google Gemini API (for advanced NLU, generation, and Function Calling).
- Backend & Orchestration: Python (utilizing frameworks like FastAPI/Flask for API endpoints and custom logic for orchestrating data flow and component interactions).
- Memory Layer:
  - Embeddings: sentence-transformers (for efficient text-to-vector conversion).
  - Vector Indexing: Annoy (for high-performance Approximate Nearest Neighbor search).
  - Persistent Storage: Firebase Firestore (for secure, scalable, user-isolated, and real-time document storage of raw memories and metadata).
- Financial Computation: PyPortfolioOpt (for portfolio optimization algorithms), Pandas (for data manipulation and analysis), NumPy (for high-performance numerical operations).
- UI/Frontend: Streamlit (for rapid interactive web application development and prototyping), HTML, CSS (Tailwind CSS for responsive and aesthetic design), JavaScript (for Chart.js integrations).
- Other Key Tools: Scikit-learn (for lightweight ML models in Anomaly Detection), Git (for version control and collaborative development), Docker (for containerization and consistent deployment environments), conceptual integration with Vertex AI for future ML model deployment and management at scale.

## Contributing

This project is currently for internal team development. Please refer to our CONTRIBUTING.md for internal guidelines.

## Team

Reflexionary

Our code's pristine, and so are our terminals.