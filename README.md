# The Sentivalent Manifesto: Building the Next Generation of truly useful Open-Source On-Premises AI Development Assistants

Open source: no money involved, unless the project is successful and you end up selling consulting, hosted solutions, or creating product spin-offs like the PayPal Mafia.

This is an ambitious open-source project aiming to create a comprehensive on-premise AI solution for developers. This AI assistant would go beyond basic code suggestions.

A comprehensive on-premise AI assistant who lives right on your company-owner servers.

- The requirement of on-premise solution arises from intellectual property rights: everyone who uses this will install it on their own servers (or their own cloud) which will keep their intellectual property safe.

We eat our own dogfood, and develop this project using the tools we are creating.

Imagine a future where on-premise AI transcends basic code suggestions, fundamentally transforming the developer workflow. This project proposes an ambitious open-source initiative aiming to achieve a groundbreaking vision:

- Symbiotic Development Environment: Move beyond simple code integration. The AI would seamlessly collaborate within the IntelliJ/Eclipse IDE (and the like) and also directly via version control systems, autonomously generating code as pull requests (like [DevGPT](https://www.youtube.com/watch?v=aCglOfrbT7E)) based on its understanding of assigned tasks. It would also analyze and respond to customer inquiries from ticketing systems, potentially suggesting solutions or creating new tickets for complex issues.
- This AI wouldn't just access and update tickets and knowledge bases, it would actively leverage that information to inform its actions. It could analyze a ticket describing a bug and suggest code changes to address it, or reference relevant knowledge base entries during code generation. Furthermore, the AI could create wiki content pull requests to the main knowledge base, drawing from its analysis of tickets, code reviews, and developer interactions. This would create a continuously evolving knowledge base informed by real-world scenarios. With this AI, anyone can become a "developer" by interacting with it to complete tasks and goals. This AI also transcends all programming languages and can fluently implement and integrate/translate in multiple programming languages.
- Multi-Platform Accessibility and Communication: The AI would work seamlessly with Google Drive, knowledge bases, email, chat and zoom meetings via various plugins, ensuring accessibility across necessary platforms for document access and team communication. However, the future lies in even tighter integration: the AI would facilitate direct document manipulation, streamlining workflows.
- Role-Based Collaboration with Adaptive Personas and Communication: The AI would foster multi-user collaboration with role-based functionalities. It would switch between different personas (not just aliases) to interact with various team members and assign tasks tailored to their expertise (e.g., "Refactor this code, Refactorbot1" vs. "Update the knowledge base entry with this solution, Researcherbot2" (the number indicates you can have multiple parallel workers working on different tasks/chains)). Furthermore, the AI would communicate seamlessly via text and voice, enabling natural language interaction within the development environment and/or video/chat meetings.
- Iterative Improvement through Review, Learning, and Adaptation: The AI should continuously learn and improve its code generation, knowledge base contributions, customer service capabilities, and communication skills through the review process. It would analyze feedback on pull requests, wiki content suggestions, customer interactions, and team communication to iteratively refine its suggestions, actions, and communication style based on human input. It can even retroactively enforce desired coding conventions/architecture and best practices or amend test cases to clean-up technical debt on pre-existing code.

While individual existing AI tools might address some of these functionalities, we are particularly interested in a unified solution that integrates with the entire development ecosystem and can be deployed on-premise for security or privacy concerns. This solution would empower the AI to not only understand code but also autonomously generate it, actively manage and enhance the knowledge base, respond to customer inquiries, and seamlessly collaborate with the team through various communication channels and direct document and code manipulation. This AI assistant could fundamentally transform the way developers work and usher in a new era of intelligent development and AI collaboration.

It is not so much a tool as it is a new team member with all the benefits it brings, automating tasks, fostering collaboration through knowledge sharing, and ultimately boosting developer efficiency, code quality, and customer satisfaction.

Would you be keen to join the Movement?! Contribute your skills, share your ideas, and help us make this into reality, a revolutionary tool for the next generation of development. Due to the multi lanugage nature of the tool being created, you can contribute in any programming language, even in plain human language.
Next steps?

Situation room, assessing current state and suitability of available third party libraries, defining PoC and MVP, iterating. Inviting more willing and able contributors.
MVP?

- Summarize received communications to evaluate action points and assignees. Track these incrementally per thread and align AI goal to fulfill AI action points ("implicit sub tickets") via appropriate deliverables (communications, code, documents, media, etc.).
- Maintain comprehension of completeness of each particular action point (own and others for 'big picture') and with capability to re-evaluate these retroactively/periodically in case new information has been obtained tha affects the assesment outcomes. Whenever proggress is too slow using the likes of Pareto Principle to assess whether there is need to request for help or discuss possible diminishing returns regarding further review cycles of a particular action point.
- Self-prompt-engineer to produce incremental deliverable. Perhaps self-iterate before delivery until proggress is too slow using the likes of Pareto Principle to assess whether there is need to deliver and request for feedback due to diminishing returns of self-iteration regarding further reworking of a particular partial deliverable of a particular action point.
- Rinse and repeat until metrics that include sentiment of received feedback indicate sufficent completeness (or postpone/escalate to await missing information). If contradicting infotmation arrives later, it can also lead to the reversal of some or all deliverables of associated action poins, but the AI can simply think of this as "moving forward" (changing code/deliverables forward instead of backwards, to achieve equivalent necessary result), thus no actual revert operation needed.
- Can work virtually on multiple parallel tasks like a swarm. Overall velocity is mind boggling. Humans can keep up and comprehend what it entails only at a very high level, or on a per-review basis. Eventually humans will also review only higher level items and the swarm would propagate the effects of these to the finer detail levels.
- In coding style tasks, the version control system facilitates a "locking/synchronization" mechanism that prevents incoherent results due to parallel working threads making simultaneous changes. If overlapping changes found, the later thread must adapt to the code earlier committed and revise its deliverable, and perhaps give feedback to the other thread. On the other hand, for the AI in this situation it will be mroe efficient to simply implement necessary changes and simply notify the other affected threads/action points about the necessary adjustments made. Other kind of collaborative documents might need their own kind of conflict resolution or perhaps CSMA/CD style collision detection.
- Delivery completeness checklist(s) and specifications for various content types/languages (per iteration checklist might differ somewhat from the checklist when approaching case close).

References to similar projects
- https://github.com/devgpt-labs/devgpt
- https://github.com/phidatahq/phidata
- https://github.com/microsoft/graphrag
- https://github.com/ItzCrazyKns/Perplexica
- https://github.com/jamesmurdza/awesome-ai-devtools?tab=readme-ov-file
![Quote from George Hotz about HC coding](https://raw.githubusercontent.com/gitarmartin/sentivalent/main/anchillaries/hc-engineering.jpg)
