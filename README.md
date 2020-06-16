# Tensorflow

TensorFlow is a free and open-source software library for dataflow and differentiable programming across a range of tasks. It is a symbolic math library, and is also used for machine learning applications such as neural networks.

# Docker Imgaes

### 1.  tensorflow-nlp

a. Pull docker images using:

**docker pull ankur310794/tensorflow:latest-nlp**

    - Images includes
        a. Base
            - tensorflow-2.2.0

        b. General Packages:
            - pandas, xlrd, tqdm, openpyxl ... etc

        c. Visualization Packages:
            - matplotlib, seaborn, bokeh, plotly ... etc

        d. General ML Packages:
            - scikit-learn, hyperas, lightgbm, xgboost,
             imbalanced-learn ... etc
        
        e.  NLP Packages:
            - transformers, sentencepiece, tensorflow_addons,
              nlp_preprocessing, model-x, tensorflow-hub, 
              lda2vec, gensim, textblob, wordcloud ... etc

b. Run docker images:

**nvidia-docker run --it -rm -p 8888:8888 -v <your_working_dir>:/tf ankur310794/tensorflow:latest-nlp**

Note: It automatically run jupyter notebook for you.

**To Be Continued...**
