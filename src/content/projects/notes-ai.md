---
title: "NotesAI"
tagline: "AI-powered storage, search, and chat over your personal notes and documents"
coverImage: "/images/projects/notes-ai_2.png"
coverAlt: "NotesAI project cover — personal knowledge and notes"
status: "active"
stage: "product-design"
stageLabel: "Product Design"
summary: "Store notes, index knowledge with vector search, and ask questions in natural language using RAG over your own documents."
startedAt: "2026-05-01"
neededRoles:
  - "Product Lead"
  - "Coordinator"
  - "ML Engineer"
  - "Backend Developer"
  - "Frontend Developer"
  - "QA Engineer"
links:
  github: "https://github.com/WildPointerOrg/notesai"
  docs: ""
  discussions: "https://github.com/orgs/WildPointerOrg/discussions/1"
  roadmap: "https://github.com/orgs/WildPointerOrg/projects/3"
contacts:
  coordinator: "tg: @chechestor"
  telegram: ""
  email: ""
materials:
  - stage: "idea-forming"
    title: "NotesAI — Idea Document"
    summary: "Formatted idea overview — problem, users, solution, competitors, and risks"
    url: "https://docs.google.com/document/d/1cckBan-CQ0EU9Gql997ZVmQO6C88TGhiQAhf4bAj72Q/edit?usp=sharing"
    order: 1
  - stage: "discovery"
    title: "NotesAI — Discovery"
    summary: "Discovery research outcomes — problem validation, use cases, and product scope"
    url: "https://docs.google.com/document/d/1vlyFimw6enDUkA3NuzuXJdf9GGQ_IA5KJhcRSSrp_x4/edit?usp=drive_link"
    order: 1
featured: true
order: 1
---

## Project Goal

People accumulate large amounts of notes, documents, and personal knowledge, but existing note-taking tools make retrieval difficult. Users forget where information was stored and spend significant time searching manually.

NotesAI addresses this by combining document storage, vector search, and LLM-based interaction in one product. Users upload notes (text, links, or voice) via bot, GUI, mobile, or app; the system indexes content into a vector database; users ask questions in natural language and receive answers grounded in their own knowledge base.

**Idea discussion:** [WildPointerOrg discussion #1](https://github.com/orgs/WildPointerOrg/discussions/1#discussioncomment-16917051)

## Expected Value

**For users**

- Find information from a personal knowledge base using natural language instead of manual search.
- Reduce time spent hunting through notes and improve day-to-day productivity.
- Search previous conversations and notes in one place.

**For the community**

- Hands-on experience building a real RAG pipeline: embeddings, retrieval, and LLM integration.
- Open-source product aimed at developers, researchers, students, and technical specialists who work with large volumes of information.

**Target audience:** developers, researchers, students, and technical specialists working across devices during study, research, development, meetings, and daily work.

## Current Focus

The squad is in **Product Design**: turning Discovery outcomes into user flows, UX/UI, and an MVP prototype.

Discovery research is complete — see [NotesAI — Discovery](https://docs.google.com/document/d/1vlyFimw6enDUkA3NuzuXJdf9GGQ_IA5KJhcRSSrp_x4/edit?usp=drive_link). Work is tracked on the [GitHub project board](https://github.com/orgs/WildPointerOrg/projects/3); code lives in the [notesai repository](https://github.com/WildPointerOrg/notesai).

**Main user flow**

1. User sends notes (text / link / voice) to the app.
2. System indexes notes into a vector database.
3. User asks questions in natural language.
4. System retrieves relevant chunks and generates contextual answers.
5. User searches prior conversations and notes.

**Design focus**

- Primary user journeys and MVP surface (bot vs web vs mobile).
- Wireframes and UX/UI prototype for note capture, search, and AI chat.
- Information architecture for notes, conversations, and retrieval feedback.

## Open Questions

**Risks**

- High API and inference costs at scale.
- Poor retrieval quality (RAG misses relevant context).
- Low contributor activity on a long-running open project.
- Privacy and trust for highly personal document stores.

**Product**

- Final choice of vector DB, embedding models, and hosting model.
- MVP surface: bot vs web vs mobile first.
- Pricing / limits for LLM calls in a volunteer-built product.

**Later**

- Team collaboration and shared knowledge spaces (post-MVP).
