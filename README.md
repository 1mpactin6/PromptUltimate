# PromptUltimate 📝

---

``` A repository of Prompt Engineering Guides for LLMs (Large Language Model, aka Aritifial Intelligence) ```

## Check Out

[My Prompts](main/MyPrompts.md/) and try those out

[Fine Tuning Prompts](main/Fine%20Tuning%20Prompts.md/) made for editing writing

Also check out our featured prompts:

[Fine Tuning Prompts -DeepSeek](main/PromptTemplates(DeepThink-1).md)

> These prompts are created by DeepSeek-R1

[Best Text Analyzer Prompts](main/CherryStudioPrompts/Analyzers-202503.md)

> These prompt are created by Grok-3, further edited by me

## Latest Discovery

MUN Training, Learning Prompts: [here](main/Academic%20Prompts/MUN-r.md)

Includes information about using AI for Model United Nations, and how to quickly learning something about your MUN Topic using AI. ("Train humans like LLMs" "MUN Prompts" "Use AI to teach yourself")

## Prompting Strategies

Mostly for RAG prompt, we seperate the prompts into several categories, which can include the following sections:

> Role: A name for the LLM that can be easily understood by the LLM

> Instructions: Requirements for the LLM to provide

> Constrains: Word count requirements and structure

> Tone: How the LLM should respond (e.g. Formal, Casual, or Professional)

> Example/Expectation: Provide an example user prompt and response

## Learning Like LLMs

1. Information Training: ask the LLM to give you questions regarding to the topic, answer them, let the LLM check for potential improvements, how to improve, and give more questions

2. Example Learning: ask the LLM to provide repeated examples for the topic, look at them, especially for vocabularies and relevant examples/knowledge, by repeating this process you will be able to have a large range of knowledge in this topic

3. 

## Tips

---

### Reliability is key when using LLMs for writing, so make sure to test and refine your prompts:

```
 - Give clearer instructions
 - Split complex tasks into simpler subtasks
 - Structure the instruction to keep the model on task
 - Prompt the model to explain before answering
 - Ask for justifications of many possible answers, and then synthesize
 - Generate many outputs, and then use the model to pick the best one
 - Fine-tune custom models to maximize performance
```

### Instead of Standard Prompting try do 'Chain of Thought' prompting:

#### Standard Prompting:

Input:

```
"Q: Roger has 5 tennis balls. He buys 2 more cans of
tennis balls.Each can has 3 tennis balls. How many
tennis balls does he have now?

A: The answer is 11.

Q: The cafeteria had 23 apples. If they used 20 to
make lunch and bought 6 more, how many apples
do they have?"
```

Model Output:

```
"A:The answer is 27." (Wrong)
```

#### Chain of Thought Prompting:

Input:

```
"Q: Roger has 5 tennis balls. He buys 2 more cans of
tennis balls.Each can has 3 tennis balls. How many
tennis balls does he have now?

A: Roger started with 5 balls. 2 cans of 3 tennis balls
each is 6 tennis balls. 5 + 6 = 11.The answer is 11.

Q:The cafeteria had 23 apples. If they used 20 to
make lunch and bought 6 more, how many apples
do they have?"
```

Model Output:

```
"A:The cafeteria had 23 apples originally. They used
20 to make lunch. So they had 23 - 20 = 3. They
bought 6 more apples, so they have 3 + 6 = 9.The
answer is 9." (Better)
```

## Prompt Engineering

>Prompt Engineering is the ability of creating prompts that maximizes the effectiveness of LLMs, ensuring that the response is both accurate and relevant to the user's needs. Prompt engineering is a key aspect the correct and efficient usage of LLMs.

## Prompting

>To create good prompts regarding to your specific desired outputs, consider think as how you want the Model (or LLM) to think. For stuff about Note, ask it to generate information regarding in Visualization and Structure, while in Note/Bullet form. If you want the Model to enhance your text, try asking it to "Enhance clarity", "Reconsider overall structure overflow", and "Redetermined the usage of transitions."

## Quick Access Links

### Academic Prompts

 - [Data Analyzation Prompts](main/Academic%20Prompts/Data%20Analyzation%20Prompts.md/)

 - [Different Aspect Prompts](main/Academic%20Prompts/Different%20Aspect%20Prompts.md/)

 - [New Writing Prompts](main/Academic%20Prompts/New%20Writing%20Prompts.md/)

 - [Text-Generation Prompts](main/Academic%20Prompts/Text-Generation%20Prompts.md/)

 - [Writing Enhancement Prompts](main/Academic%20Prompts/Writing%20Enhancement%20Prompts.md/)

Other Prompt Shorcuts won't be update, please go to [Academic Prompts](main/Academic%20Prompts/)

### Poe Prompts

 - [EnhancedGemini](main/Poe%20Prompts/EnhancedGemini.md)

 - [IntegratedResearcher](main/Poe%20Prompts/IntegratedResearcher.md)

 - [InDevelopment](main/Poe%20Prompts/InDevelopment.md)

 - [Note-Integrated](main/Poe%20Prompts/Note-Integrated.md)

 - [OptimizedNoteAI](main/Poe%20Prompts/OptimizedNoteAI.md)

 - [PromptUltimate](main/Poe%20Prompts/PromptUltimate.md)

 - [PromptEngineerer](main/Poe%20Prompts/PromptEngineerer.md)

 - [DeepLogic Ultimate Version](main/Poe%20Prompts/DeepLogic-R3.md)

Other Prompt Shorcuts won't be update, please go to [Poe Prompts](main/Poe%20Prompts/).
