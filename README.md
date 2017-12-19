# MAIN REPO FOR 266 CLASS project
#
# Richard Hitchens, Tom Seddon

Data files
----------
Raw conference call transcripts stored in four directories:
T1
T2
T3
T4


Main Analysis Notebooks
-----------------------
Analysis and results in report and presentation generated from the following
notebooks:

Fullset_NLP_1209_TS_CHanges.ipynb       -- cleaning, parsing, baseline
Building_models_1215_TS.ipynb           -- building LDA models
Evaluating_coherence_1215_TS.ipynb      -- topic coherence analysis
Evaluating_topics_1215_TS.ipynb         -- other topic evaluation and display
Evaluating_similarities_1215_TS.ipynb   -- q and a similarity analysis
Chart_portfolios_1216_TS.ipynb          -- charting portfolio returns


Model files
-----------
Saved models are stored under the directory saved_models.

Within each model directory, there is:
corpus.txt          -- corpus used to build that model
dictionary.txt      -- dictionary used to build that model
full_model          -- gensim LDA model
hell_sims.txt       -- hellinger similarities of q and a given that model
lda_logfile.log     -- log of the training
model_runtime.txt   -- when model was run
model_spec.txt      -- dictionary containing model specification


Other
-----
Remaining files are preliminary EDA and other work done that we did not remove
in case we needed to return to it at some point.
