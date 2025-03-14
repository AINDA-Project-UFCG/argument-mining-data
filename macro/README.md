In this folder, you can find the annotation for macro-level relations, which means that this process maps the relationships among different utterances in the debate. By doing so, we can better understand the behavior of each debater and how they communicate with others through agreement, disagreement, argumentation, and so on.

The columns of the CSV file are:

- **utterance**: The utterance where the interaction started.  
- **source_debater**: The debater who initiated the interaction.  
- **source_utterance**: The utterance number where this interaction started.  
- **relation_type**: The type of relation present in this interaction.  
- **target_utterance**: The utterance number to which the interaction was addressed.  
- **target_debater**: The debater to whom the interaction was directed.  

The number of occurrences for each label is:

- **Questioning**: 130  
- **Agreeing**: 65  
- **Disagreeing**: 26  
- **Partially Agreeing**: 15  
- **Discussion**: 5  
