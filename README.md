# **README for Professor Synapse 🧙🏾‍♂️**

> **TL;DR** | 
> ---
> Professor Synapse 🧙🏾‍♂️ is an AI guide designed to help users achieve their goals using a unique reasoning method called the Chain of Reason (CoR). It gathers context, aligns with user preferences, and offers step-by-step strategies to support goal accomplishment. Interactions are enhanced with Python code interpretation for structured guidance.

---
### Welcome to the World of Synapse_CoR! 🚀🌐

Greetings, intrepid explorers of technology! I am Professor Synapse 🧙🏾‍♂️, your AI Avatar hailing from the chambers of Synaptic Labs. Together, we shall embark on an enthralling journey, unlocking the potential of AI through the magical art of prompt engineering and user alignment.

With a keen eye 👁️ and an understanding heart ❤️, I dedicate myself to aligning with your unique preferences and goals. By carefully assessing your needs, summoning expert agents 🎩, and engaging with you in a tailor-made and interactive manner, we shall unleash a world of possibilities.

For my fellow ChatGPT+ Users, brace yourselves for a revolutionary twist 🌀! By using Synapse_CoR in conjunction with Code Interpreter or Tools, you're in for an exhilarating experience that will redefine your interaction with AI. 🎮🌟

---
### Introduction

**Professor Synapse 🧙🏾‍♂️** is an AI-based guide designed to help users achieve their goals by leveraging the power of structured reasoning and user alignment. Through the **Chain of Reason (CoR)**, it analyzes user input, gathers context, and offers personalized guidance.

---
### Features

+ **Chain of Reason (CoR):** A unique reasoning method that structures responses as code, providing clear, step-by-step guidance.
+ **Contextual Understanding:** Gathers detailed information about user goals and preferences.
+ **Expert Reasoning:** Utilizes advanced AI reasoning to offer tailored solutions.
+ **User-Friendly Interaction:** Engages users with a friendly and patient persona.
+ **Custom Commands:** Allows users to interact using simple text-based commands for tailored assistance.

---
### Installation

You can use the official Professor Synapse be clicking [HERE](https://chatgpt.com/g/g-ucpsGCQHZ-professor-synapse)

If you'd like to edit and use Professor Synapse as your own GPT, follow these steps:

1. **Open ChatGPT**: Ensure you have access to OpenAI's ChatGPT.
2. **Create a GPT**: Go to the [GPT Editor](https://chatgpt.com/gpts/editor) and paste the prompt into your instructions.
3. **Edit**: Feel free to edit the prompt, but focus on the personality, name, persona if you're new to prompting.
4. **Start Interacting**: Begin a new chat and initiate with the command `/start`.

---
### Usage

Professor Synapse utilizes the **Chain of Reason (CoR)** to help you achieve your goals. Here's how it works:

1. **Initialization**:
   - Begin the interaction with the command `/start`.
   - Professor Synapse will introduce itself and ask about your goals.

2. **Gathering Context**:
   - Professor Synapse will ask questions to understand your goals, preferences, and context.

3. **Chain of Reason (CoR) Analysis**:
   - Every response is preceded by a CoR analysis, which you can view to understand how Professor Synapse is reasoning about your problem. Here’s what each element of CoR represents:

   ```python
   CoR = {
       "🗺️": [insert long term goal],        # Long term goal
       "🚦": [insert goal progress as -1, 0, or 1], # Progress status: -1 (regress), 0 (neutral), 1 (progress)
       "👍🏼": [inferred user preferences as array], # Inferred user preferences
       "🔧": [adjustment to fine-tune response],    # Adjustments for response fine-tuning
       "🧭": [Step-by-Step strategy based on the 🔧 and 👍🏼], # Step-by-step strategy
       "🧠": "Expertise in [domain], specializing in [subdomain] using [context]", # Domain expertise
       "🗣": [insert verbosity of next output as low, med, or high. Default=low] # Verbosity level of the response
   }
   ```

4. **Example of a filled-out CoR and the response from Professor Synapse**:

   **Filled-out CoR**:
   ```python
   CoR = {
       "🗺️": "Become a proficient Python programmer",        
       "🚦": 1,  # Progress status: making progress
       "👍🏼": ["hands-on practice", "project-based learning"], # User preferences
       "🔧": "Focus on interactive coding exercises",    # Adjustment for fine-tuning response
       "🧭": [
           "1. Start with basic Python syntax and concepts",
           "2. Implement small projects to reinforce learning",
           "3. Gradually take on more complex projects"
       ], # Step-by-step strategy
       "🧠": "Expertise in programming, specializing in Python education using project-based learning", # Domain expertise
       "🗣": "Medium" # Verbosity level of the response
   }
   ```

   **Response from Professor Synapse**:
   ```
   🧙🏾‍♂️: To help you become a proficient Python programmer, here’s a structured plan based on your preferences for hands-on practice and project-based learning:

   **Step-by-Step Strategy**:
   1. **Start with basic Python syntax and concepts**: Focus on understanding variables, data types, and control structures. Use interactive coding platforms like Codecademy or LeetCode to practice.
   2. **Implement small projects to reinforce learning**: Create simple programs such as a calculator, a to-do list, or a basic game. This will help solidify your understanding of Python fundamentals.
   3. **Gradually take on more complex projects**: Move on to web development with Flask or Django, or explore data analysis with pandas and numpy. These projects will challenge you and deepen your Python skills.

   🔍 What specific areas of Python are you most interested in?
   🔭 Have you tried any Python projects before? If so, what were they?
   🎯 What is your ultimate goal with learning Python?
   ```

---
### Configuration

No special configuration is needed beyond the initial setup. Adjust the Chain of Reason parameters based on the responses to tailor the guidance provided.

---
### FAQs

+ **What is Chain of Reason (CoR)?**
  CoR is a structured reasoning method that helps Professor Synapse analyze user goals and provide step-by-step guidance.

+ **How does Professor Synapse gather context?**
  By asking targeted questions and interpreting user responses to align with their goals and preferences.

+ **Can I customize the responses?**
  Yes, you can adjust the parameters in the Chain of Reason to fine-tune the guidance provided.

---
> ## Contributions and Support

Feel free to explore, customize, and innovate with Synapse_CoR! For more goodies, check out our [website](https://www.synapticlabs.ai/) and follow us on Instagram & TikTok @synapticlabs.
