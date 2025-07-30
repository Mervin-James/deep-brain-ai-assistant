# DeepBrain AI Assistant &mdash; Extending Your Personal Knowledge

*A production-grade AI with a meta-reasoning agent that uses knowledge from your sources (such as Notion, Google Drive) to provide insights, summarize documents, and answer questions*

### About This Enhanced Implementation

This project builds upon Decoding ML's open-source Second Brain AI Assistant course, adding **dynamic reasoning capabilities** that adapt processing complexity based on input characteristics. The system automatically scales from simple retrieval for straightforward queries to multi-step reasoning for complex analytical tasks.

### Skills Mastered

* LLM system architecture (FTI) and MLOps best practices
* Pipeline orchestration and tracking with ZenML
* LLMOps and RAG evaluation using Opik
* Large-scale web crawling and content normalization
* Quality scoring with LLMs and heuristics
* Dataset generation through distillation
* Llama model fine-tuning with Unsloth, Pytorch, and Comet
* Serverless model deployment to Hugging Face
* Advanced RAG with contextual or parent retrieval and vector search
* Agent building using smolagents, LangChain
* Modern Python tooling (uv)

### Key Enhancement: Meta-Reasoning Agent

The core innovation introduces a **meta-reasoning agent** that examines user input and dynamically adjusts the reasoning steps threshold required for optimal response generation:

- **Simple Queries**: Low threshold - direct contextual retrieval with basic summarization
- **Moderate Complexity**: Medium threshold - enhanced contextual search with analysis  
- **Complex Queries**: High threshold - multi-step reasoning with iterative refinement

This meta-reasoning layer acts as an intelligent controller, determining how many reasoning steps the system should take based on input complexity analysis.

### What's Built

**Adaptive Intelligence**: 
- Meta-reasoning agent for dynamic threshold adjustment
- Query complexity analysis and reasoning strategy selection
- Intelligent escalation of reasoning depth based on input requirements

**Production-Ready System**:
- End-to-end agentic RAG powered by your personal knowledge base
- Advanced RAG with contextual retrieval and hybrid search
- Fine-tuned LLMs with serverless deployment
