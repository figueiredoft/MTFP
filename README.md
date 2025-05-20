# Instances - Multiple Formation Team Problem (MTFP) and Multi-Skills Multiple Formation Team Problem (MMTFP)

Instances - Multiple Formation Team Problem (MTFP)

The instances are grouped into 9 classes according to the configurations of the following parameters: number of projects, number of available individuals, number of skills, time allocation fraction allowed.

Class 1 - Project = 2; Individuals = 25; Skills = 10; Time Allocation Fractions = {0; 1}.

Class 2 - Project = 5; Individuals = 50; Skills = 5; Time Allocation Fractions = {0; 1}.

Class 3 - Project = 10; Individuals = 100; Skills = 10 Time Allocation Fractions = {0; 1}.

Class 4 - Project = 2; Individuals = 25; Skills = 10 Time Allocation Fractions = {0; 0.5; 1}.

Class 5 - Project = 5; Individuals = 50; Skills = 5 Time Allocation Fractions = {0; 0.5; 1}.

Class 6 - Project = 10; Individuals = 25; Skills = 10 Time Allocation Fractions = {0; 0.5; 1}.

Class 7 - Project = 2; Individuals = 25; Skills = 10 Time Allocation Fractions = {0; 0.25; 0.5; 0.75; 1}.

Class 8 - Project = 5; Individuals = 50; Skills = 5 Time Allocation Fractions = {0; 0.25; 0.5; 0.75; 1}.

Class 9 - Project = 10; Individuals = 100; Skills = 10 Time Allocation Fractions = {0; 0.25; 0.5; 0.75; 1}.

Thus, there are 3 named folders with the number of vertices (individuals) of the graphs that representing the social networks: 25, 50 and 100 vertices. Example: a folder called 50Vertices has 3  synthetic graphs, 3 graphs using dataset social network Epinions and 3 graphs using dataset social network Bitcoin OCT. Totaling 9 graphs with 50 vertices. In addition, there are three folders: referring to classes 2, 5 and 8. Each folder class has 6 folders, one for each instance configuration. Each instance configuration consists of 4 files:

D.txt (set of individual's allowed time allocation fractions)

R.txt (project requirements matrix)

S.txt (sociometric matrix)

K.txt (skills / individuals)

In this way, as in each folder related to the number of vertices of the graphs there are 3 classes with 6 instances. Therefore, there are 18 different configurations to combine with 9 different graphs, for each type of cardinality of vertices (25, 50, 100), generating a total of 486 instances for MTFP.

Instances - Multi-Skills Multiple Formation Team Problem (MMTFP) 

