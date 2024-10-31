# Plan

## Introduction

Co-writing a novel with a Language Learning Model (LLM) presents unique challenges, especially when dealing with limited context windows. LLMs like GPT-4 have a maximum token limit for input and output, which can make maintaining narrative consistency over a long-form piece like a novel challenging. To overcome this, a strategic approach is essential to ensure that each iteration stays on topic, avoids drift, and keeps key narratives and information consistent throughout the writing process.

## Strategy Overview

The core strategy involves meticulous planning, modular writing, efficient context management, and continuous consistency checks. By breaking the novel into manageable sections, creating detailed outlines and profiles, and establishing a robust feedback loop, you can guide the LLM to produce coherent and consistent content within its context window limitations.

## Detailed Plan

### 1. Pre-Planning Phase

#### A. Develop a Comprehensive Story Bible

Create a detailed document that serves as the reference point for the entire novel. This “Story Bible” should include:

- Plot Outline: A chapter-by-chapter breakdown of the story, including key events, plot twists, and the progression of the narrative arc.
- Character Profiles: In-depth descriptions of all major and minor characters, including their backgrounds, motivations, relationships, and development arcs.
- World Building: Detailed information about the settings, cultures, societies, rules of magic or technology (if applicable), and any other world-specific details.
- Themes and Motifs: Clearly defined themes, motifs, and symbols that will be woven throughout the novel.
- Tone and Style Guidelines: Establish the narrative voice, writing style, and tone to maintain consistency.

#### B. Define Key Narratives and Information

Identify and document:

- Core Conflicts: Central conflicts driving the story.
- Subplots: Secondary storylines that support or contrast the main plot.
- Foreshadowing Elements: Early hints or clues about future events.
- Character Relationships: Dynamics between characters that influence the plot.

### 2. Modular Writing Approach

#### A. Break the Novel into Sections

Divide the novel into small, manageable sections or chapters that can be developed independently within the LLM’s context window.

#### B. Define Objectives for Each Section

For every section:

- Summary of Previous Sections: A brief recap to provide necessary context.
- Specific Goals: What needs to happen in this section (e.g., character development, plot advancement).
- Key Details to Include: Essential information, dialogues, or events that must be incorporated.

### 3. Context Management Strategies

#### A. Use Summaries Effectively

At the beginning of each LLM interaction:

- Provide a concise summary of relevant previous content (within the token limit).
- Highlight key points, character states, and ongoing conflicts.

#### B. Implement Recurring Prompts

Develop a standard prompt structure that includes:

- Contextual Recap: Brief summary as above.
- Instruction: Clear guidance on what the LLM should produce.
- Style Reminders: Notes on tone, perspective, and style guidelines.

##### Example Prompt

[Summary of previous chapter/section]

In the next chapter, focus on [specific objectives]. Write in [narrative style], maintaining the tone of [emotional atmosphere]. Ensure that [key character] reacts to [event] in a way that reflects their [character trait].

C. Reference External Documents

Since the LLM cannot access external files, you can:

- Embed Key Details: Include essential information in the prompt as bullet points.
- Utilize Tokens Wisely: Prioritize the most critical context to include.

### 4. Consistency Checks and Revision

#### A. Regularly Review Outputs

After each iteration:

- Read Carefully: Check for consistency in plot, character behavior, and factual details.
- Annotate Changes: Note any discrepancies or new elements introduced.

#### B. Update the Story Bible

- Incorporate any agreed-upon changes or developments.
- Adjust character profiles or plot outlines as needed.

#### C. Provide Feedback to the LLM

- Clarify Mistakes: If the LLM introduces inconsistencies, address them in the next prompt.
- Reinforce Key Points: Remind the LLM of essential details that must remain consistent.

### 5. Establish a Feedback Loop

#### A. Collaborative Iterations

- Initial Draft: Let the LLM generate content based on the prompt.
- Editing: Manually edit the output for style, consistency, and coherence.
- Refinement: Feed the revised version back into the LLM for further development if necessary.

#### B. Version Control

- Save Iterations: Keep copies of each version to track changes.
- Document Decisions: Record why certain changes were made to inform future prompts.

### 6. Practical Implementation Steps

#### A. Setting Up the Environment

- Choose the Right Platform: Use an interface that allows for easy management of inputs and outputs.
- Token Management Tools: Utilize tools that count tokens to stay within limits.

#### B. Crafting Effective Prompts

- Be Specific: Clear and detailed instructions yield better results.
- Limit Open-Endedness: Guide the LLM to prevent it from drifting off-topic.

#### C. Example Interaction Workflow

1. Prepare the Prompt: Include the summary and instructions.
2. Generate Output: Let the LLM produce the content.
3. Review and Edit: Make necessary adjustments.
4. Update Documentation: Reflect any changes in the Story Bible.
5. Proceed to Next Section: Repeat the process.

## Conclusion

By implementing a structured approach that emphasizes detailed planning, modular writing, and proactive context management, you can effectively co-write a novel with an LLM despite its limited context window. Regular consistency checks and a robust feedback loop will ensure that the narrative remains cohesive, and key information stays consistent throughout the writing process. This strategy not only mitigates the challenges posed by the LLM’s limitations but also leverages its strengths to collaboratively create a compelling novel.
