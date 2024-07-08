## RAG Patterns

### Brief

Your client, a global construction company, is expanding to many new cities. They want to speed up the construction process by having quick access to the construction codes and regulatory information of the cities they are expanding their operations to. They have provided you a list of the relevant codes that they are concerned with.

Your task is to implement a RAG pattern using IBM's LLMs and cloud infrastructure. The models must output the correct information regarding the building policies and codes of a number of cities from around the world. Your aim is to produce the most accurate model which is concise but can also be very detailed and verbose depending on the client's needs.

Next, by using this model try to determine in which cities your client can begin construction projects first. Do different cities have different levels of regulation? Construct a business strategy based on the model's output and your construction failure data analysis from section 1 of the project. The strategy should be broad, but should mainly cover the order of cities to start projects in (e.g. start with LA, then NYC, then Singapore...) and it should also cover the best ways to avoid project failures in these new cities (based on the data from section 1).

Keep in mind, there are no right answers, but remember to justify your choices. Presentation information is in summary.

**Summary**

- Implement a RAG pattern to get information about building codes and regulations in cities around the world for your client (a construction company)
- Use your LLM and analysis from part 1 of the project (construction failure data) to determine a business strategy for your client about expansion order and maintaining successful projects
- _Create a presentation outlining your choices for part 1 of the project, your choices for the RAG pattern design and implementation, your choices for the business strategy/actionables. Aim for 6-8 mins._
- Remember to always justify your choices! Good luck :3

### This repo

- _pdfs_ folder contains all relevant pdfs for the RAG pattern (feel free to try and find more)
- _llm_testing.ipynb_ should be run first to ensure all your dependencies work properly
- _rag_pattern.ipynb_ must be completed and run to successfully implement a RAG pattern. If you would like an extra challenge, try to implement a RAG pattern without looking at this file
- Make sure to create a venv (instructions in _llm_testing.ipynb_)
- Make sure to install all dependencies (instructions in _llm_testing.ipynb_)

**DO NOT SHARE .env FILE ANYWHERE AND DO NOT UPLOAD IT TO GIT**
