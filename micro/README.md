In this folder, you will find the relationship annotation for the micro level. This annotation provides information on how the components that form an argument communicate within the argument itself. For example, it maps how premises, claims, and evidence relate to each other to construct an argument. The relations can be of two types: **support** and **attack**. Usually, a premise or evidence is used to either support or attack a certain claim.  

The columns in the CSV file are:  

- **utterance**: The utterance to which the mapped relation belongs to.  
- **source_component**: The identifier and type of the component that serves as the source of the relation.  
- **relation_type**: The description of the type of relation.  
- **target_component**: The target component to which this relation is mapped to.  

The dataset contains a total of **336 support-type relations** and **19 attack-type relations**.  
