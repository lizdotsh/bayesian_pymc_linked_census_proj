# bayesian_pymc_linked_census_proj

Background: 

This was made as a final project for my Bayesian econometrics class. If any of the comments or anything are confusing, it's probably because of the target audience (my professor). 

The jupyter notebook has a more detailed description, but TL;DR: 

- It uses a _full count_ census dataset, so I wouldn't try to run it. It took a long, long time to run on A100s. I did include a way (and the raw dataset) to run it using just a sample percentage of the dataset, though. 
- A lot of the processing is done in duckdb, and I did not include the database in the repo. the full size of is gigantic, far too big for github. I included the cut down samples after processing, though. 
- Jupyter could not load a large number of the figures without crashing, so they are all in the /figures directory. the chains of the models are also in .nc form in the /chains directory. I normally dislike jupyter because it is messy like this, but was a project requirement for me. 
- All analysis is extremely rushed as this was a final project and most of the time was spent dealing with technical issues in actually sampling the data, and the analysis is sub-par at best.
