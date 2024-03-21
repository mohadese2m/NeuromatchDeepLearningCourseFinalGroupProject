**A Performance Analysis on Question and Answering Chatbots**

Today, many organizations and companies use question answering chatbots to quickly answer the
frequently asked questions by clients. Considering the importance of speed in receiving answers and
ease of work for clients, we wanted to know if we could design a chatbot that would automatically answer
the new questions of the clients by using knowledge base and additional documents. We are looking to
find out how the additional information and documents will affect the performance of our deep artificial
intelligence model. We hypothesized that additional information about question is crucial for the model to
achieve the best accuracy because it provides the necessary information and background for the model
to understand the questions and generate accurate answers. We finetuned our both Bert and GPT-2
models on squad2 dataset. For the Bert we use additional knowledge while in gpt-2 we don&#39;t utilize it. As
a result of asking numerous questions and evaluating the model, the Bert model that received additional
information related to the question text was more accurate. We conclude that the simpler model with
richer additional information can outperform the more advanced model but without information related to
the question context. which shows the importance of data and additional information. Due to the
limitations of Colab Gpu, we were not able to use the model with more parameters and epochs. Instead of
using our entire data set, we only used 1000 samples. If it was possible to use more data, the accuracy
would increase. According to what was observed, it is suggested to consider the use of additional
knowledge for future works in the field of question answering chatbots.

This is a group project for the Neuromatch Academy Deep Learning Course.
