# langgraph tutorials
Series of tutorials:
Agenda:

Describe what are agents, what is langchain.

Build a REACT agent from scratch. React (Thought->Action->Observation) is one of the most popular agents. Building it from scratch will be a good intro into what are agents and how to work with them. Demo blast planning notebook

Describe what is langgraph, pros/cons over built-in function calling.Go over the different components of a graph (nodes, edges, conditional edges). Describe AgentState (graph memory)

Build a simple research assistant langgraph agent from scratch. This would be a good way to get familiar with langgraph module, tool calling implementation and AgentState. Demo weather research notebook 

Multiagent Langgraph
presenter: @Stepan Lavrinenko 

Describe Multi-agent langgraphs, applications, pros & cons

Build an essay writing tool with planner, generator, reflection, research planner and research critique nodes. Demonstrate how this essay writer can be used for intelligent search through Seequent help section. Demonstrate how this type of langgraph can be rewired as an error handling tool in llm apps. Demo essay research notebook.

Describe Query analysis tools, what these are, how can they help with vague or overly complex user queries. Pros&cons compared to REACT agent.

Build a ReWOO agent. This agent can be used for breaking a complex query into a plan of tasks and subtasks, then dynamically substituting the information from research on each task, until the initial query can be answered. This approach is more efficient than some other planner type langgraphs, but not too complex. Demo rewoo notebook with a user query “how to create a surface in leapfrog geo”

requirements:

1. Google ai studio (gemini) api key
https://aistudio.google.com/apikey

2. tavily search engine api key:
   https://tavily.com/


   Both are free


Collab links:
1_lang_building-react-agent-from-scratch (1).ipynb
https://colab.research.google.com/drive/1G9MXhOTkLrwpfPYTsx8MKKa4_u0CNTE7?usp=sharing

2_lang_langgraph-components (1).ipynb
https://colab.research.google.com/drive/1nxgAKlyi1get3NTfSCvERvTuXZv50oHJ?usp=sharing

3_lang_langgraph_essay_writer.ipynb
https://colab.research.google.com/drive/1iEFbZmYaRJEolrpN5DhN4RRxMA2FfmQV?usp=sharing

4_lang_rewoo_task_planner (2).ipynb
https://colab.research.google.com/drive/1SKA2e56_Uvs9imw_vLxyaPCseYVQvtwT?usp=sharing

