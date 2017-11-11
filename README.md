# Mobile Network Statistics

In my this project, I have worked using NS-3 Network Simulator. I have done 4 tasks in this project to see and understand the simulation in several conditions. In all the conditions I have calculated the Throughput separately too. Those conditions are discussed as below - 

1. **Point-to-Point Communication** : This is the most basic and starting simulation technique to see the transmission of data between two nodes; calculating the total number of packets received by the reciever in the network.

2. **Three-Node Network** : In this part, we have increased the number of nodes in the network by one. From this point we have also started visulaizing the simulations for getting a better understanding of what is going on inside the network.

3. **Increasing th distance** : We have increased the distance between the transmitters and the receivers and thus also increasing the distance between the transmitters. Also, I have analyzed why the number of packets decreased after increasing the number of nodes and with the increment in the distance, packet loss due to collisions has increased and also taht the sender is uanble to sense the packet transfer going on in the network, due to which number of packets decreased.

4. **RTS/CTS Enabling** : We have enabled RTS/CTS at this step, by changing the code in C++ file. By enabling RTS/CTS, the number of packets increase, because it reduces the frame collison among hidden stations. Once we enable the RTS/CTS, it stops sender from sending a data frame until it completes a RTS/CTS handshaking with the other station. 

5. **Throughput as a function of number of users** : In our last step, I tried to understand how the number of users affects the throughput of the network. Also, I ran the simulation for 3 different number of users, 10,20 and 30 users. 
