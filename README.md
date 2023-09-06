# ChipStabber
BBI Fault Injection Tool

Body-Biasing Injection is a fault injection method used on WLCSP devices causing them to malfunction. My design was based on the ChipJabber created by Colin O'Flynn.

![image](https://github.com/IsaaccW/ChipStabber/assets/65687558/d72d3f91-7231-44e3-906c-fda8398af076)


![image](https://github.com/IsaaccW/ChipStabber/assets/65687558/7cf5a0ff-58e8-4549-b170-7dfa952b55f8)


![BBI-Image](https://github.com/IsaaccW/ChipStabber/assets/65687558/26d813ce-3b5c-4e8d-bcb2-c624176621dc)



It takes in a Pulse input, Power source ranging from 5-30V, and a ground. The received voltage is multiplied by 10x using a 1:10 ratio transformer, and precisly inserted into the DUT(Device under Test) by a probe as seen in the photos above. 
Attached below are examples of attacks that have been succesful using this device previously.
https://eprint.iacr.org/2020/1228.pdf
https://www.researchgate.net/publication/311490102_Body_Biasing_Injection_Attacks_in_Practice

