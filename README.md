
<h2> Synthetic data  </h2>

- Synthetic data refers to artificially generated information that mimics the characteristics of real-world data, but is created through computational methods rather than being collected from actual events or sources.
- This simulated data is valuable for testing, training, and - research purposes, as it overcomes privacy concerns, data scarcity, and logistical constraints associated with using genuine data.

<b>Advantages of Synthetic Data </b><br/>
- Enhanced Privacy and Security: Eliminates risk of personal data breaches.<br/>
- Regulatory Simplification: Ensures compliance with stringent data protection laws.<br/>
- Accelerated Development and Unrestricted Access: Enables rapid prototyping, testing, and access when real data is unavailable.<br/>
- Data Enrichment and Scenario Customization : Augments datasets and creates specific or rare scenarios for improved machine learning.<br/>
- Controlled Testing: Allows simulation of specific conditions for experimentation.<br/>
- Improved Model Robustness: Leads to better-performing and generalizing AI models.<br/>
- Cost Efficiency: Offers a cost-effective alternative to real-world data collection.<br/>
<br/>
Point to consider: Synthetic data should be used carefully, as it may not always capture real-world complexities.<br/>

<h2> LLMs used in this project</h2> 
<b>OpenAI</b><br/>
- OpenAI provides the API for accessing powerful language models like GPT-3.5 Turbo.<br/>
- In this application, the OpenAI API is used to generate responses based on the data retrieved from Elasticsearch, for the query passed from the chatbot.<br/>

<h2> Framework used in this project </h2>
- Langchain <br/>

<h2> How to run This Application</h2> 
**Note:** OpenAI immediately revokes the API key once it detects that the key has been exposed publicly. Therefore, do not expose your API key.<br/>
<br/>
Generate your OpenAI API key here: [Click Here](https://platform.openai.com/account/api-keys)

1. Clone this git repository from command prompt<br/>
git clone https://github.com/padmapria/llm-synthetic-data-gen-for-structured-data.git    
cd llm-synthetic-data-gen-for-structured-data  

2. Create a `.env` file inside the 'app' folder and store the key as follows:     
OPENAI_API_KEY=YOUR_API_KEY_HERE<br/>

```python   
from dotenv import load_dotenv   
load_dotenv()   
openai_api_key = os.getenv("OPENAI_API_KEY")
```

3. Run the jupyter notebook to generate synthetic data <br/>

