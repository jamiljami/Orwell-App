# Research

Initial Questions:
The grand question is how can we predict people's political identity (including for MPs) so that we can contrast the MP with the voter. We are looking for an abstract representation of one's identity using the data we have.

What _sources_ of data are there for understanding a voter?
* Online (social media, advertisement cookies, search history)
* Personal (demographics, personal information like age, sex, address)
* Direct (questionnaires and election results e.g. 538)
* MP (parliamentary voting patterns e.g. TheyWorkForYou)

Which _frameworks_ could we use? (this includes model and data)
* Classification/Regression algorithms (perhaps with clustering or NLP)
* Dimensional reduction model (PCA/SVD/RBM/Netflix)
* Recommender system
* 538 Model (DW-NOMINATE)
* Psycho-analytical model (e.g Cambridge Analytica)

Source:
https://theconversation.com/how-cambridge-analyticas-facebook-targeting-model-really-worked-according-to-the-person-who-built-it-94078

Each framework has its development complexity, time, accuracy/bias and drawbacks. (create design table later)

## Framework Evaluation

The _Recommender System_ (RS) with _Direct_ and _MP_ data seems the easiest model to implement, with no privacy issues.
