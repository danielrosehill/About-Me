# Tech & AI Journey

[![Made with Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](https://www.markdownguide.org/)
[![AI Enthusiast](https://img.shields.io/badge/AI-Enthusiast-brightgreen.svg)](https://github.com/)
[![LLM Projects](https://img.shields.io/badge/LLM-Projects-blue.svg)](https://github.com/)

## 📚 Table of Contents

- [Tech \& AI Journey](#tech--ai-journey)
  - [📚 Table of Contents](#-table-of-contents)
    - [The Initial Spark: A Home Automation Success](#the-initial-spark-a-home-automation-success)
- [Interest in: Curating LLM Outputs \& AI-Derived Knowledge Development](#interest-in-curating-llm-outputs--ai-derived-knowledge-development)
    - [From Output to Insight: The Value of Preservation](#from-output-to-insight-the-value-of-preservation)
    - [Contextual Data Mining: Building a Personal "Context Repo"](#contextual-data-mining-building-a-personal-context-repo)
    - [The Deep Challenge of Contextual AI](#the-deep-challenge-of-contextual-ai)
    - [Experiments in Contextual Data Generation: Multi-Agent Systems](#experiments-in-contextual-data-generation-multi-agent-systems)
    - [By Abstracting The Mundane Details Of Technology, AI Allows Creativity To Flourish](#by-abstracting-the-mundane-details-of-technology-ai-allows-creativity-to-flourish)
    - [My Long-Term Vision](#my-long-term-vision)
  - [Footnotes](#footnotes)

I'm enormously interested in exploring the many ways large language models can provide utility in everyday use cases (boring intro, I know, but let me warm up).

### The Initial Spark: A Home Automation Success

My fascination with AI and LLMs ignited around February 2024 when ChatGPT wrote a Home Assistant YAML configuration that, to my amazement, worked flawlessly on the first run *(I mean, it could have turned the TV off and I would have been pretty impressed)*.

Watching lights turn off in a sequence that a *computer* had successfully programmed – with little more intervention than me asking for help as if I were talking to a highly competent and always-available coding sidekick – was both a lightbulb moment (in a literal sense!) and a breakthrough so exciting that I spent the night wondering what else this amazing advance in technology could offer.

---

# Interest in: Curating LLM Outputs & AI-Derived Knowledge Development

My fascination with AI has unfolded quite naturally in a series of evolutions.

### From Output to Insight: The Value of Preservation
Having discovered that with some careful prompt engineering even chat interfaces could yield staggering insight and value (sometimes!), the digital prepper in me kicked into overdrive. I began thinking about how these "outputs" (completions) could be preserved and organised so they don't vanish into the digital ether (output storage remains, sadly, a much neglected topic!).
Building my own modest CRUD interface to store these outputs ("Output Hub"!) then led to the second realisation<sup>1</sup>: while numbers and statistical models are what's happening under the hood, text is the layer at which humans provide information to LLMs and get information back from them. Curating it is key to leveraging it to maximal effect.

### Contextual Data Mining: Building a Personal "Context Repo"
An unintended benefit of carefully curating outputs was discovering that those same outputs could be mined for contextual data and then reintroduced in subsequent interactions. My boring but demonstrative example is a five-line markdown file laying out the key details of my OS and hardware, which can single-handedly do everything from making highly useful recommendations for local models to run to helping me pick out a hardware upgrade without tedious component checking.
I developed an interest in deliberately and selectively curating a repository of personal information (like a few others toying around with the idea, I naturally gravitated to the language of "context repo").

---

### The Deep Challenge of Contextual AI
Imagining how to develop a "context repo" is a work in progress and by no means easy. Inevitably, it leads to rather stark realisations about life: without contextual awareness and memory, human life would be meaningless!
Our very cognition is a byproduct of the passage of innumerable memories, thoughts, and feelings. Without the context of our lives determining the value of information to us, the sea of information surrounding us is irrelevant (because it is bereft of *meaning*).

Our life's "context," moreover, is in a constant state of flux. In the drab terms of database systems, it might be described as an immensely nodal network of data with a constant level of file operations that defy the type of technical architectures we have at our disposal today. So, I think it's no exaggeration to say that the technical challenge of reflecting this in the type of AI systems needed to develop transformative and personal experiences is significant, worthwhile, and hugely important to how humans will best harness the technology.

---

### Experiments in Contextual Data Generation: Multi-Agent Systems

On a more practical level:

One of my experiments-in-progress involves a multi-agent system for proactively developing contextual data. The mechanics are simple: one agent interviews you, another tries to distill it to the contextual clues, and finally, it's factorized in a context database. I don't view this as the ultimate solution or direction that personalized AI systems will take, but it is proving an interesting experiment in how one might kick-start a personal RAG system of sorts.

---

### By Abstracting The Mundane Details Of Technology, AI Allows Creativity To Flourish

My favorite part of exploring AI at the moment, however, is actually the perhaps unloved art of writing system prompts: the configurations that take the final product of the LLM produced by the vendor and imbue it with subtle or definitive direction, personality, and nuance.

System prompt writing exemplifies how generative AI tools have provided creatives with access to technology in a way that is transformative and wonderful. It allows us to think beyond the mechanics of orchestrating API calls, storing context, and choosing database types. It allows our minds to think freely about how humans can leverage intelligent computers to improve not only their lives, but the world around them and their relationships with others. I've written a collection of over 700 system prompts to date, of which more than 600 are open-sourced (here, on Hugging Face, and other nooks and crannies of the internet).

---

### My Long-Term Vision

I'm motivated by the idea and conviction that beyond the hype surrounding the latest and greatest models with reasoning powers that may lack current applicability is a less glamorous but longer-term transformation. 

This transformation will flourish not over individual release cycles or months but over the course of decades through the collective efforts of technologists, ethicists, creatives, thinkers, and everybody else who believes that AI is a change worth nurturing. If I can play even a microscopic role in that direction, it will be a positive contribution.

---

## Footnotes

1: I discovered DALLE a few years prior to really exploring AI and LLMs and, being the highly mature and evolved grown-up that I am, my first prompt was: *"Show a sloth in a suit shopping for leaves in a supermarket. The other shoppers are a mixture of monkeys and humans but nobody seems astounded by the randomness of the various species casually shopping."* Sadly, I didn't record the image, but the quality of sloth generations has provided a weird kind of yardstick for how far image generation has come over the years. I think that we have sadly, reached "peak AI sloth". But I continue to collect an eclectic gallery of some of my generations on my website. 

I've also coopted them as an kind of signature of sorts for these Github repositories. Both because they're cute, but also because there's something undeniably hillarious about their very existence, which is compounded delightfully when they're depicted in casual human contexts. Sloths are great and (this is true) a latent AI aspiration remains creating a cartoon series with them once AI video gen tools become more affordable and powerful.

2: While I continued to think that output storage is immensely important And that many AI interfaces would at the very least do well to provide basic routing capabilities to databases and knowledge bases, the evolution of MCP Is a clear indication to me that the future of AI output storage will be in existing systems through tool operation and not through the kind of CRUD interface that I developed.