# Zync AI

![Zync AI Workspace](frontend/public/screenshot.png)

**Zync AI** is a premium, zero-scroll, multi-model AI workspace designed for speed, fluidity, and zero financial overhead. Built with a dynamic fallback routing system, it leverages the free tiers of top-tier AI models to provide uninterrupted text and image generation without incurring API costs.

## Core Features

*   **Multi-Model Fallback Engine:** Intelligently routes text queries through Groq (Llama 3), Google Gemini, and Cohere. If one API rate-limits, Zync seamlessly falls back to the next.
*   **Zero-Cost Image Studio:** Integrated with Hugging Face's **FLUX.1-schnell** via Base64 buffer conversion for instantaneous, high-quality, and free image generation.
*   **Zero-Scroll Interface:** A highly optimized, Gemini-style UI built with Framer Motion, ensuring all tools are accessible within a single, fixed viewport.
*   **Specialized AI Studios:**
    *   **Smart Chat:** General purpose multi-model AI assistant.
    *   **Caption Studio:** Platform-specific (Instagram, LinkedIn, X, TikTok) viral caption generator with tone selectors.
    *   **Article Pro:** Long-form, SEO-optimized content writer with internal/external linking and markdown formatting.
*   **Persistent Memory:** MongoDB integration automatically titles and saves all text conversations and generated images for future retrieval.

## Technology Stack

*   **Frontend:** React (Vite), Tailwind CSS, Framer Motion, Lucide Icons, React Markdown.
*   **Backend:** Node.js, Express.js, Mongoose.
*   **Database:** MongoDB Atlas.
*   **AI Providers:** Google Generative AI, Groq, Cohere, Hugging Face (Inference API).

## Local Setup & Installation

### 1. Clone the Repository
```bash
git clone [https://github.com/rafay-kh-dev/Zync-AI.git](https://github.com/rafay-kh-dev/Zync-AI.git)
cd Zync-AI
