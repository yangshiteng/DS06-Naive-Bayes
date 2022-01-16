# 1. Video Tutorial

## 1.1 https://www.youtube.com/watch?v=O2L2Uv9pdDA

- The intial guess can be any probability that we want, but a common guess is estimated from the training data
- For example, since 8 of the 12 messages are normal messages, our initial guess will be 0.67
- The initial guess that we observe a Normal messages is called a Prior Probability
![image](https://user-images.githubusercontent.com/60442877/149651275-9610c671-420f-49d5-8f5d-ae9d6a4fe7b3.png)
- The thing that makes Naive Bayes so naive is that it treats all word orders the same
![image](https://user-images.githubusercontent.com/60442877/149651771-5917e6d8-1943-4ac0-8b9b-c7186a61039d.png)
- Every language has grammar rules and common phrases, but naive bayes ignores all of that stuff. Instead, Naive Bayes treats language like it just a bag full of words and each message is random handful of them
- Naive Bayes ignores all the rules because keeping track of every single reasonable phrase in a language would be impossbile
