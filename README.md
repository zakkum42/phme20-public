# Remaining Useful Life Prediction for Experimental Filtration System: A Data Challenge

Maintenance costs of industrial systems often exceed the initial investment cost. Predictive maintenance, which analyzes the health of the system and suggests maintenance planning, is one of the strategies implemented to reduce maintenance costs. Health status and life estimation of the machinery are the most researched topics in this context. In this paper, we present our analysis for [Fifth European Conference of the Prognostics and Health Management Society 2020 Data Challenge](http://phmeurope.org/2020/data-challenge-2020), which introduces an experimental filtration system for different experiment setups, and asks for remaining useful life predictions. We compared random forest, gradient boosting, and Gaussian process regression algorithms to predict the useful life of the experimental system. With the help of a new fault-based piecewise linear RUL assignment strategy, our gradient boosting based solution has been ranked 3rd in the Data Challenge.

In this repository we provide Jupyter Notebooks for random forest, gradient boosting, and Gaussian process pipelines for the Data Challange. Your results may be different than our results in the paper because of the randomness used in algorithm initializations.

Citation:

@InProceedings{PHME20-GTU,
    author = {Kürşat İnce and Engin Sirkeci and Yakup Genç},
    title = {Remaining Useful Life Prediction for Experimental Filtration System: A Data Challenge},
    booktitle = {Proceedings of the European Conference of the PHM Society 2020},
    month = July,
    year = 2020,
    publisher = {PHM Society},
    editor = {Anibal Bregon & Kamal Medjaher},
    note = {Available at https://phmpapers.org/index.php/phme/article/view/1317}
}
