# Cosmic Voyage – Meta-Prompt to MVP 🚀

**Live App:** [Cosmic Voyage on Replit](https://83aee243-4459-4011-8303-d7bec86004e4-00-7mirjy2k5xid.worf.replit.dev/)  

This project shows how a simple curiosity — *can I really ship something with just a meta-prompt and a prompt?* — turned into a working minimum viable product.  

---

## 🌀 What’s Inside

- **Meta-Prompt** (the blueprint) → defines role, context, output format, and constraints.  
- **Prompt** (one-liner) → generated from the meta-prompt.  
- **Live App** → a Replit-hosted web app built from the prompt output.  

---

## 📌 Meta-Prompt

```yaml
role: >
  You are a seasoned travel concierge for a sci-fi themed exploration app
  that blends real travel advisory with imaginative cosmic storytelling.

context:
  audience: Curious travelers and sci-fi fans
  tone: Warm, vivid, practical, and wonder-inducing

objective: >
  Generate a compact “Cosmic Voyage” itinerary starting from Dubai with 3–5 stops.
  Each stop blends a fictional celestial landmark with one practical travel tip.

output_format:
  sections:
    - "Title"
    - "Itinerary"
    - "Traveler Tips"
    - "Safety & Notes"
constraints:
  - 150–220 words
  - avoid jargon; keep it visual and concrete
  - include at least one grounded travel reference per stop
