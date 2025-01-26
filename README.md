# Senior NodeJS Engineer Test Assignment

---

## Objective

Build a **Knowledge Base System** as a NestJS application. The system should allow users to upload documents, extract insights, and perform intelligent queries using an LLM API. It should also demonstrate the ability to choose between a monolithic or microservices architecture and manage database operations effectively.

### Key Features

1. **Document Management**:
   - Implement an API to upload text or PDF documents.
   - Store document metadata and content in a database.

2. **Insight Extraction**:
   - Use an LLM API (e.g., OpenAI, Hugging Face) to extract summaries or key insights from uploaded documents.
   - Store the extracted insights in the database for future queries.

3. **Query System**:
   - Build an API endpoint to allow users to query the knowledge base.
   - Integrate an LLM API to provide intelligent responses based on document content and insights.

4. **Database**:
   - Use a relational database (e.g., PostgreSQL) or a document-oriented database (e.g., MongoDB) to manage documents and insights.
   - Showcase advanced queries (e.g., full-text search, filtering, ranking based on relevance).

5. **Architecture**:
   - Implement either a monolithic or microservices architecture (your choice). Include a rationale for your choice in the documentation.
   - If using microservices, demonstrate inter-service communication (e.g., via RabbitMQ, Kafka, or gRPC).

6. **Environment Setup**:
   - Use Docker for containerization.
   - Provide a `docker-compose.yml` file to spin up the application, database, and any other necessary services.

7. **Documentation**:
   - Include a `README.md` file with:
     - Installation and setup instructions.
     - Explanation of your architectural choice.
     - API documentation.
     - Assumptions and limitations.

---

## Deliverables

1. **Codebase**:
   - NestJS application with the above features implemented.
   - Database schema and any necessary seed data.

2. **Documentation**:
   - A comprehensive `README.md` file.
   - Inline comments explaining key parts of the code.
  
---
