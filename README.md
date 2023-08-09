# ChipStabber
BBI Fault Injection Tool

Body-Biasing Injection is a fault injection method used on WLCSP devices causing them to malfunction. My design was based on the ChipJabber created by Colin O'Flynn.

![image](https://github.com/IsaaccW/ChipStabber/assets/65687558/d72d3f91-7231-44e3-906c-fda8398af076)


![image](https://github.com/IsaaccW/ChipStabber/assets/65687558/7cf5a0ff-58e8-4549-b170-7dfa952b55f8)

It takes in a Pulse input, Power source ranging from 5-30V, and a ground pin which makes it able to take in a voltage, multiply it by 10x using a 1:10 ratio transformer, and precisly insert the fault using the trigger from pulse input placing a large voltage on the probe which is then inserted on the backside of the device under test(DUT). 
