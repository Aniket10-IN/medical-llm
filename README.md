# Health Report diagnosis (LLM)
## Utilising Large Language Models in health care.

The purpose of this application is to test LLM-generated interpretations of medical observations. 
The explanations are generated fully automatically by a large language model. 
This application should be used for experimental purposes only. 
It does not provide support for real world cases and does not replace advice from medical professionals.

### Architecture

* Streamlit caching loaded Synthea synthetic medical data
* Prompting with LangChain PromptTemplate
* LLM served by Clarifai backend

### Run the app

```
pip install -r requirements.txt
streamlit run Main.py
```
