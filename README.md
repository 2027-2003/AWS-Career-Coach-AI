# AWS-Career-Coach-AI

 Project Overview
An AI-powered career coaching system built on **Amazon Web Services (AWS)**. It leverages **Amazon Q Business** to provide personalized career advice, resume feedback, and skill gap analysis using **RAG (Retrieval-Augmented Generation)**.

 Tech Stack
- **Amazon Q Business**: For the Generative AI assistant logic.
- **Amazon S3**: Data lake for storing student CVs and course catalogs.
- **AWS IAM & ACLs**: For fine-grained data access control.
- **RAG Architecture**: To ensure the AI provides accurate info based on private datasets.

 Data Governance (My Special Focus)
As an Information Systems student focused on **Data Engineering**, I implemented a custom **Access Control List (ACL)** system to manage data privacy. This ensures that:
- Certain users (e.g., `career.coach.two`) can access sensitive data like Medical catalogs.
- Others are restricted based on their roles.

Example ACL Configuration:
The project includes a `data-access-control.json` file that defines these permissions to simulate a real-world enterprise environment.

Key Features
- **Skill Gap Analysis**: Compares user CVs against job descriptions.
- **Automated Training Recommendations**: Suggests specific courses from the internal catalog to bridge skill gaps.
- **Multi-domain Support**: Handles data across different sectors (Technology, Medicine, etc.).

 Project Structure
- `/docs`: Contains the full project documentation (PDF).
- `data-access-control.json`: The JSON policy for data security.
- `README.md`: Project summary and setup.


 Author 
 Meshal Ahmad
