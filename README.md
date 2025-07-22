\documentclass{article}
\usepackage[margin=1in]{geometry}
\usepackage{hyperref}
\usepackage{graphicx}
\usepackage{amsmath}
\usepackage{xcolor}

\title{\textbf{Predicting Heart Disease using Machine Learning}}
\author{Adit S.}
\date{}

\begin{document}

\maketitle

\section*{Overview}
This project aims to develop a machine learning model capable of predicting whether a patient has heart disease based on a set of medical attributes. The entire workflow is implemented using Python and various data science libraries.

\section*{Problem Statement}
Cardiovascular diseases are a leading cause of death globally. Early diagnosis is crucial for timely intervention. This project utilizes patient data to train and evaluate models that can assist in the early prediction of heart disease.

\section*{Technologies Used}
\begin{itemize}
    \item Python
    \item Pandas, NumPy
    \item Matplotlib, Seaborn
    \item Scikit-learn
\end{itemize}

\section*{Dataset}
The dataset used in this project is the \textbf{Cleveland Heart Disease dataset}, publicly available from the UCI Machine Learning Repository. It contains 14 attributes including:
\begin{itemize}
    \item Age, Sex, Chest Pain Type (cp), Resting Blood Pressure (trestbps)
    \item Cholesterol Level (chol), Fasting Blood Sugar (fbs), Resting ECG (restecg)
    \item Maximum Heart Rate Achieved (thalach), Exercise-Induced Angina (exang)
    \item ST Depression (oldpeak), Slope of Peak Exercise (slope)
    \item Number of Major Vessels Colored by Fluoroscopy (ca), Thalassemia (thal)
    \item Target (presence or absence of heart disease)
\end{itemize}

\section*{Approach}
\begin{enumerate}
    \item \textbf{Data Cleaning and Preprocessing:} Handling missing values, encoding categorical features, and feature scaling.
    \item \textbf{Exploratory Data Analysis (EDA):} Visualizing feature distributions and correlations.
    \item \textbf{Model Training:} Evaluated multiple classifiers including:
    \begin{itemize}
        \item Logistic Regression
        \item K-Nearest Neighbors
        \item Random Forest
        \item Support Vector Machines
    \end{itemize}
    \item \textbf{Evaluation Metrics:} Accuracy, Precision, Recall, F1-Score, ROC-AUC.
\end{enumerate}

\section*{Results}
The best-performing model was \textbf{Random Forest Classifier}, achieving:
\begin{itemize}
    \item Accuracy: \texttt{92\%}
    \item ROC-AUC Score: \texttt{0.94}
\end{itemize}

\section*{How to Run}
\begin{enumerate}
    \item Clone the repository.
    \item Install dependencies: \texttt{pip install -r requirements.txt}
    \item Run the Jupyter Notebook: \texttt{jupyter notebook HeartDiseasePrediction.ipynb}
\end{enumerate}

\section*{Open in Google Colab}
\noindent
\href{https://colab.research.google.com/}{\includegraphics[scale=0.7]{https://colab.research.google.com/assets/colab-badge.svg}}

\section*{Project Structure}
\begin{itemize}
    \item \texttt{HeartDiseasePrediction.ipynb} -- Main Jupyter Notebook
    \item \texttt{README.tex} -- Project description (LaTeX)
    \item \texttt{requirements.txt} -- Python dependencies
    \item \texttt{images/} -- Visuals and charts
\end{itemize}

\section*{License}
This project is released under the \textbf{MIT License}.

\section*{Author}
\textbf{Adit S.} \\
\href{https://github.com/your-github}{GitHub Profile}

\end{document}
