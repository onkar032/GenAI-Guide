# Understanding Agentic Systems: Evolution and Advancements

## What Are Agentic Systems?
Agentic systems are AI-driven systems designed to perform tasks autonomously. They involve multiple components that interact dynamically to solve complex problems through reasoning, decision-making, planning, and learning from experience. These systems are not monolithic, static programs but are instead capable of flexible, adaptive behaviors that enable them to tackle complex real-world scenarios.

Agentic systems often rely on Foundation Models (FMs), which are large-scale pre-trained AI models capable of performing a wide range of tasks. These models serve as the backbone for agentic systems, enabling them to integrate tools, reason across multiple steps, use memory, and even make decisions autonomously by accessing external resources such as databases or search engines. Examples of agentic behaviors include:

### Planning and Reasoning: Agentic systems can break down tasks into smaller sub-tasks and solve them step-by-step using reasoning capabilities.
Tool Usage: These systems can interact with tools, such as search engines or databases, to gather and process information as part of their decision-making process.
Self-Reflection and Learning: They can reflect on their actions, learn from past mistakes, and iteratively improve their performance.
Evolution of Agentic Systems
Agentic systems have evolved significantly over the last few decades, transitioning from simple rule-based programs to complex, learning-based systems:

**Rule-Based Systems (Early AI):** In the initial stages of AI, agentic systems were rule-based and could only handle specific, predefined tasks. These systems were limited in flexibility as they required hand-crafted rules and could not adapt to new environments or tasks without human intervention.

**Expert Systems (1980s-1990s):** Expert systems marked the first significant evolution, where AI could mimic the decision-making abilities of a human expert in specific domains. They used a combination of rules and knowledge bases to solve tasks but were still static and domain-specific.

**Reinforcement Learning (RL) (2000s):** The introduction of reinforcement learning brought a paradigm shift by enabling agentic systems to learn from their environment. RL allowed systems to make decisions based on rewards and penalties, making them adaptive to a wider range of tasks.

**Deep Learning and Foundation Models (2010s-2020s):** The rise of deep learning and large-scale foundation models like GPT and BERT allowed agentic systems to handle complex, language-based tasks. These systems could understand, generate, and reason with text, improving their flexibility and generality.
Systems such as self-driving cars and robotic assistants became more practical, combining various sensory inputs and decision-making abilities to operate autonomously in the real world.

**Multi-Agent Systems and AI Generating Algorithms (Late 2020s):** Multi-agent systems, where multiple agents work together or compete to solve tasks, became a focal point of research. AI-generating algorithms (AI-GAs), which learn to design AI systems autonomously, began to push the boundaries of agentic systems by exploring the automated creation and optimization of these agents.

Today, many agentic systems can operate across different domains, making them adaptable, self-learning, and capable of working with other agents or humans to solve tasks.

# Unleashing the Power of AI: The Future of Automated Design of Agentic Systems

Artificial Intelligence (AI) is on the cusp of revolutionizing how we design systems capable of performing complex tasks autonomously. In a groundbreaking study by Shengran Hu, Cong Lu, and Jeff Clune, titled "Automated Design of Agentic Systems" (ADAS), the authors propose a novel research area focused on creating agentic systems through automation. This new research marks a significant departure from manual design, which has traditionally dominated AI system development. Here, we’ll dive into the highlights, key takeaways, and future potential of ADAS.

## What is ADAS?
Automated Design of Agentic Systems (ADAS) introduces the concept of using foundation models (FMs) like GPT and Claude to design agentic systems automatically. Agentic systems refer to AI systems that can plan, reason, and use tools iteratively to solve tasks—systems that aren't merely executing pre-programmed steps but dynamically learning and improving over time.

The paper emphasizes that while current models rely heavily on hand-designed solutions—such as prompts, tool use, and memory structures—ADAS aims to automate this process. It proposes using meta-agents, which are AI models capable of programming new agents based on code. These agents are automatically refined, tested, and improved in a continuous cycle, resulting in designs that are more robust and powerful than manually created agents.

## What’s New in ADAS?
The most significant advancement in ADAS lies in its ability to automatically design agents in code, allowing AI systems to innovate new solutions without human intervention. The authors propose a "Meta Agent Search" algorithm, which iteratively programs new agents, tests their performance, and uses past discoveries to inform future designs.

## Here’s a snapshot of the key innovations:

### Meta Agent Search: A meta-agent autonomously creates new agentic systems, evaluates them, and iteratively refines them.

**Cross-domain Transferability:** The discovered agents not only perform well in their designed domain but also excel when transferred across different domains and models.

**Generalizability:** Agents discovered through Meta Agent Search have proven their robustness across fields like coding, math, and science, significantly outperforming state-of-the-art hand-designed agents.
**Key Findings:** The authors tested their Meta Agent Search algorithm across multiple domains, demonstrating its superiority over traditional methods. For example:

**In reading comprehension tasks, agents discovered via ADAS improved F1 scores by 13.6%.**

**In math problem-solving, they outperformed baseline models by over 14%.**

**The transferability of these agents across domains further emphasizes their flexibility and general utility, illustrating that agents developed for one task can perform well in unrelated fields like science or coding.**

**Why It Matters**
The ADAS approach to designing agentic systems automatically represents a paradigm shift. It removes the need for manual effort in developing intricate, task-specific AI systems. This ability to autonomously invent new system components, control flows, and combinations of these elements is a significant leap forward.

The paper argues that this automation is not just efficient but also potentially faster and more effective than manual efforts, especially when scaling AI solutions to real-world applications. Given the success of ADAS in improving agent robustness and transferability, this research may prove to be a game changer for industries that rely on complex AI systems for automation, decision-making, and more.

### Looking Ahead: Future Directions for ADAS
The authors propose several exciting future research directions. One involves "Higher-order ADAS," where meta-agents can themselves be improved by ADAS, creating a recursive loop of ever-improving agents. Another potential direction is "Multi-objective ADAS," which would allow agents to optimize for multiple objectives, such as cost, efficiency, and safety, in real-time. The paper also highlights the importance of safely developing ADAS, considering the implications of executing untrusted model-generated code.

### Conclusion
In a world where AI systems are becoming more integral to everyday life, the ability to design more powerful, general-purpose agents automatically is crucial. The innovations presented in the "Automated Design of Agentic Systems" paper underscore the future potential of AI. By harnessing the power of meta-agents, ADAS offers a glimpse into a future where AI systems can self-improve, becoming not only more powerful but also more generalizable across domains.

The work of Shengran Hu, Cong Lu, and Jeff Clune opens new avenues for research and development in AI and agentic systems, pushing the boundaries of what’s possible in AI-driven automation.

For more detailed insights, check out the full paper and code available on their GitHub repository: [ADAS GitHub.](https://github.com/ShengranHu/ADAS)
