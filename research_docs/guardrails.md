
## Guardrails 
#### Breaking Down the Defenses: A Comparative Survey of Attacks on LLMs (2024)

https://arxiv.org/html/2403.04786v2

This comprehensive survey explores security vulnerabilities and defense strategies for Large Language Models (LLMs). It covers adversarial prompt attacks, data poisoning, privacy leaks, and examines the challenges to LLM integrity. The paper presents a detailed taxonomy of attack methods and defenses, including alignment techniques and guardrails, and highlights their limitations. It serves as a critical resource for practitioners, helping them understand the threat landscape and informing where to apply effective guardrails in LLMs.

#### Adversarial Prompt Evaluation: Benchmarking Guardrails Against Prompt Attacks (IBM Research, 2025)

https://arxiv.org/html/2502.15427v1

This IBM-led study systematically evaluates guardrail defenses against prompt injection and jailbreak attacks. The research tests 15 different guardrail methods on a variety of malicious prompt styles and benign inputs, revealing significant variation in performance. It emphasizes the necessity of layered, adaptive guardrails, warning against relying on static defenses. The findings highlight the importance of thorough testing and combining defenses to address multiple attack vectors.

#### Constitutional Classifiers: Defending Against Universal Jailbreaks (Anthropic, 2025)

https://www.anthropic.com/news/constitutional-classifiers

This paper introduces Constitutional Classifiers, a novel framework for LLM guardrails. Trained on synthetic data derived from explicit "constitution" rules about allowed and disallowed content, these classifiers have shown resilience in red-teaming efforts. The method blocks harmful prompts with minimal refusal rates and computational overhead, making it a promising solution for defending LLMs against sophisticated, multi-step attacks. The work illustrates the effectiveness of policy-driven training and classifier layers in hardening LLMs.

#### Security Best Practices for Generative AI Applications in Azure (Microsoft, 2024)

https://techcommunity.microsoft.com/blog/azurearchitectureblog/security-best-practices-for-genai-applications-openai-in-azure/4027885

Offers a checklist of best practices for securing LLM-powered applications in production. It addresses key challenges, such as protecting data confidentiality, ensuring model reliability, preventing misuse, and complying with AI principles. It covers the implementation of guardrails like data encryption, content filtering, access control, and auditing, providing a blueprint for building secure and compliant LLM applications from day one.

#### Guardrail tools for LLM applications
    
    Google Cloud Model Armor
    Rebuff (OSS)
    LLM Guard (OSS)
    Nemo Guardrails (OSS)
    Protect AI
    Lakera AI
    HiddenLayer
    Amazon Bedrock Guardrails