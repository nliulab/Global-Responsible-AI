# 🌍 Global Landscape of Responsible AI in Healthcare: A Comprehensive Guide

Welcome to the **Global Responsible AI Landscape** repository! This repository is a curated collection of guidelines, policies, research institutes, and tools related to the development and deployment of Responsible AI around the world. Our goal is to provide an organized and narrative-rich resource that bridges technical, ethical, and governance aspects of AI in healthcare and beyond.

## 📌 Why This Repository?

The rapid advancement of AI technologies has brought immense opportunities and challenges. Ensuring responsible AI requires:

- **Robust Guidelines & Frameworks**: Frameworks to guide AI development and deployment.
- **Effective Policies**: Governance structures to regulate AI use ethically and equitably.
- **Collaborative Research**: Institutes and organizations leading the way in RAI initiatives.

This repository goes beyond simple listings to offer contextual narratives that explain the importance and application of each resource.

## 📩 Contact Us

We value your input and are here to answer your questions or hear your suggestions! For inquiries, please reach out to:  
- **Yian Ma** at [yian.ma@nus.edu.sg](mailto:yian.ma@nus.edu.sg)
- **Nan Liu** at [liu.nan@duke-nus.edu.sg](mailto:liu.nan@duke-nus.edu.sg)  

## 🌀 The AI Lifecycle: A Holistic Approach

The development of AI systems follows a structured lifecycle, encompassing multiple phases from initial ideation to long-term maintenance. Each phase involves specific processes, challenges, and considerations that contribute to the overall quality and impact of the AI system.  

| **Stage**             | **Description**                                                                                                                                                  | **Key Considerations**                                                                                                                                                           |
|-----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Model Development** | Designing, training, and validating the AI model to achieve specific objectives. Developers select datasets, define model architectures, and employ training methodologies. | Data quality, ensuring representativeness, documenting design choices, addressing biases, and fostering transparency.                                                             |
| **Evaluation**        | Testing the AI system under diverse conditions to ensure reliability, robustness, and fairness.                                                                  | Defining relevant performance metrics, ensuring reproducibility, avoiding misrepresentation of metrics, and considering diverse scenarios.                                        |
| **Bias and Risk Assessment** | Identifying potential pitfalls in the model's predictions, focusing on fairness, safety, and ethical implications.                                             | Evaluating fairness metrics, managing risks proactively, and addressing discrimination, inequities, and societal impacts.                                                        |
| **Implementation**    | Deploying the AI system in real-world settings, integrating it into workflows, providing training, and establishing governance mechanisms.                        | Ensuring scalability, accountability, data privacy, user autonomy, and mitigating risks of inappropriate use.                                                                     |
| **Continuous Monitoring** | Tracking the system's performance and ethical compliance post-deployment, including addressing data drift and updating models.                                   | Maintaining accuracy and relevance, updating for new data, incorporating user feedback, and addressing risks of outdated systems or non-transparent updates.                      |

## 📃 Frameworks and Guidelines

