# OncoMut
Predicting Genetic Mutations as Primary or Metastasis Using Deep Learning

Business Problem
Modern gene sequencing technologies are getting cheaper year after year and also generate huge amounts of genetic data. With deep learning techniques, it is possible to build an early diagnosis and prognosis solution that can predict whether a particular genetic mutation is of type primary or metastasis. In this work, with the deep learning model, I will be predicting whether a given mutation is primary or metastasis. To accomplish this task novel deep learning algorithms and architecture will be applied on clinical research data. The open clinical research data called Memorial Sloan Kettering-Integrated Mutation Profiling of Actionable Cancer Targets (MSK-IMPACT) is used in this study to predict a given mutation is of type primary or metastasis using Deep Neural Network (DNN) Models. Multiple DNNs has been tried along with feature engineering. The model performance is compared to select the best performing model.

## Results

\begin{table}[]
\begin{tabular}{|r|r|l|r|}
\hline
\multicolumn{1}{|c|}{**No**} & \multicolumn{1}{c|}{**Model**} & \multicolumn{1}{c|}{**Description**}                                                           & \multicolumn{1}{c|}{**Validation Accuracy**} \\ \hline
1                            & DNN 1                          & DNN with numerical features only                                                               & 0.66639                                      \\ \hline
2                            & DNN 2                          & \begin{tabular}[c]{@{}l@{}}DNN with numerical features \\ and more layers\end{tabular}         & 0.57940                                      \\ \hline
3                            & DNN 3                          & \begin{tabular}[c]{@{}l@{}}DNN with numerical features \\ and categorical feature\end{tabular} & 0.73492                                      \\ \hline
\end{tabular}
\end{table}
