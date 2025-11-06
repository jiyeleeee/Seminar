# Seminar 
- The topic of the seminar is solving complex tasks using Large Language Models (LLMs).
- The goal of the this topic is to verify the utility of advanced prompt engineering techniques by applying them to tasks beyond the tasks used in the respective papers for illustration and evaluation.

# Topic: LLM for Literary Translation and Evaluation
## Evaluating the Effectiveness of LLMs in Translating Korean Poetry
This project is a seminar paper that evaluates the effectiveness of Large Language Models (LLMs) in translating Korean poetry into English while preserving its literary quality and cultural nuances.

- Primary Objective:
To assess the ability of LLMs to handle the stylistic and contextual integrity of Korean poetry.
To compare the translation quality at three different levels of context: Line-level, Stanza-level, and Whole poem-level to determine which provides the most effective translation.

- Methodology:
 - Dataset: A dataset of 50 modern Korean poems (written from 1910) was collected , totaling 570 lines, 118 stanzas, and 50 poems.
 - Model: The study utilized the Mistral 7B Instruct v0.2 model accessed via LM Studio.
 - Prompt Engineering: A specific prompt was designed to instruct the LLM to consider historical information, the author's life, poetic style, rhythm, rhyme, unity, and metaphors during translation.
 - Evaluation: The study deliberately avoided automatic metrics (like BLEU) and instead relied on human evaluation performed by the author, a native Korean speaker, to assess quality.
 - Error Analysis: An annotation task based on Multidimensional Quality Metrics (MQM) was used to categorize errors into six types: Mistranslation, Addition, Omission, Grammar, Inconsistent, and Awkwardness.

- Key Findings:
 - Overall Quality: Human evaluation showed a strong preference for translations generated at the Stanza-level and Whole poem-level over the Line-level.

 - Context is Crucial:
  - The Stanza-level translation was identified as the most effective, striking a balance between maintaining the poem's original structure and capturing its emotional and thematic depth.
  - In one example, a line-level translation failed to distinguish the contrast between "fire" and "flower," translating "a person" for both. The stanza-level translation correctly interpreted the context and used "One person" and "Another".
  - The stanza-level approach was also more successful at preserving poetic elements like rhyme schemes.

 - Error Patterns:
  - Mistranslation was the most frequent error across all three levels.
  - Awkwardness was most common at the line-level, demonstrating that translations lacked a natural flow without broader context.

- Limitations:
 - The evaluation of poetry is inherently subjective.
 - Human evaluation, while insightful, is exceptionally time-consuming.
 - Korean is a low-resource language in terms of high-quality training data for translation models compared to English, which can impact performance

