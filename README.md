# Can Temporal Graph Networks be useful for change point detection?
Use of Temporal Graph Networks to analyze node states shift during a shocking event in an online social network (OSN). 

The case study is a user migration from Steemit, the most well-known Blockchain-based OSN, to Hive, due to an hard-fork event.

This repository contains information, data and code behind the work: TBA

# Overview
We investigated the learning power of temporal graph learning during shocking events, an important task since they occur in temporal networked data and may lead to drastic variations in the characteristics of single nodes as well as their interactions.
As a case study, we analyzed a user migration due to a hard-fork event from Steemit, a novel blockchain-based online social network that allows the retrieval of validated high-resolution temporal information. 

To do so, first,  we model ``follow'' links between users and textual content produced by users as a dynamic attributed graph.
Then, we use future link prediction as a self-supervised task for a deep TGL model to obtain useful node representations from the dynamic graph.
The embeddings represent node states before, during, and after the shocking event.
Finally, we analyze how the node states change over time.

Our results show that TGL can be a useful tool to analyze and detect change points in networked temporal data.
Indeed, node states extracted by the model reflect i)  the habits changes of single users, ii) the diversity of the behavior of previously similar users during the event, and iii) the effect of the event on the interests of the users.
