# RYSe

Online search engines for children are known to filter retrieved resources based on page complexity, and offer specialized functionality meant to address gaps in search literacy according to a user's age or grade. However, not every searcher grouped by these identifiers displays the same level of text comprehension, or requires the same aid with search. Furthermore, these search engines typically rely on direct feedback to ascertain these identifiers. This reliance on self identification may cause users to accidentally misrepresent themselves. We therefore seek to recognize users from skill based signals rather than utilizing age or grade identifiers, as skill dictates appropriate aid and resources. Therefore, in this thesis we propose a strategy that automatically recognizes users on the fly by analyzing search behavior found in search sessions. In particular, our efforts focus on recognizing the stereotypical 8 to 12 year old searcher, who we posit exhibits skills defined by developmental stages that have a strong impact on language development (Piaget's concrete operational stage) and search literacy (digital competency's first level). This strategy analyzes user-generated text extracted from queries and patterns of search interactions in order to infer features that are leveraged by a random forest classifier in order to determine whether or not a user is a part of this specific segment of searchers. 

Contained in this repository is code for my thesis, "Why don't you act your age?  Recognizing the stereotypical 8-12 year old searcher by their search behavior." This code is presented primarily in Jupyter Notebooks, with links for any data set 
larger than 20 megabytes found in their respective folders. 

The folders contain code which must be run in the following order:

1. Data
2. FeatureExtraction
3. Experiments
4. Results

env.txt Contains the Anaconda environment that these experiments were run on.
