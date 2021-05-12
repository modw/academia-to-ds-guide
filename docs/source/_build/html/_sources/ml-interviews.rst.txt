Machine Learning Interviews
===========================

Interview Objective
--------------------
In a machine learning (ML) interview, the interviewer will most likely be interested 
in assessing how comfortable you are with solving a business problem using
machine learning as a tool. Note that the focus should be on utilizing the tool
to solve the problem, as opposed to focusing on the tool itself. 

Still, in a business setting every modeling decision needs to be deliberate,
justified, and usually motivated by a business metric such as revenue. For that
reason, you still need to have a broad understanding of the whole modeling
process, and a diverse set of problem types.

Core Concepts
-------------
Rather than going in depth, here's a list of core concepts you might tested on,
in an order you may see in a typical ML system design interview.

- Identifying a business problem as an ML problem.
- Choosing a type of ML solution optimal for the problem, such as:
  
  - Binary, multiclass, and multi-label classification.
  - Regression.
  - Ranking (i.e. Learning to Rank).
  - Recommendation.
- Proposing a set of candidate labels for training.
  
  - In real life, datasets usually don't come with labels. So you need to find 
    proxies in the data, and be mindful of label leakage when training.
- Recognizing statistical biases and/or challenges with your training data.
- Picking a specific ML model and justifying it.

  - Make sure to understand tradeoffs with other models.
  - Have an idea of basic hyper parameter tuning for your chosen model.
  - Understand your loss functions and justify your choices.
  - Pick a metric to optimize the model against. 
  
    - For example, if choosing a binary classification model, would you value
      precision over recall for your interview problem?
- Establishing both offline and online model testing processes.
  
  - Offline testing usually means train-test splits or cross-validation.
  - Online testing usually involves some form of metric tracking, hypothesis
    testing like AB testing, etc.
- Proposing ways to monitor and retrain the model if necessary.
- Proposing ways to identify model issues in production.
- Have an idea on how to improve or iterate on the model.
- Being able to explicitly state caveats and assumptions, and anticipate 
  possible issues that might surface with the model in production.

  - For example, if you're serving a recommendation model, how do you make
    sure the model won't converge to always recommending the same item?

Learning Resources
------------------
(in order of complexity)

- Brilliant_ has a nice and simple mathematical intro to ML.
- TheMLBook_ is an easy 100 page book with a fairly complete view of the topic.
- scikit-learn_'s user guide is fairly complete and includes plenty of examples
  for you to play with.
- Kaggle_ competitions are great to see what the best performing models are and
  how people train them.
- Udacity_ has plenty of Data Science and ML courses, including a Data Scientist
  nanodegree.
- Coursera_'s Machine Learning class by the famous Andrew Ng is very complete if
  you have the time.




.. _Brilliant: https://brilliant.org/courses/machine-learning/
.. _TheMLBook: http://themlbook.com/
.. _scikit-learn: https://scikit-learn.org/stable/user_guide.html
.. _Kaggle: https://www.kaggle.com/
.. _Udacity: https://www.udacity.com/
.. _Coursera: https://www.coursera.org/learn/machine-learning