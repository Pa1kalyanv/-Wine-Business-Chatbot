# Chatbot.ai
An assignment given by Artificial Intelligence (AI) internship
Computer Market Hub - AI Intern Assignment

Problem Statement:
You have a corpus about the information about a business who sells wines. They have their own website which customers often visit. But in this era of GenAI, people are looking for quick answers. They do not want to read anything, everybody wants quick answers. 
Taking this into concern, the business owners want to deploy a chatbot on their website. They want the chatbot to be able to answer the questions from this corpus and not use the other information. If the user asks anything that is not there in the corpus, it should just tell them to contact the business directly. A sample of question-answers is given here.

Now your task is to build this chatbot with the following functionalities:
It should have a minimalistic UI where users can chat with the chatbot. You are free to use your creativity for this. 
When asked a question, the chatbot should be able to answer from the corpus as described above. And for any out of corpus questions, it should tell the users to contact the business directly. 
You are free to use any GenAI tools, models (pretrained or fine-tuned), anything. You can even use ChatGPT, Gemini for your help, you are free to copy paste the code from anywhere. 
If you are using any LLMs for this, think about the cost perspective also, for example, track the token usage. Try to reduce them as much as possible.
Also, make sure to optimize the chatbot so it doesn’t have a very high latency. In real world use-case a maximum latency of 2-3 seconds is admissible but anything beyond that needs optimization. 
Make sure the chatbot maintains the conversation history, for example if in one question the user asks, “What is your best red wine?” and in the next questions the user asks, “Tell me more about it.” The chatbot must be able to interpret that it is referring to the previous questions, and mean “red wine” here. It shouldn’t be done just for the previous questions, but users can ask anything from the previous messages, so that chatbot should be able to answer all these queries well. 

