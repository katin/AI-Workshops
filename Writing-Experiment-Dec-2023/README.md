# Santa Story ChatGPT4 Writing Experiment

### Greetings, Zine readers!
The process of how ChatGPT "thinks" about things and processes writing prompts is fascinating. 
Equally important, however, is how much the prompt writing and process affects the output.
I'm still learning a lot about "prompt engineering", and I don't put forth the prompts I used
in this experiment as model, best-case prompts. I certainly could have put more work and development
into the prompting to get better results here.

However, this serves as an interesting case study and a good example of mid-level prompting.
You'll be able to see how ChatGPT4 doesn't exactly produce good writing out-of-the-gate.
To address that, I used a few techniques:

1. Chain-of-Reasoning (CoR) or Chain-of-Thought (CoT) sequenced prompting.
This is when you walk ChatGPT through the steps of the process, building up
details and definitions for the task. In this case, I asked ChatGPT to first produce
a plot summary, then a set of character sketches, then a set of detailed story points
in three acts. Only after all that did I ask it to write the story, act by act.

2. Rewrite and this time do a specific thing differently. You can have ChatGPT rewrite things
as many times as you like, and you can ask for specific changes each time. There is a limit
to this, I've found: ChatGPT can only keep in mind so many factors or requirements at a time,
and there is a limit to the number of words it can include in the conversation history (it's
a rolling window of the last 32,000 tokens, to be expanded to 100,000 tokens and beyond in the
future. A Token is roughly one syllable or segment of a word.)

3. "In the style of" and descriptive mood words for the writing style. This works well, and I could
have done this better by repeating more specifics about mood and style in each act-writing prompt.
Instead, I relied on the idea that I had included these in the initial prompt.

5. Long, specific prompts. I did copy-and-paste of the detailed story-point outlines of each act

   




