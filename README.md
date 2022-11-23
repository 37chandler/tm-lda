# Topic Modeling with LDA

This assignment asks you to do topic modeling via LDA. Follow the example in the code I walked
through in the video. Create a notebook of your own and choose a corpus to analyze. 

You're looking for a corpus with lots of text on a relatively limited number of themes. 
So congressional speeches are a good candidate, or a slice of reddit or wikipedia data. This
might be a good time to explore some of the 
[prepared data sets on Kaggle with the NLP tag](https://www.kaggle.com/datasets?sort=votes&tags=13204-NLP).  
You don't need to limit your number of topics to the number
of groups you have. 

Once you've chosen your corpus, do the following: 
1. Prepare the data for the `gensim` LDA modeling as in the example. 
1. Fit your model. Feel free to play around with the number of topics and 
the number of passes (and alpha, if you're feeling adventerous.) 
1. Estimate the most likely topic for your documents (or a subset of your
documents). 
1. The topic estimates come with probabilities. For each topic, show the 
single document that had the highest probability of being in that topic. 

