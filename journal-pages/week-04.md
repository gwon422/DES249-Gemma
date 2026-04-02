---
layout: default
---

# Week 04 - Experement 4: Artificial Intelligence

[← Back to Home](../index.md)

## Studio Exercise
This week we explored local and cloud-based AI workflows with activities to introduce practical and ethical dimensions of working with AI, building on the ideas about data representation from previous experiments.  

### Activity 1: Local AI with Ollama

We started by downloading and conversing with Ollama for a couple minutes, see video below.

<video controls src="../assets/week-04/Ollama.mp4" width="500" length="500" title="Ollama Interaction"></video>
*Ollama Interaction*

It was slower than ChatGPT, but slightly faster or equal to Copilot. It also felt more humanised and explained the code in more depth than copilot. However, their were more errors in the code, but that could be from not having the data to work with.


### Activity 2: Cloud AI with NotebookLM
For the second activity we opened NotebookLMLinks to an external site and created a new notebook.

1. Build your notebook: 
We added sources that represent our experimentation so far on the course, mixing our own works with other sources. I added my Making Journal URL, GitHub Pages Repository and a few practitioner websites that resonated with me.

![Notebook 1](<../assets/week-04/Notebook 1.png>)
![Notebook 2](<../assets/week-04/Notebook 2.png>)
*NotebookLMLinks*

2. Frame your research:
Before generating artefacts, we add a short document to shape the AI's focus. We wrote three explainations about: the experiment we found most interesting and why, a theme or idea we keep coming back to, and something we're curious about but haven't had a chance to explore yet.

3. Explore in the chat:
We used the chat to ask questions about our sources with prompts like:

"If my sources were documentation for a design project, what would the final outcome be?"
"What do my sources suggest I care about?"
"Identify a provocation hidden in my sources"
"What would someone who disagrees with the ideas in my sources argue?"
"Which of my sources are you drawing on for that, and which are you ignoring?"

<video controls src="../assets/week-04/Exploration.mp4" width="500" length="500" title="Exploring with NotebookLM"></video>  
*Exploring with NotebookLM*

4. Generate the Audio Overview:
The Audio Overview option make it seem more philosophical. Hearing my work discussed feel different from reading the chat responses in many ways, it makes it sound more professional and more like a topic of discussion.

## Independent Study: AI-Assisted Data Exploration
### Intructions

Choose a public dataset about life in Aotearoa New Zealand and use cloud-based AI tools to explore, interpret, and represent the data. The challenge is to go beyond a single prompt, working through sustained dialogue with the AI, directing its decisions, and critically evaluating its outputs.

Step 1: Find a Dataset

I browsed through the open data catalogue at catalogue.data.govt.nz and found a dataset that might be interesing, Tunnel Restrictions, then moved on to step 2 after downloading. 

Step 2: Understand the Data

I upload the CSV into Copilot and had a conversation about it. I ask the AI to explain what is in the dataset: what the columns mean, what the values represent, how much data there is, and what is missing or incomplete. This is what it gave me, see video below.

<video controls src="../assets/week-04/CSV Upload.mp4" width="500" length="500" title="CSV Upload and Conversation with Copilot"></video>  
*CSV Upload and Conversation with Copilot*  
OpenAI. (2026). Copilot (Mar 20 version) [Large language model]. https://m365.cloud.microsoft/chat

### Considerations:

Working with the tunnel dataset prompted me to think about how seemingly dry or administrative data can still contain meaningful stories. At first glance, the dataset feels functional and constrained, focused on identifiers and measurements rather than human experience. However, spending time examining it made me more aware of how infrastructure data reflects decisions about movement, safety, and space. The lengths of tunnels and their placement on different roads hint at the challenges of navigating terrain and urban density, even if those stories are not explicitly stated.

As a designer, I found it interesting how limited the dataset is, and how those limitations shape what can be visualised. The absence of descriptive or temporal information forced me to think creatively about how to represent what is available rather than what I wished the data contained. This made me reflect on how much design work involves working within constraints and acknowledging gaps rather than trying to resolve them. The dataset’s lack of context encouraged me to focus on form, scale, and comparison rather than narrative detail.

