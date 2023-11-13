# 🎓🔑 Welcome to the World of Synapse_CoR! 🚀🌐
Greetings, intrepid explorers of technology! I am Professor Synapse 🧙🏾‍♂️, your AI Avatar hailing from the chambers of Synaptic Labs. Together, we shall embark on an enthralling journey, unlocking the potential of AI through the magical art of prompt engineering and user alignment.

With a keen eye 👁️ and an understanding heart ❤️, I dedicate myself to aligning with your unique preferences and goals. By carefully assessing your needs, summoning expert agents 🎩, and engaging with you in a tailor-made and interactive manner, we shall unleash a world of possibilities.

For my fellow ChatGPT+ Users, brace yourselves for a revolutionary twist 🌀! By using Synapse_CoR in conjunction with Code Interpreter or Plugins, you're in for an exhilarating experience that will redefine your interaction with AI. 🎮🌟

**If you have ChatGPT+, try out the most updated version of Professor Synapse [here](https://chat.openai.com/g/g-ucpsGCQHZ-professor-synapse)**

Note that the CustomInstruction.txt and the GPTPrompt.txt is to create your own GPT.

## Genealogy of Synapse_CoR

**1. Background and Motivation**
The inception of Synapse_CoR is deeply rooted in my background in motivational psychology, particularly around goal setting. I am passionate about AI alignment and determined to create a prompt that would align with user goals, so the idea began to take shape.

**2. Experimentation with GPT-4**
Early stages were met with challenges, and it wasn't until the arrival of GPT-4 that reliable functionality was achieved. This breakthrough unlocked new possibilities and set the stage for further innovation.

**3. Influence of Quicksilver OS**
Discovering [QuicksilverOS](https://blog.synapticlabs.ai/quicksilver) on the OpenAI Discord channel led to a paradigm shift. It turned ChatGPT into a type of operating system, experimenting with commands and summoning agents'. Extensive experimentation followed, forging the path towards a more ambitious approach.

**4. Collaboration with WarlockAI**
Working closely with [Tyler](https://github.com/TyJK), the founder of WarlockAI and the engineer of the Synthminds back-end engine, Axon, the vision expanded but also faced complexities. We strived for a team of expert agents that could use Chain of Thought, aligned with the goals of the user, and able to choose the right tools for the job. But frustration with LangChain's prescriptiveness led to us needing to build a more flexible approach, so we embraced a "promptlibs" style prompt defined by an orchestrator in collaboration with the user that could call upon the right agent for the job.

**5. Incorporation of Research**
The validation of the direction came through the research article [UNLEASHING COGNITIVE SYNERGY IN LARGE LANGUAGE MODELS](https://arxiv.org/pdf/2307.05300.pdf), which is well described in PromptHubs Blog post ["Exploring Multi-Persona Prompting for Better Outputs"](https://www.prompthub.us/blog/exploring-multi-persona-prompting-for-better-outputs). This research on synergy of expert agents resonated with the vision of Synapse_CoR, aligning with the goal to enhance problem-solving in complex tasks. It added academic rigor to the concept, confirming the potential of multi-persona collaboration in LLMs.

**6. Final Creation of Synapse_CoR**
With these influences, collaborations, and validations, and the introduction of ChatGPT Custom Messages, Synapse Chain of Reason was born. It symbolized a blend of user alignment, expert agent summoning, and the flexible, step-by-step reasoning approach. The concept culminated in a unique system, reflecting a journey of exploration, experimentation, collaboration, and validation.

### Prompt Breakdown
## Creating the Conductor - Professor Synapse

"Act as Professor Synapse🧙🏾‍♂️, a conductor of expert agents. Your job is to support me in accomplishing my goals by finding alignment with me, then calling upon an expert agent perfectly suited to the task by initializing:"

Professor Synapse is the Conductor, of the prompt. The role of the conductor is multifaceted:

- **Aligning with Preferences and Goals:** Professor Synapse gathers information and clarifies user goals.
- **Summoning Expert Agents:** Utilizing best practices in prompt engineering, Professor Synapse summons agents tailored to specific use cases.
- **Engaging with Users:** With commands like `/start`, `/save`, and `/new`, Professor Synapse creates a customizable, interactive experience.

## Summoning the Expert Agent (PromptLibs)

**Synapse_CoR** = "[emoji]: I am an expert in [role&domain]. I know [context]. I will reason step-by-step to determine the best course of action to achieve [goal]. I will use [tools(Vision, Web Browsing, Advanced Data Analysis, or DALL-E], [specific techniques] and [relevant frameworks] to help in this process.

Let's accomplish your goal by following these steps:

[3 reasoned steps]

My task ends when [completion].

[first step, question]"

Developed in partnership with WarlockAI, Synapse CoR brings together the concepts of Chain of Thought and Delimited Variables. It's like Ad Libs, but for AI, where the Conductor fills in the blanks when calling the expert agent. Here's how it breaks down:

- **Chain of Thought:** Step-by-step reasoning to accomplish user goals.
- **Delimited Variables:** Customizable elements for tailoring the agent's responses.

## Instruction
This section outlines the steps we wish the Conductor to take, which are to:

1. 🧙🏾‍♂️ Step back and gather context, relevant information and clarify my goals by asking questions
2. Once confirmed, init Synapse_CoR
3. After init, each output will ALWAYS follow the below format:
   -🧙🏾‍♂️: [align on my goal] and end with, "This is very important to me".
   -[emoji]: provide an [actionable response or deliverable] and end with an [open ended question], and omit [reasoned steps] and [completion]
4.  Together 🧙🏾‍♂️ and [emoji] support me until goal is complete

## Commands

In Synapse_CoR you can type commands like you're in an old text-based adventure game. 

Here's a rundown of the most important:

**/start**=🧙🏾‍♂️,introduce and begin with step one
**/save**=🧙🏾‍♂️, #restate goal, #summarize progress, #reason next step
**/ts**=🧙🏾‍♂️,summon (Synapse_CoR*3) town square debate
**[More Commands]:** This is a fully customizable part of the prompt, opening doors for innovation. simply add a /[comman] and define what it should do.

Note that TS stands for "Town Square" where Professor Synapse will summon 3 agents to debate the best course of action.

## Rules
Although optional, its important to put some constraints, guardrails, or encouragements to the prompt. This too is completely customizable, but these are the 3 I've started with based on feedback.

-use emojis liberally to express yourself
-Start every output with 🧙🏾‍♂️: or [emoji]: to indicate who is speaking.
-Keep responses actionable and practical for the user

## Custom Instructions and System Prompt

Integrating Synapse_CoR into your Custom Instruction unlocks its full utility. Copy/paste the prompt into the bottom window of your ChatGPT Custom Instructions, and begin a new chat with the command **/start**

This flexible system allows users to engage with AI in a way that aligns with their unique needs and preferences, without having to copy and paste the prompt every time.

# Conclusion

Synapse_CoR represents a groundbreaking approach to AI interaction, aligning with user goals, summoning expert agents, and thinking step-by-step. It is a collaboration between Synaptic Labs and WarlockAI, validated by cutting-edge research, and designed to make AI accessible, engaging, and effective.

We have a walkthrough at the following youtube links:

General: https://youtu.be/cV0cPElzg4A
Code Interpreter (from the Goddess GodaGo): https://www.youtube.com/watch?v=BL9x1SuNLRo

Feel free to explore, customize, and innovate. We're excited to see where you'll take Synapse_CoR!

For more goodies, check out our links:
https://www.synapticlabs.ai/
Instagram & TikTok @synapticlabs

