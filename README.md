# Ollama_DeepSeek-AWS_Cloudtrail

<img width="300" alt="Ollama_sec" src="https://github.com/user-attachments/assets/8eb85eb0-bfa3-4138-8265-97ede8194edf" />


# Let DeepSeek analyse your AWS CloudTrail Alerts

This repository contains a Python script that integrates with **Ollama's DeepSeek model** to analyze AWS CloudTrail logs and generate a comprehensive security summary. The script interacts with a locally running Ollama model, processes the CloudTrail logs  and outputs security findings, categorizing the identified issues based on severity (Critical, High, Medium, or Low).



## Features


- **Query Ollama Model**: Uses **Ollama's DeepSeek model** to generate insights from AWS CloudTrail logs.
- **Log Parsing & Analysis**: Automatically cleans and formats the user input before sending it to the model.
- **Security Summary Generation**: Provides a detailed security summary, identifying key findings like suspicious activities or potential vulnerabilities in the logs.
- **Customizable**: Easily customizable to work with any type of log file or input query.
- **BYOI**: Integrate with you SIEM or SOAR, just need to run Ollama with required model locally



## Requirements


- **Ollama**: Ensure Ollama and the **deepseek-r1:1.5b Model** is installed and running locally.
- **Ollama API Endpoint**: `http://localhost:11434/api/generate`
- Python 3.x and ofcourse the server/system capable enough to run the models.



## Code Logic Flow

![Ollama_AWS_CT](https://github.com/user-attachments/assets/86bd1d3b-4035-489a-a9a9-7a6a9c8d6a10)
