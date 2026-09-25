# llm-policy
My thoughts and rules for agentic coding and LLM usage

> [!IMPORTANT]
> **ALL OF MY PROJECTS CONTAINING ANY AMOUNT OF LLM-GENERATED CODE ARE INDICATED AS SUCH WITH A DISCLAIMER AND A LINK TO THIS DOCUMENT IN THE README**

I have not found LLMs to be particularly intelligent. In my experience, they are not capable of consistently writing complex code, let alone complex programs. Letting an LLM or a group of LLMs write or maintain a complex program is not something I personally see going well. In my workflow and experience, LLMs are good for answering questions or certain coding tasks, as long as they have the right harness and tooling around them, good prompts, and tight constraints. These systems are still evolving, and I don't see them as useful in the way that some industries are touting them quite yet, and I'm not sure LLM technology in its current form can do that at all. I am very willing to be proven wrong on that.

If you are willing to specify absolutely everything an agent needs to do at every step and review *everything* they do *at every single step*, you can get some good results. I have found that doing this often takes as much time and effort as doing it myself, without the valuable processes of trial and error that are essential to the way I learn.

I personally use LLMs in the following ways in my workflow:

- **Answering questions that I would spend significant effort answering by looking through search engine results otherwise.** I am always careful to review the sources used for context and do not trust the knowledge of the model, essentially making it a search engine that understands natural language better. To be clear, that kind of functionality is very useful to me, but it's also considered and controlled in a way that a lot of LLM usage tends not to be.

- **Small amounts of boilerplate code or structured data that I'd likely be copying from Stack Overflow or documentation anyway.** For example, Pi Coding Agent did a decent enough job writing a [theme for itself](https://github.com/ajlardner/pi-coding-agent-config/blob/main/agent/themes/more-contrast.json), which is literally just JSON, with some fairly simple constraints and the context provided by the Pi documentation.

- **Code for the purposes of prototyping, proofs of concept, or examples to learn from.** Using an LLM in these ways, I don't see much risk or issue with copyright or IP theft. I do think it is irresponsible and wrong to let an LLM write an entire program and not acknowledge that doing so is very different and requires very different considerations from writing an entire program yourself.
