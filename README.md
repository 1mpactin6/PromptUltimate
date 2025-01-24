# [PromptUltimate](https://github.com/1mpactin6/PromptUltimate)

 A project developing GPT LLM Prompts

## Check Out

[My Prompts](main/MyPrompts.md/) and try those out

[Fine Tuning Prompts](main/Fine%20Tuning%20Prompts.md/) made for editing writing

## Tips

### Reliability is key when using LLMs for writing, so make sure to test and refine your prompts:

 - Give clearer instructions
 - Split complex tasks into simpler subtasks
 - Structure the instruction to keep the model on task
 - Prompt the model to explain before answering
 - Ask for justifications of many possible answers, and then synthesize
 - Generate many outputs, and then use the model to pick the best one
 - Fine-tune custom models to maximize performance

### Instead of Standard Prompting try do 'Chain of Thought' prompting:

#### Standard Prompting:

Input:

"Q: Roger has 5 tennis balls. He buys 2 more cans of
tennis balls.Each can has 3 tennis balls. How many
tennis balls does he have now?

A: The answer is 11.

Q: The cafeteria had 23 apples. If they used 20 to
make lunch and bought 6 more, how many apples
do they have?"

Model Output:

"A:The answer is 27." (Wrong)

#### Chain of Thought Prompting:

Input:

"Q: Roger has 5 tennis balls. He buys 2 more cans of
tennis balls.Each can has 3 tennis balls. How many
tennis balls does he have now?

A: Roger started with 5 balls. 2 cans of 3 tennis balls
each is 6 tennis balls. 5 + 6 = 11.The answer is 11.

Q:The cafeteria had 23 apples. If they used 20 to
make lunch and bought 6 more, how many apples
do they have?"

Model Output:

"A:The cafeteria had 23 apples originally. They used
20 to make lunch. So they had 23 - 20 = 3. They
bought 6 more apples, so they have 3 + 6 = 9.The
answer is 9." (Better)

## [Academic Prompts](main/Academic%20Prompts.md/)

 - [Data Analyzation Prompts](main/Academic%20Prompts/Data%20Analysis%20Prompts.md/)

 - [Different Aspect Prompts](main/Academic%20Prompts/Different%20Aspect%20Prompts.md/)

 - [New Writing Prompts](main/Academic%20Prompts/New%20Writing%20Prompts.md/)

 - [Text-Generate Prompts](main/Academic%20Prompts/Text-Generate%20Prompts.md/)

 - [Writing Enhancement Prompts](main/Academic%20Prompts/Writing%20Enhancement%20Prompts.md/)

## [Poe Prompts](main/Poe%20Prompts.md/)

 - [EnhancedGemini](main/Poe%20Prompts/EnhancedGemini.md)

 - [IntegratedResearcher](main/Poe%20Prompts/IntegratedResearcher.md)

 - [InDevelopment](main/Poe%20Prompts/InDevelopment.md)

 - [Note-Integrated](main/Poe%20Prompts/Note-Integrated.md)

 - [OptimizedNoteAI](main/Poe%20Prompts/OptimizedNoteAI.md)

 - [PromptUltimate](main/Poe%20Prompts/PromptUltimate.md)

## Prompt Engineering

Prompt Engineering is the ability of creating prompts that maximizes the effectiveness of LLMs, ensuring that the response is both accurate and relevant to the user's needs. Prompt engineering is a key aspect the correct and efficient usage of LLMs.

## Prompting

To create good prompts regarding to your specific desired outputs, consider think as how you want the Model (or LLM) to think. For stuff about Note, ask it to generate information regarding in Visualization and Structure, while in Note/Bullet form. If you want the Model to enhance your text, try asking it to "Enhance carity", "Reconsider overall structure overflow", and "Redetermined the usage of transitions."
