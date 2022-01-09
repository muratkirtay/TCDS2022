# TCDS2021
A repository for reproducing the results presented in TCDS submission: "Trust in robot-robot scaffolding."

> **Abstract:** The study of robot trust in humans and also other robots remains virtually unexplored regardless of its importance in the coming symbiotic society. To address this issue, we build upon the idea that robots should trust partners that tend to reduce their computational load and test the idea using an interactive visual recalling task. The robot in this task aims to process visual patterns presented as a grid to minimize the total computational burden of recall. In the first set of experiments, the robot is allowed to get help from online instructors with different guiding strategies: reliable, less-reliable, and random. The robot interacts with these instructors and decides which one it should trust based on the computational load it experiences during the experiment. In robot-robot interaction experiments, akin to the robot-online instructor case, a robot (Pepper) is asked to scaffold the learning of a less capable ‘infant’ robot (Nao) with or without being equipped with the cognitive abilities of theory of mind and task experience memory to assess the contribution of these cognitive abilities. Overall, the results show that robot trust based on computational/cognitive load within a sequential decision-making framework leads to effective partner selection and robot-robot scaffolding, which is enhanced by additional cognitive modules. Thus, using the computational load incurred by the cognitive processing of a robot may serve as an internal signal for assessing the trustworthiness of interaction partners.


### Experiments
![](https://github.com/muratkirtay/TCDS2021/blob/main/Figures/expFlow1.png)

---
## Folder and file descriptions
+ **Assets:** contains various assets to create the scene for visual processing, visual patterns to train associative memory, etc.  
+ **Source:** hosts python scripts to reproduce visualization and run the experiments. 
+ **Figures:** hosts the figures generated for the article. Additionally, we provide figures for direct trust results, which were not illustrated in the paper.
+ **Data:** contains experiment data for the results in .pkl format. Note that the .pkl files direct trust tranfer, trust-transfer-nao, also located in this folder.
+ **packages.txt:** a text file containing the python packages' version numbers for running the scripts. Due to the Naoqi framework, most packages should be compatible with Python 2.7.
+ **Videos:** hosts the experiment videos: i) robot-online instructor interactions ii) robot-robot interaction, and iii) trust transfer nao, i.e., single robot experiment. 