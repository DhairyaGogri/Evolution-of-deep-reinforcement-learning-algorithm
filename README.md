this project focuses on the evaluation of deep reinforcement learning and its application through a case study in computer games.

The abstract provides an overview of the report's content. It discusses the application of Q-learning, a model-free reinforcement learning technique, to the iterated prisoner's dilemma (IPD) as a testbed for evaluating the development of optimal conditional cooperative strategies through trial-and-error experience. The report reviews the literature on Q-learning, generalization techniques, deep reinforcement learning, and multi-agent learning in social dilemmas. It describes a systematic investigation using Q-learning with enhancements like neural function approximation, experience replay, and hyperparameter tuning applied to the IPD within the Axelrod library framework. Multiple learning agents are trained against a diverse pool of opponents and then compete in tournaments. The experiments demonstrate the effectiveness of basic Q-learning in achieving cooperation against certain strategies but highlight the need for more sophisticated deep reinforcement learning methods to master complex multi-agent strategic scenarios.

The declaration section states that the dissertation is submitted in fulfillment of the requirements for the degree and acknowledges the author's own work while giving proper credit to others. It also includes permission for the university to provide copies of the dissertation and place it in a publicly available archive.

The acknowledgments express gratitude to the project supervisor, Dr. Jules Hedges, for guidance and support throughout the research project. The head of the Department of Computer and Information Sciences, Professor Clemens Cupke, is also acknowledged for providing access to computational resources. The open-source Axelrod Library community is thanked for their contributions to the research project.

The contents section provides an outline of the dissertation, indicating the different sections and their respective page numbers. The sections include an introduction and rationale, literature review, applying Q-learning to IPD, methodology, implementation, conclusion, improvements that can be done in the research, and references.

The introduction and rationale section explains the importance of investigating Q-learning in the IPD and presents the research goals and purposes. It highlights the prisoner's dilemma problem and its relevance to game theory.

The literature review section discusses various topics related to the research, such as Q-learning for repeated matrix games, generalization and exploration, memory and communication, deep reinforcement learning, evolution of cooperation, and multi-agent reinforcement learning.

The methodology section describes the Axelrod library architecture and provides an overview of the Q-learning algorithm implementation. It explains the strategy implementation, updating match attributes, storing metrics, plotting, statistical analysis functions, and the q_learning_tournament() function.

The implementation section details the application of Q-learning against different strategies and the experimentation with hyperparameters, function approximation, replay buffer, and separate target networks. It also includes the training of multiple agents and their participation in tournaments.

The conclusion section summarizes the findings and discusses potential improvements for future research. It mentions the application of Q-learning in solving complex computational problems in the real world and provides detailed explanations of real-life prisoner's dilemma situations.
