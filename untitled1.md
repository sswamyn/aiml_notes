## __Notes.md__ 


### Thoughts & ideas 
    History -> 1950's 
    How machine learns .. learning algorithms that learns patterns without explicit code. 
    Gen 0.1 --> Expert systems 
    AI --> No explicit code; No domain knowledge [example Google translation]
    Vocabulary - Attention, Reasoning, Comprehension, Perception, Learning, -- Cognitive computing
    Cognition - The mental action or process of acquiring knowledge and understanding through thought, experience, and the senses. [Oxford Dictionary]

    ML - Parametric learning vs. Non-parametric learning 
    [slide 7]
    Parametric
        Straight line y = A + Bx ... x is a matrices of dataset. A & B are the parameters. So this is a two-parameter model. Consider the LLM LaMMA 70 billion parameter
        Fundamentally it is a optimization (mathematically) problem (remember the transportation problems from high school?)
        Gradient descent (and its variants) is the most common optimization algorithm used in ML.
        .. cost function, loss function, etc. Then we have regularization, etc. Minima/Maxima, etc.
        Best example: Linear regression, Logistic regression, etc.
        Bascially, guess (predict) the output based on the input.
        
    Non-parametric 
        There is no model (equation)
        The model is learned as part of the machine learning process. The algorithm needs to figure out the model based on the training data. 

    Data classification 
        Structured data .. table, list of stock prices, monitoring data from IOT device, etc. 
        Unstructured data .. text, audio, video, images, etc.
        Semi-structured data .. there is structure, but the stucture contains Unstructured data. example: XML, JSON, etc.

        Labelled data .. data with output.
        Unlabelled data .. data without output. 

    Supervised learning 
    Unsupervised learning 
    Semi-supervised learning
    Reinforcement learning
    Transfer learning - Use a model that is generic and then using a data from a specific domain to train the model to make it specific to the domain. Transfer the learning from one domain to another.

    Self supervised learning (it is still narrow to the domain, not wide like human learning) 
        Self-learning
        Self-evolving
        Self-improving

    ML algorithm - Are usually not self-learning, self-evolving, self-improving. But reinforcement learning is an exception. Or Transfer learning.

> Human brain --> 100 billon neurtons; over 100 trillion synapses
The human brain consists of 100 billion neurons and over 100 trillion synaptic connections. There are more neurons in a single human brain than stars in the milky way! During development, neurons navigate this complex cellular environment and assemble into functional circuits.
[https://medicine.yale.edu/lab/colon_ramos/overview/#:~:text=The%20human%20brain%20consists%20of,and%20assemble%20into%20functional%20circuits.]

### Algorithms
#### Supervised - Regression 
    - Simple & multiple linear regression 

#### Supervised - Classification 
    - Naïve Bayes 
    - Support Vector Machines (SVM)
    - Logistic Regression

#### Supervised - Both 
    - Decision trees
    - Random forest 
    - Neural Networks 
    - K Nearest Neighbors (KNN)
    - ExtraTrees
    - Generalized Linear/Additive Models (GLM/GAM)

#### Unsupervised
    - K-Mean 
    - Principle Component Analysis (PCA)
    - Hidden Markov Models
    - Gaussian Mixture Model

INput x ==> w-x + b ; where w is the weight and b the bias ==> z ==> Activation [high/1 is above threshold; if below threshold low/0]

Input --> Hidden layer 1 --> Hidden layer 2 --> ... --> Output [is there a dog in the picture]
Decoder/Encoder 

Models - CRISP-DM model; [slide 16]

Model fitting 
    - High bias (underfit); ex: trying to fit a linear equation to a non-linear (curvy) pattern. 
    - High variance (overfit); Forcing a very complex equation to make it perfectly fit the data/pattern. The model cannot generalize and predict based on future data. 
    - We are aiming for a balance 


