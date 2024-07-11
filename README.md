To use the project, download the pretrained LlaMa - 2 model from <a href = "https://llama.meta.com/llama-downloads"> Download here </a>, the website url is https://llama.meta.com/llama-downloads.
We have used a pretrained LlaMa - 2 model for our project. The goal of the project is to create a custom chatbot by fine tuning pretrained LLMs, which we've done here.
Download the model in GGUF format and save it in the same directory of the project.
We ran the model locally on our system by deploying it locally using flask and streamlit(separately, because they are 2 different ways to run the model locally).
Our system configuration:
- Processor: Intel Core i7 1260P
- GPU: Intel Iris Xe(integrated)
- RAM: 16GB
- Storage: 512GB SSD
The model takes around 2 to 3 minutes to generate the output in our system. The maximum context length is around 4096, so it can be altered accordingly.

The generated output is like:
![image](https://github.com/Thenameisafsal/Intel-Unnati-Project/assets/117061951/e51d93f3-7464-4d2e-9822-9610914af216)
Deploy the model locally using flask to run the model with html code, the model works as '/generate' invokes the model from the generate button in the webpage.

Tech stack used:
- Python
- HTML
- CSS
- Javascript
- Flask for deployment

  Note: We could not upload the model here as it is around 9GB in size, and the deployment was done locally to run the model for this reason.

