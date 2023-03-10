# Speech Recognition with Emotion and Summarization API

## Overview
* Detected aggressive behavior from speech and summarize the content to provide unbiased information 
* Implemented Voice-to-text transformation API and utilized retrieved text to conduct emotion detection 
* Automated summarization of the speech content, suitable for meeting scenario or journalism industry

## Tools
Python, Tensorflow, BERT, flask, HTML

![alt text](./Speech_recog/API_overview.png)

## Steps to Reproduce
1. Install the dependency
```
pip install requirements.txt
```
2. Clone the repository
```
git clone https://github.com/ChenFengTsai/Speech_Emotion_Summary_API.git
```
3. Run the application
```
python wsgi.py
```
## Demo
### Speech Recognition with Emotion Detection
![alt text](./Speech_recog/Speech_recognition.jpg)

### Speech Recognition with Content Summarization
![alt text](./Speech_recog/summarization_example.jpg)

## Potential Future Usage
* More real-world context for generativeAI to learn (scientists concern that good learning written material is going to be depleted in near future, how we can solve this problem?)
* Distinguish good learning material like tutorial video by analyzing the summary of material
* Detect aggresive behavior in specific institution like school, medical institution, bank
* Social justice to learn opinion from minority group if they do not have written material only speech or talk
* Determine whether the speech is biased (racist, non pc) or not with more dataset
* Replace reporter/journalist since sometimes they give biased information or comment
