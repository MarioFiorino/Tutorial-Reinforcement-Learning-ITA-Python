# Reinforcement-Learning-ITA-Python

In questa repository un corso in italiano sulle basi del Reinforcement Learning, sviluppato in Python, attraverso la piattaforma di Google Colab.

Non sono richieste conoscenze teoriche preliminari, se non nozioni pratiche di programmazione Python di base.

Tutti i contenuti sono rilasciati sotto licenza "MIT License". Vedi: https://choosealicense.com/licenses/ 

In caso di pubblicazioni o distribuzioni, si richiede solo che l'autore (Mario Fiorino) sia citato nelle note bibliografiche.

## Contenuti:

### Introduzione "sul campo" al Reinforcement Learning 
In questo notebook troverete un'introduzione al reinforcement learning "pratica"; cioè che si concentra sulla comprensione e sull'applicazione pratica degli algoritmi di reinforcement learning tramite un esempio molto semplice ed accessibile a tutti coloro che si avvicinano per la prima volta a tale disciplina.

>File : [Intro_sul_campo_RL_ita.ipynb](https://github.com/MarioFiorino/Tutorial-Reinforcement-Learning-ITA-Python/blob/main/Intro_sul%20campo_RL_ita.ipynb)


Nel notebook sottostante è descritto lo sviluppo di un agente che impara a giocare e vincere a Tris (Tic-Tac-Toe Game) tramite un algoritmo di Q-learning.

>File : [Tris_game_RL_ITA.ipynb](https://github.com/MarioFiorino/Tutorial-Reinforcement-Learning-ITA-Python/blob/main/Tris_game_RL_ITA.ipynb)


### Introduzione a OpenAI Gym
In questo notebook trovere un introduzione all'uso della libreria OpenAI Gym

>File : [Introduzione_OpenAI_Gym_ITA.ipynb](https://github.com/MarioFiorino/Tutorial-Reinforcement-Learning-ITA-Python/blob/main/Introduzione_OpenAI_Gym.ipynb)


### Reinforcement Learning - Fondamenti teorici
In questo notebook vengono presentate le basi teoriche del Reinforcement Learning, che affondano nella Programmazione Dinamica e nella Teoria del controllo ottimale. Sono inoltre presenti esempi applicativi

>File : [Programmazione_Dinamica_ITA.ipynb](https://github.com/MarioFiorino/Tutorial-Reinforcement-Learning-ITA-Python/blob/main/Programmazione_Dinamica_ITA.ipynb)

### Metodi Monte Carlo
In questa sezione sono presentati una serie di notebook che trattano i metodi Monte Carlo.

Parte 1 : Introduzione, Monte Carlo with Exploring Starts, On-policy first-visit Monte Carlo control
>File : [Metodi_Monte_Carlo_RL_ITA](https://github.com/MarioFiorino/Tutorial-Reinforcement-Learning-ITA-Python/blob/main/Metodi_Monte_Carlo_RL_ITA.ipynb)

Parte 2 : Incremental v.s Non-incremental, Importance sampling, Off-Policy Monte Carlo Control.
>File : [Off_policy_Monte_Carlo_ITA](https://github.com/MarioFiorino/Tutorial-Reinforcement-Learning-ITA-Python/blob/main/Off_policy_Monte_Carlo_ITA.ipynb)


### Temporal Difference Learning (TD Learning)
Il presente notebook offre un'introduzione al Temporal Difference Learning (TD Learning), in particolare sono trattati i seguenti argomenti: TD Prediction, Batch updating, one-step SARSA:On-policy TD Control, one-step Q-learning: Off-policy TD Control, Maximization Bias e Double Q-learning, n-step (o multi step) TD methods, n-step SARSA.

>File : [Temporal difference ITA.ipynb](https://github.com/MarioFiorino/Tutorial-Reinforcement-Learning-ITA-Python/blob/main/Temporal_difference_ITA.ipynb)

### Dyna
In questo notebook viene presentata un'introduzione ai metodi Dyna. Tali algoritmi cercano di migliorare l'efficienza dell'apprendimento del RL integrando tecniche di pianificazione (planning).

>File : [Dyna ITA.ipynb](https://github.com/MarioFiorino/Tutorial-Reinforcement-Learning-ITA-Python/blob/main/Dyna_ITA.ipynb)


###  Introduzione al Deep Learning

In questo notebook verrà fornita un'introduzione alle reti neurali, illustrandone la matematica di base del loro funzionamento.

>File : [Introduzione_al_Deep_Learning.ipynb](https://github.com/MarioFiorino/Tutorial-Reinforcement-Learning-ITA-Python/blob/main/Introduzione_al_Deep_Learning_ITA.ipynb)

Nel notebook sottostante sarrà fornita un'introduzione, nei suoi aspetti basilari, ad una delle librerie di Machine Learning più usate: TensorFlow version 2 (sviluppata da Google).

>File : [Introduzione_TensorFlow_v2_parte1_ITA.ipynb](https://github.com/MarioFiorino/Tutorial-Reinforcement-Learning-ITA-Python/blob/main/Introduzione_TensorFlow_v2_parte1_ITA.ipynb)

Nei notebook sottostanti verrà illustrato l'utilizzo di TensorFlow v2 per la costruzione e l'addestramento di reti neurali; successivamente la  stessa rete sarà implementata con la libreria Keras.

>File : [Introduzione_TensorFlow_v2_parte2_ITA.ipynb](https://github.com/MarioFiorino/Tutorial-Reinforcement-Learning-ITA-Python/blob/main/Introduzione_TensorFlow_v2_parte2_ITA.ipynb)

>File : [Introduzione_Keras_ITA.ipynb](https://github.com/MarioFiorino/Tutorial-Reinforcement-Learning-ITA-Python/blob/main/Introduzione_Keras_ITA.ipynb)

Nel notebook successivo un'introduzione a PyTorch.

>File : [Introduzione_PyTorch_ITA.ipynb](https://github.com/MarioFiorino/Tutorial-Reinforcement-Learning-ITA-Python/blob/main/Introduzione_PyTorch_ITA.ipynb)


###  Value Function Approximation

In questo notebook vedremo l'impiego di tecniche di approssimazione di funzioni per stimare la funzione-valore degli stati. 
In particolare, svilupperemo l'algorimo Semi-Gradient one step SARSA, con modellizzazione lineare, nel contesto Mountain Car (gymlibrary). Inoltre, daremo una prima occhiata alla tecnica di apprendimento per imitazione (Imitation Learning): come, osservando la strategia di un esperto, possiamo migliorare i risultati dell'apprendimento.


>File : [Value_Function_Approximation_parte1_RL_ITA](https://github.com/MarioFiorino/Tutorial-Reinforcement-Learning-ITA-Python/blob/main/Value_Function_Approximation_parte1_RL_ITA.ipynb)


Nel notebook successivo un'implementazione dell'algoritmo Deep Q Networks, contesto MsPacman(Atari), con Convolutional neural network(CNN); ed un introduzione al concetto di: Experience Replay.

>File : [Value_Function_Approximation_parte2_RL_ITA](https://github.com/MarioFiorino/Tutorial-Reinforcement-Learning-ITA-Python/blob/main/Value_Function_Approximation_parte2_RL_ITA.ipynb)


Nel notebook successivo, viene fornito un compendio sulle tecniche di Value Function Approximation, che si conclude con i suggerimenti di Sutton riguardo alla "Deadly Triad". Inoltre, viene mostrata la risoluzione del problema Cartpole (Gym) utilizzando prima un algoritmo DQN, poi Gradient Monte Carlo target control e infine un DQN con supporto imitation mode.

>File : [Value_Function_Approximation_Compendio](https://github.com/MarioFiorino/Tutorial-Reinforcement-Learning-ITA-Python/blob/main/Value_Function_Approximation_Compendio.ipynb)


###  Eligibility Traces 

Il notebook di seguito presenterà un'introduzione al meccanismo di eligibility trace.

>File : [Eligibility_Traces_ITA.](https://github.com/MarioFiorino/Tutorial-Reinforcement-Learning-ITA-Python/blob/main/Eligibility_Traces_ITA.ipynb)


### Policy Gradient

Nel notebook sottostante sono presentati i metodi policy-based, in particolare i metodi policy gradient. Questi metodi per funzionare necessitano di tre componenti: 1. una policy definita da parametri. 2. una funzione obiettivo da massimizzare. 3. un meotdo per aggiornare i parametri della policy. Troverete implementato una versione dell' algoritmo REINFORCE (noto anche come: Monte Carlo Policy Gradient) nel contesto CartPole(Gym).

>File : [Policy_Gradient_ITA](https://github.com/MarioFiorino/Tutorial-Reinforcement-Learning-ITA-Python/blob/main/Policy_Gradient__ITA.ipynb)


Nei prossimi due notebook troverete un'introduzione agli algoritmi Actor-Critic, un approfondimento sul dilemma "Varianza-Bias", una panoramica sul concetto di Advantage Function, e di Entropy Regularization. Infine, verrà presentata un'implementazione per risolvere l'ambiente Pendulum(Gym).

>File : [Actor_Critic_teoria_ITA](https://github.com/MarioFiorino/Tutorial-Reinforcement-Learning-ITA-Python/blob/main/Actor_Critic_teoria_ITA.ipynb)

>File : [Actor_Critic_code_teoria_ITA](https://github.com/MarioFiorino/Tutorial-Reinforcement-Learning-ITA-Python/blob/main/Actor_Critic_code_ITA.ipynb)

