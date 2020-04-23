# LMCO - EVERGLADES Robot Behavior Analytics

EVERGLADES is a synchronous, turn-based 1v1 strategy game originally developed by Lockheed Martin for reinforcement learning in real life combat situations. The primary objective of the game is to capture the opponent’s base, and the secondary objective is capturing nodes and eliminating enemy opponents.

Our primary objective as the Robot Behavior Analytics team was to evaluate game telemetry data from the EVERGLADES games in an attempt to collect advanced analytics to help determine what behaviors most leads to wins. This was done by running games played by various AI agents developed by our team. To generate new and relevant metrics, our original analysis of normal game play will be scrutinized and used to create AI scripts to test hypotheses. These scripts provided additional data sets to be analyzed. Analyzing the new data set along with our original data set provided insight into our original hypotheses thus allowing us to form new conclusions. These iterations of hypothesis testing identify and
characterize behaviors that lead to wins. The historical data was then stored in our database so that datasets could be generated for analysis.

Afterwards, the data sets were analyzed using classification algorithms to analyze the data. These models combined with proper tuning and analyses were designed to help identify metrics that lead to wins.
Lastly the group was tasked with the design of a Real Time Analytic Engine that could predict the winner of a game given a game state and provides a brief summary of what was occurring during the game. The Real Time Analytic Engine was developed and designed to be compatible with the EVERGLADES match play back system in the future.
