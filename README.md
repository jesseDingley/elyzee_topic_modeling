# elyzee_topic_modeling

Worked on developing visualization tools for LumenAI's online clustering platform, in order to facilitate clustering interpretation. Applied classic natural language processing techniques to this problem, notably topic modeling. This work was done in the context of a summer internship (2020) at LumenAI.

### Main Notebooks:
  - `elyzeeTopicModeling.ipynb`: Perform topic modeling on twitter data from the 2017 french presidential campaign. The data concerns Twitter profiles active during the campaign (from November 2016 to May 2017), and their corresponding tweets and retweets, plus the retweet and mention networks related to these profiles. We define a community as a set of twitter users. 
  - `parameterTuningLDA.ipynb`: Fine-tune the LDA model used in the `elyzeeTopicModeling.ipynb` notebook.
  - `differentiateElyzeeComs(1).ipynb`: In the `elyzeeTopicModeling.ipynb` notebook, we see how to perform topic modeling on communities. But we didn't really dig further than that. In this notebook, we try and find out more precisely what each community talks about. If we calculate the topic distributions for each community and stop there, it's not actually that interesting. A lot of communities will share the same topics and it's hard to tell them apart. That is what this notebook is focused on: differentiating the communities.


This repository also contains an article (in html format) that gives an introduction to community interpretation with topic modeling.
