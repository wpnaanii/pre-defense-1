# Supervisor Feedback

Project: Development of an AI-powered chatbot for customer support

Supervisor: PhD Aigerim Bakiyeva

Team: Balnur, Karina, Karakat

## 1. General Assessment

The supervisor positively evaluated the project's relevance, practical value, technical complexity, and organization.

The project addresses the need for a configurable AI-powered customer support platform for small and medium-sized businesses.

The supervisor highlighted the clear distribution of responsibilities, the proposed architecture, the focus on data isolation, and the planned evaluation metrics.

## 2. Project Strengths

- Relevant and practical project topic.
- Clear responsibilities among team members.
- Appropriate proposed technologies, including Python, FastAPI, PostgreSQL, and RAG.
- Attention to multi-tenant architecture and data security.
- Comprehensive evaluation criteria covering accuracy, relevance, response time, retrieval quality, and tenant isolation.

## 3. Recommendations for Improvement

Recommendation 1: Improve AI Response Reliability

The supervisor recommended reducing unsupported AI-generated answers by evaluating response faithfulness to retrieved source information.

Suggested actions:
- Evaluate document chunk sizes for knowledge retrieval.
- Define an appropriate similarity threshold.
- Apply fallback handling when retrieved information is insufficient.

Recommendation 2: Improve Frontend Technology Selection

The supervisor suggested considering React, Vue.js, or suitable templating tools to simplify development of the administration dashboard.

Suggested actions:
- Compare frontend implementation options.
- Select a suitable approach based on project complexity and available development time.

Recommendation 3: Strengthen Chatbot Evaluation

The supervisor recommended integrating RAG evaluation metrics into the testing process.

Suggested metrics:
- Faithfulness.
- Answer Relevance.
- Context Precision.

Suggested actions:
- Prepare representative evaluation questions.
- Define expected answers and relevant knowledge sources.
- Evaluate chatbot responses using the selected metrics.

## 4. Planned Team Actions

- Balnur will investigate the technical implementation of AI response reliability, frontend technologies, and testing tools.
- Karakat will refine the evaluation plan and review the proposed RAG quality metrics.
- Karina will add the recommendations to YouTrack and monitor their progress.

## 5. Feedback Implementation Status

| Recommendation | Status |
|---|---|
| Improve response faithfulness and fallback mechanisms | Planned |
| Evaluate frontend framework options | Planned |
| Include RAG evaluation metrics | Planned |
| Update project tasks based on feedback | To be confirmed |

## 6. Conclusion

The supervisor's feedback provides guidance for improving the system architecture, frontend implementation, AI response reliability, and evaluation methodology.

The team will consider these recommendations during the next development stages.
