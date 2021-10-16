BL40A2010 Introduction to IoT-Based Systems
Assignment 4, 16.10.2021
Author:ZhouZiAo
(1) Draw a graph with star topology with five nodes (one in the center $A$, four in the edges $B$-$E$). If the topology is directed as a many-to-one topology, write the structure of awareness of the system, considering that nodes $B$-$E$ acquire and process data about a supporting reality $T$, while $A$ can only receive data from it. Remember the notation $Xy$ means the image of $X$ by $Y$.


![40eb84bfeb99f01af3ea185e5dd2185](https://user-images.githubusercontent.com/91326706/137590831-f4d78a0f-d657-4f4f-baba-6595dd77d084.png)
![9878a66744b36f867e3dae97454be62](https://user-images.githubusercontent.com/91326706/137590867-33cf8490-a35c-4d40-bb08-8911d3638b22.png)
structure of awareness:
The image of $T$ done by $B, C, D, E$ are denoted $Tb, Tc, Td, Te$, and Node $A$ has four
neighbors $B, C ,D, E$ so that it knows the information about them, so the refexive system $Ω$ is
$Ω = Ta + Tab + Tac + Tad + Tae = Ta(1 + b + c + d + e)$. The structure of awareness is $ω = a(1 + b+ c + d + e)$



(2) Assume that graph illustrate a scenario of four sensor nodes that also (pre-)process data and one aggregator node as follows. Nodes $B$ and $C$ monitor temperature and wind speed at Airport station in Lappeenranta, respectively. Nodes $D$ and $E$ monitor temperature and wind speed at Lepola station in Lappeenranta, respectively. Nodes $B$ and $D$ send a binary message to $A$ indicating if during that period the temperature was more than $25$ degrees ("1" means above, "0" means below or equal to). Likewise nodes $C$ and $E$ send a binary message to $A$ indicating if during that period the wind speed was more than $5$ m/s ("1" means above, "0" means below or equal to). Download and plot the data from FMI with 1 hour resolution during July, 2018. Using this data, plot the binary signals sent from the nodes $B$-$E$ to the aggregator $A$.

![0677172c2f4d2bfa4bd269f71548796](https://user-images.githubusercontent.com/91326706/137590949-48f41456-29e6-4dac-bb99-232b7511d888.png)
![0e3214807afa59ac074f83d6bc4a2a3](https://user-images.githubusercontent.com/91326706/137590981-1920e5bb-38e9-464d-9c34-565876c49f8e.png)
![15ca6eb575d06ae6081f8766fd08c64](https://user-images.githubusercontent.com/91326706/137591215-5c7893b5-c934-46fd-9471-fc5b15c175b8.png)
![5d6a01fb66861612ebbc2031f529b18](https://user-images.githubusercontent.com/91326706/137591309-ea6f181d-b272-40aa-8009-806a4f5b8d9a.png)
![4b4ed380242f11816cc9a24199ba584](https://user-images.githubusercontent.com/91326706/137591324-aa9cb6a3-d893-4b08-8a98-8def9476e001.png)
![39f5dce783367a7934fa1419a6aa4b9](https://user-images.githubusercontent.com/91326706/137591335-0d27828a-541c-4dc5-ace2-2c38cce76176.png)
![image](https://user-images.githubusercontent.com/91326706/137591353-e8b4ba72-86ba-40c7-8cbe-46397a20b873.png)




(3) Node $A$ needs to identify risky situations in Lappeenranta when the temperature is above $25$ degrees and the wind is above $5$ m/s based on the sensors' signals. If a risky situation is identified at node $A$ as binary number "1" while normal situations as "0". How would you solve this problem? Plot the output signal from node $A$ and discuss its relation to the input signals from $B$-$E$.

![94c1bf8b489b58c0bd4d4417f1e9d41](https://user-images.githubusercontent.com/91326706/137591132-f51eb95f-11d9-4e69-af1e-baf28b410079.png)
![2ffd8e75804ed9f78eee18ab1c64297](https://user-images.githubusercontent.com/91326706/137591159-8532c7aa-c61f-47dc-ae24-5ed08bea5d3d.png)
