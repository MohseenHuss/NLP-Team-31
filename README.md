# NLP-Team-31
UCL NLP COMP0087

In this paper, we explore the effectiveness of football match outcome prediction using pre-match
analysis text articles. Specifically, we evaluate the performance of Random Forest models and neural
networks (namely LSTM and BERT models) on the task of predicting match outcomes for a selection of
past games from the EPL using match preview articles sourced from ”The Guardian” newspaper
(Beal et al., 2021). We compare this against two baseline predictors using only statistical features and
no text data; these are the Dixon & Coles method (Dixon and Coles, 1997) and the predictions based
on historical bookmakers’ betting odds for each game. 

We demonstrate that, of the text-based models 
that we experiment with, the Random Forest models generally outperform the neural network approaches.
We find that the accuracy of our bestperforming textual Random Forest model beats that
of the Dixon & Coles technique, but is not able to match the accuracy of the bookmakers’ predictions.
We then ensemble the text-based Random Forest with the predictions of the Dixon & Coles method
and the bookmakers, showing that this combination is beneficial to predictive accuracy. The accuracy
of the ensemble model is greater than that of any of the individual constituent predictors. Hence, we
exhibit that match-preview text data does indeed capture some information, not represented by statistical
features, which is of value in match result prediction.
