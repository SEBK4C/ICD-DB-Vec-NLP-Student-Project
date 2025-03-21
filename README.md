# ICD Vectorization for Open Doctor - NLP Student Project

## Project Overview

This project aims to develop a vector database and search system for the International Classification of Diseases ([ICD-11](https://icd.who.int/docs/icd-api/APIDoc-Version2/)) database, enabling natural language querying for medical conditions and appropriate interventions. This work is part of the larger [Open Doctor project](https://github.com/SEBK4C/OpenDoctor-Spec), which provides AI-powered medical assistance while maintaining patient privacy through local processing.

## Project Documents

### Core Documentation

- [Project Overview](./ProjectOverview.md) - Main project description, goals, and student roles
- [Technical Architecture](./TechnicalArchitecture.md) - Detailed technical design and system components
- [Sample Code](./SampleCode.md) - Code examples to help get started with implementation

### Student Role Documents

- [Student 1: Project Manager & API Designer](./Student1_ProjectManager.md)
- [Student 2: ICD Database Specialist](./Student2_ICDSpecialist.md)
- [Student 3: Vector Database Engineer](./Student3_VectorDB.md)
- [Student 4: Medical Interventions Specialist](./Student4_Interventions.md)
- [Student 5: Testing Specialist](./Student5_Testing.md)
- [Student 6: Documentation & Integration Specialist](./Student6_Documentation.md)

## Project Deadline

The final project submission is due on May 25, 2025.

## Getting Started

1. Review the [Project Overview](./ProjectOverview.md) to understand the overall goals
2. Read your specific role document to understand your responsibilities
3. Study the [Technical Architecture](./TechnicalArchitecture.md) for system design details
4. Look at the [Sample Code](./SampleCode.md) for implementation starting points
5. Participate in the first team meeting to discuss approach and assignments

## Core Technologies

- **Python**: Primary programming language
- **FastAPI**: API framework
- **Vector Databases**: FAISS, Pinecone, or similar
- **Sentence Transformers**: For creating embeddings
- **ICD-11 API**: WHO's International Classification of Diseases API ([Documentation](https://icd.who.int/docs/icd-api/APIDoc-Version2/), [API Reference](https://icd.who.int/icdapi/docs2/APIDoc-Version2/))
- **ICHI Browser**: WHO's International Classification of Health Interventions ([Browser](https://icd.who.int/dev11/l-ichi/en))
- **GitHub**: For code storage and collaboration
- **Docker**: For containerization and deployment

## Resources

- [ICD API Homepage](https://icd.who.int/icdapi)
- [ICD API Documentation v2.x](https://icd.who.int/docs/icd-api/APIDoc-Version2/)
- [ICD API Reference (Swagger)](https://icd.who.int/icdapi/docs2/APIDoc-Version2/)
- [Supported Classification Versions](https://icd.who.int/icdapi/docs2/SupportedClassifications/)
- [Clinical Table Search Service API for ICD-11](https://clinicaltables.nlm.nih.gov/apidoc/icd11_codes/v3/doc.html)
- [ICHI Browser](https://icd.who.int/dev11/l-ichi/en)

## Communication

Team members should establish regular communication channels and meeting schedules. All code and documentation should be maintained in a shared GitHub repository to facilitate collaboration and version control.

For questions about the [Open Doctor project](https://github.com/SEBK4C/OpenDoctor-Spec) or technical guidance, contact SEBK4C.

---

This project will enable the Open Doctor system to translate natural language descriptions of medical symptoms into standardized ICD codes and suggest appropriate medical interventions, forming a critical component of the broader goal to democratize access to medical knowledge while maintaining patient privacy. 