# Health Report diagnosis (LLM)
## Utilising Large Language Models in health care.

The purpose of this application is to test LLM-generated interpretations of medical observations. 
The explanations are generated fully automatically by a large language model. 
This application should be used for experimental purposes only. 
It does not provide support for real world cases and does not replace advice from medical professionals.

### Architecture

![app-architecture-image](https://github.com/bsenst/streamlit-llm/assets/8211411/d5bc2063-b5fb-43ad-9220-8c5d16954024)

* Streamlit caching loaded Synthea synthetic medical data
* Prompting with LangChain PromptTemplate
* LLM served by Clarifai backend

### Run the app

```
pip install -r requirements.txt
streamlit run Main.py
```
