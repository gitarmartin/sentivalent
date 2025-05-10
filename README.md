# The Sentivalent Manifesto: Building the Next Generation of truly useful Open-Source On-Premises AI Development Assistants

Open source: no money involved, unless the project is successful and you end up selling consulting, hosted solutions, or creating product spin-offs like the PayPal Mafia.

This is an ambitious open-source project aiming to create a comprehensive on-premise AI solution for developers - automating work of midlevel software engineers. This AI assistant would go beyond basic code suggestions. For example Sourcegraph.com claims to be all of this, but it is not.

> "_Accomplish anything you <ins>want</ins> by breaking down the path to your goal, first into understanding and learning the skills and qualities needed to progress, and then creating an iterative plan of actions that move you towards your goal, one small step at a time._" - Martin Terra

> "_AI could more efficiently handle black box coding tasks—implementing a given specification by any means necessary, even if the process is somewhat opaque, like with LLMs or image generation—compared to trying to replicate the often convoluted and redundant code produced by human programmers. The more quantized the state space can be made (not necessarily in an uniform manner), the more complete training can be performed, thus yielding more predictable outcomes._" - Martin Terra

- AI models, particularly those like Large Language Models (LLMs), can generate code based on given specifications without needing to follow traditional human coding practices. This can lead to more efficient and streamlined solutions, as the AI isn't constrained by the same habits and complexities that human coders might introduce.
- While AI can handle many coding tasks efficiently, it still faces challenges in understanding and implementing complex, nuanced requirements that might benefit from human creativity and experience. Additionally, ensuring the transparency and traceability of AI-generated code remains an important consideration.

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
    - A mechanism that can maintain a coherent and self-consistent corpus of requirements and tha allows making amendments to it, but every time a change request is made, it will require to resolve any conflicts that may exist between the addition and the existing corpus?
- Self-prompt-engineer to produce incremental deliverable. Perhaps self-iterate before delivery until proggress is too slow using the likes of Pareto Principle to assess whether there is need to deliver and request for feedback due to diminishing returns of self-iteration regarding further reworking of a particular partial deliverable of a particular action point.
- Rinse and repeat until metrics that include sentiment of received feedback indicate sufficent completeness (or postpone/escalate to await missing information). If contradicting infotmation arrives later, it can also lead to the reversal of some or all deliverables of associated action poins, but the AI can simply think of this as "moving forward" (changing code/deliverables forward instead of backwards, to achieve equivalent necessary result), thus no actual revert operation needed.
- Can work virtually on multiple parallel tasks like a swarm. Overall velocity is mind boggling. Humans can keep up and comprehend what it entails only at a very high level, or on a per-review basis. Eventually humans will also review only higher level items and the swarm would propagate the effects of these to the finer detail levels.
- In coding style tasks, the version control system facilitates a "locking/synchronization" mechanism that prevents incoherent results due to parallel working threads making simultaneous changes. If overlapping changes found, the later thread must adapt to the code earlier committed and revise its deliverable, and perhaps give feedback to the other thread. On the other hand, for the AI in this situation it will be mroe efficient to simply implement necessary changes and simply notify the other affected threads/action points about the necessary adjustments made. Other kind of collaborative documents might need their own kind of conflict resolution or perhaps CSMA/CD style collision detection.

