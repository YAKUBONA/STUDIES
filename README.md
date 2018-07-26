# Chapter One Summary on Hands_On_Machine_Learning_with_Scikit_Learn and TensorFlow (Aurélien	Géron)
### Machine Learning 
   Machine Learning is the science of programming computer so that it can learn from given data.
   
   *Note* Data supplied for computer to learn must be 
   - Sufficiently Enough so that the machine can be able to perform well on new data
   - Data used to train a machine should be representative of the case you want to generalize
   - Data should be of good quality ,so that the system should be able to detect the underlying pattern easly
   - Data feed to machine so that it can learn from it need to have relevant features and this is done using 
    **feature Engineering** which involves:-
    1. Feature Selection 
    2. Feature Extraction, combining existing features to produce a more useful one.
    3. Creating new features by gatherinhg new data that fit  the idea to be generalized 
                                    
### Why Machine learning ?
Machine learning emerged to address the long rule based human programming for complex problems like sparm filter as well as to address the 
the problem that are too complex for traditional approaches or have no known algorithm like speech recognition.

**TYPES OF MACHINE LEARNING**

Classified to the following categories:-

1.Based on Human Supervision we get the following 
 - Supervised Learning(you feed training data to the algorithm including the results i.e labels) typical task is **Classification and regression**
 - Unsupervised Learning (the opposite of Supervised learning i.e learning on unlabeled data ) typical task here is **anomaly detection**
 - Semi Supervised Learning (Combine Supervised and Unsupervised learning)
 - Reinforcement (Used to train robots by giving award and reward basing on set of actions)
2. Based on whether they can learn incrementally we get the following 
 - Batch Learning (System is incapable of learning incrementally)and
 - Online Learning (the reverse of batch learning train the system using minibatchs learning step is fast and cheap)
 
 **Note**Important parameter on online learning is *learning rate* i.e how fast it adapt to changing data but the challenge to this 
 is performance decline when bad data is fed to the system.
 
3. Based on how they generalize we have the following 
- Instance based Learning (system learn the example by heart and generalize new cases using similarity measues)
- Model based Learning (build a model of provided examples the n use model to make prediction)

**Challemges of Machine Learning**

The main challenge of machine learning is *bad data* as it has explained earier at top as well as *bad algorithm.*
On bad algorithm overffiting and underfitting arises ,where by <br/>
Overfitting ,the model perfform well on training data but it does not generalize well ,mostly of time this arise because the model 
is too complex relative to the amount of noiseness while underfitting occurs when the model is too simple to learn the underlying structure
of the data e.g Linear model is prone to underfit ,reality is just too complex that the model