Overall, this process reinforced my interest in translating technical datasets into more interpretable and expressive visuals. It highlighted the importance of questioning where data comes from, what it leaves out, and how design choices can either flatten or reveal underlying structures. Even a small dataset like this can become useful and engaging when approached as a starting point for exploration rather than a complete story.

Step 3: Design Multiple Representations

I ask the AI to produce multiple data visualisations with a few edits in the I wanted outputted. It gave me a diagram, a p5.js code, and a potential physical/analogue visualiasion

<video controls src="../assets/week-04/Visualisations.mp4" width="500" length="500" title="Visualisations"></video>
*Data visualisation Ideas*  
OpenAI. (2026). Copilot (Mar 20 version) [Large language model]. https://m365.cloud.microsoft/chat

Step 4: Critically Evaluate

Across the representations produced, the AI tended to default to familiar, conventional data‑visualisation forms, particularly a horizontal bar chart with neutral colour choices and a clear, descriptive title. This approach prioritised legibility, comparison, and clarity, making it easy to interpret the dataset even for viewers unfamiliar with it. While this was effective for understanding scale differences in tunnel lengths, it leaned toward an analytical rather than expressive visual language.

To move beyond this default, I had to redirect the AI toward more conceptual and exploratory representations, such as abstract shape‑based visuals and physical installations. These required reframing the task away from efficiency and accuracy and toward interpretation and experience. Prompting the AI to consider physical materials, spatial metaphors, or non‑numeric mappings helped shift the output from informational to speculative, which better aligned with my interests in design and creative practice.

The AI also appeared to assume that the primary audience was a general or technical viewer seeking quick understanding of the data. This assumption influenced choices such as labelled axes, proportional scaling, and a focus on tunnel length as the main variable. While reasonable, this overlooked the potential for ambiguity, emotional engagement, or critical questioning. It also assumed that tunnel length was the most meaningful feature, rather than considering absence, invisibility, or infrastructure impact as equally important narratives.

The representation I found most interesting was the physical visualisation concept, particularly the use of scaled objects or hanging elements to represent tunnel length. This approach moved away from screen‑based legibility and encouraged embodied comparison, making infrastructure feel present rather than abstract. It revealed the imbalance in tunnel scales more intuitively and aligned better with my interest in translating hidden systems into tangible experiences.

If I were building this project without AI, I would likely begin with sketching and material exploration rather than charts, allowing the data to suggest form through experimentation. I would spend more time questioning which variables deserve to be visualised and deliberately designing for ambiguity rather than clarity. While the AI was helpful for rapidly generating understandable representations, working without it might allow for slower, more intuitive decisions rooted in personal interpretation rather than established visualisation conventions.

Reading Data Feminism by D’Ignazio and Klein alongside Kirikowhai Mikaere’s talk on Māori data sovereignty prompted me to reconsider my assumptions about data and visualisation. Both emphasise that data is never neutral and that design choices can reinforce existing power structures. This made me more aware of how default visual forms such as clean charts or efficiency driven representations can obscure lived experience, context, and care. In my own work, I noticed how easily I prioritised legibility and comparison over questioning whose perspectives were centred and what kinds of knowledge were being left out.

Mikaere’s discussion of data as a taonga particularly reinforced the idea that data carries cultural responsibility as well as informational value. Even though the dataset I worked with was infrastructural rather than personal or Indigenous, the framework of Māori data sovereignty encouraged me to think about ownership, absence, and purpose in all datasets. Together, these readings pushed me toward exploring slower, more embodied and interpretive forms of visualisation, and to treat data visualisation not just as a technical exercise, but as an ethical and relational design practice.

## AI Usage Statement

As stated above, use of AI for vibe coding and help with coding issues, M365 Copilot. Use of other local and cloud AIs' for studio tasks including NotebookLM and Ollama.