|Overview
|:----------
|● has chats like an online ai chat
|● has access to my ticket repository so we can discuss and modify/draft tickets
|● has access to company/project wide self documenting coding, tdd/bdd unit/automatable testing and naming standards, conventions and best practices (including any commit message templates & standards, branch naming recommendations) to adhere to
|● has access to user facing documentation for user perspective
|● has access to my code base for code perspective (multiple code repositories if necessary)
|● has configuration authentication/authorization rules for users/ticket contexts/code contexts/repositories to prevent unauthorized access/modification
|**Workflow:** I can open a discussion about a change, possibly related to existing ticket(s) and it will:
|● discuss the change request in the chat, to understand what is needed. Multiple users can join the same discussion, like in team chats.
|● If case is new, it will ask if there are some related tickets (it will include these also into the eventual ticket update draft). If ticket exists it will find such information itself.
|● during tasking discussion, the AI will review for background info all necessary related information: user facing documentation, existing code, and related tickets, to get the big picture. Implicitly but effectively this also ties feedback from past ticket history/performance to future endeavors.
|● If a change depends on another ticket or external factor, such an item will simply come up in the process (foreseen or un-foreseen) and resolved like any other design related matter.
|● If multiple users in the chat have conflicting ideas or requirements, the AI assistant can act as a facilitator and also highlight discrepancies and propose canonical approaches.
|● based on its (iteratively, if necessary) scouting so far, it will discuss proposals in the chat and possibly show some drafts in chat or canvas to ensure it's on the right track; clearly defining the problem the change aims to solve, where feasible by cross-referencing similar past issues or user feedback. This is also the stage where Design, Architecture, and Impact/Implication Analysis are covered at a level suitable for the context.
|● At a suitable step in the process, it will also discuss and review the changes to tickets and user facing documentation.
|● As perfect is the evil of proggress (any omissions can be fixed in further iterations), when it is sufficiently confident (and confirmed by chat participants (or a chat chairperson)), it will open a new version management (e.g.) branch for the change and push the changes (these are subject and open for further discussion; next iterations will go into same branch until merged to target branch). Each commit would contain:
|&nbsp;&nbsp;● Commit story: summary of premise, rationale, and solution, for changes committed; if the idea is just nascent, most of the changes might appear in here and documentative commits.
|&nbsp;&nbsp;● Changed code files or related non-code artifacts
|&nbsp;&nbsp;● Changes to affected user facing documentation in markdown or similar
|&nbsp;&nbsp;● Changes or amendmends to company coding standards and best practices that were agreed on during the iteration
|&nbsp;&nbsp;● Draft state update to associated case ticket(s) (contingent on ticketing system's support for such functionality, otherwise in markdown or similar). It can update multiple ticket(s) update draft(s) per commit.
|● Striking balance of when and what to draft in chat/canvas and what to ask from users before reviewing them from a commit perspective, is part of continuous improvement of the tool itself. Furthermore, depending on the scope of particular case, the optimal stage might vary. When unsure, it would ask for confirmation to proceed with drafting branch update.
|● After each commit the user(s) can request changes or request merge into target branch. After the merge the change flows into the company's default approval process flow which might have different review automation mechanisms and tools, and for a very agile company this might already be the final step and its requirements would need to include all necessary aspects. Automatable (also UI) tests are already included in the code, but if manual testing is required, this should be performed before requesting merge into target branch. Also any codebase-wide regression tests and validations (syntax etc.) should be run before proceeding with merge into target branch, and if any conflicts arise, users must decide whether they are resolved within the same ticket or a related later ticket (this case can be made to include the creation of a new related open ticket).
|● For accountability, especially in regulated environments, teams need to trace changes back to discussions, approvals, and the assistant’s actions (e.g., who approved a merge, what discussions led to a change). These shall be both mentioned in the "story" and logged into the ticketing system in a more tractable way.
|● Any non-code artifacts shall be committed as if they were code, unless need for a different workflow arises and needs to be implemented later and will be managed via the tool's own RFE repository.
|● If a change needs to be aborted or paused midway, the ticketing and versioning systems are assumed to support these primitives. The users can choose whether and when to delete such nodes if they're past their usefulness and there can be a separate housekeeping task+ui that checks and notifies about these.
|● If users frequently modify AI's code suggestions or reject its approaches in a way that is not directly assignable to the referenced coding standards guide, the assistant should have its own typical chatbot style features to learn from the interactions and this should follow more the general mainstream chatbot best practices evolution.
|● The chat remembers what it can within the chat (like AI chats do) but it can also refer the already committed stories and changes and mentioned source materials (depending on temperature, it should be able to arrive at somewhat identical results repeatably).
|● The specification assumes real-time chat collaboration and currently doesn't make any special considerations for users contributing at different times or email support. If need arises these will be managed via the tool's own RFE repository.

References to similar/relevant projects
- https://githubnext.com/projects/github-spark
- https://github.com/OpenDevin/OpenDevin
- https://github.com/devgpt-labs/devgpt
- https://github.com/phidatahq/phidata
- https://github.com/karpathy/LLM101n
- https://github.com/reworkd/AgentGPT
- https://openai.com/index/finding-gpt4s-mistakes-with-gpt-4/
- https://github.com/microsoft/graphrag
- https://github.com/ItzCrazyKns/Perplexica
- https://github.com/jamesmurdza/awesome-ai-devtools?tab=readme-ov-file
- https://www.nvidia.com/en-us/ai/
- https://www.hebbia.ai/

![Quote from George Hotz about HC coding](https://raw.githubusercontent.com/gitarmartin/sentivalent/main/anchillaries/hc-engineering.jpg)

[![Stargazers over time](https://starchart.cc/gitarmartin/sentivalent.svg?variant=adaptive)](https://starchart.cc/gitarmartin/sentivalent)