| **Name**                                                                 | **Category**         | **Focus Area**             | **AI Lifecycle Step**             | **Description**                                                                                                                                                 |
|--------------------------------------------------------------------------|----------------------|----------------------------|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [ABCDS Framework](https://aihealth.duke.edu/algorithm-based-clinical-decision-support-abcds/) | Prediction Models    | Clinical Decision Support  | Whole Lifecycle                   | Provides a structured approach for the oversight and deployment of AI prediction models, emphasizing monitoring, safety, and quality in real-world applications. |
| [CARE-AI](https://care-ai.health)                                        | Prediction Models    | Ethical and Responsible    | Implementation                    | The Collaborative Assessment for Responsible and Ethical AI Implementation (CARE-AI) tool guides the ethical deployment of AI in healthcare, providing actionable suggestions and decision trees to support diverse real-world settings.                                                |
| [CANAIRI](https://www.nature.com/articles/s41591-024-03364-1)            | Prediction Models    | Translational Trials       | Bias and Risk Assessment          | CANAIRI promotes the use of translational trials to assess the integration of AI systems into real-world clinical workflows, prioritizing fairness and system performance. |
| [CANGARU](https://arxiv.org/abs/2307.08974)                              | LLMs                 | Reporting                  | Model Development                 | Establishes guidelines for responsible use of LLMs like ChatGPT.                                                                                                |
| [CHART](https://bmjopen.bmj.com/content/14/5/e081155)                    | LLMs                 | Chatbot Evaluation         | Evaluation                        | Provides structured reporting standards for evaluating LLM-linked chatbots.                                                                                      |
| [CLAIM](https://pubs.rsna.org/doi/10.1148/ryai.2020200029)               | Prediction Models    | Medical Imaging            | Model Development                 | Guides reporting of AI applications in medical imaging to ensure clarity and reproducibility.                                                                   |
| [DECIDE-AI](https://www.ideal-collaboration.net/projects/decide-ai/)     | Prediction Models    | Decision-Support Systems   | Evaluation                        | Framework for evaluating and reporting early-stage decision-support AI systems in healthcare.                                                                    |
| [FUTURE-AI](https://future-ai.eu)                                        | Prediction Models    | Interdisciplinary Healthcare | Whole Lifecycle                   | Provides 30 best practices for trustworthy AI in healthcare, addressing technical, clinical, ethical, and legal dimensions.                                       |
| [HEAAL Framework](https://healthaipartnership.org/health-equity-across-the-ai-lifecycle-heaal) | Prediction Models    | Health Equity              | Whole Lifecycle                   | Assesses the impact of AI solutions on health equity across five domains.                                                                                       |
| [PROBAST-AI](https://www.probast.org)                                    | Prediction Models    | Bias Assessment            | Bias and Risk Assessment          | Tool for assessing the risk of bias and applicability in AI prediction models.                                                                                   |
| [STARD-AI](https://bmjopen.bmj.com/content/11/6/e047709)                 | Prediction Models    | Reporting Standards        | Evaluation                        | Focuses on diagnostic AI studies, ensuring reproducibility and reliability.                                                                                      |
| [TRIPOD+AI](https://www.tripod-statement.org)                            | Prediction Models    | Prognosis/Diagnosis        | Model Development, Evaluation     | Provides clarity on the development and validation of AI prediction models.                                                                                      |
| [TRIPOD-LLM](https://www.nature.com/articles/s41591-024-03425-5)         | LLMs                 | Reporting and Evaluation   | Model Development, Evaluation     | TRIPOD-LLM extends the TRIPOD guidelines to large language models (LLMs), offering a structured framework for transparent reporting and rigorous evaluation of LLM-based healthcare tools. It emphasizes clarity in data usage, model evaluation, and potential clinical impacts.                                                     |

## 📖 Governance Policies

| **Name**                                                        | **Region**         | **Description**                                                                                                    |
|-----------------------------------------------------------------|--------------------|--------------------------------------------------------------------------------------------------------------------|
| [EU AI Act](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai) | Regional (EU)      | Creates a legal framework categorizing AI systems based on risk levels.                                           |
| [Singapore IMDA Model](https://www.imda.gov.sg)                 | Regional (Singapore) | Outlines principles for ethical AI use, emphasizing transparency and accountability.                              |
| [NIST AI RMF](https://www.nist.gov/itl/ai-risk-management-framework) | Regional (US)      | Offers a structured approach to identifying and managing AI-related risks.                                        |
| [WHO Ethical AI](https://www.who.int/publications/i/item/9789240029200) | Worldwide          | Guides ethical deployment of AI in healthcare with six principles.                                                |
| [WHO LMMs Guideline](https://www.who.int/publications/i/item/9789240084759) | Worldwide          | Provides ethical and practical considerations for large multimodal models.                                        |

## 🏛️ Research Institutes

| **Name**                                                       | **Region**         | **Description**                                                                                                    |
|----------------------------------------------------------------|--------------------|--------------------------------------------------------------------------------------------------------------------|
| [CHAI](https://chai.org/assurance-standards-guide/)            | Worldwide          | Unites experts to establish assurance standards and governance guidelines for equitable and responsible AI integration. |
| [CHARGE-AI](https://chargeai.org)                              | Worldwide          | CHARGE is a community uniting healthcare leaders to discuss AI regulation, governance, ethics, and compliance, shaping a responsible future of health AI.  |
| [DIHI](https://dihi.org)                                       | Regional (US)      | Accelerates innovative healthcare solutions integrating data science and advanced technologies.                    |
| [HEALTHAI](https://www.healthai.agency)                        | Worldwide          | Focuses on advancing responsible AI in healthcare through multi-stakeholder collaboration.                         |
| [Oxford AI Ethics](https://www.oxford-aiethics.ox.ac.uk)       | Regional (UK)      | Explores ethical dilemmas arising from AI technologies.                                                           |
| [Responsible AI Network (RAIN)](https://www.industry.gov.au/science-technology-and-innovation/technology/national-artificial-intelligence-centre/responsible-ai-network) | Regional (Australia) | Promotes ethical AI through collaboration with government, academia, and industry.                                 |
