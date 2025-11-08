uplink: [Modulation](Modulation.md)

---
## Definition
- The phase of the carrier signal is shifted in accordance to the amplitude of the modulating signal.
- The phase angle of the carrier signal is being changed in accordance to the amplitude of the message signal.

## Diagram

![](../Pictures/Untitled-draw.jpg)

![](../Pictures/Pasted%20image%2020251108171943.png)

## How it works
1. **Carrier source signal/transport source signal** is produced for transmission/transport. 
2. The output is fed to 90deg stage shifter that changes sinwct to coswct.
3. **Frequency selective network/equilibrium or balance module** superimpose the message signal and carrier signal with m(t)sinwct = thetasinwmt x sinwct. The result of this module is, for the most cases, smooth transport signal.
4. The output of the 90deg stage shift and equilibrium module is fed to the a viper(adder) that adds both the inputs.
## Advantages and disadvantages
### Advantages
- The PM is fast.
- PM requires low sign power.
- PM has basic circuit plan.
### Disadvantages
- It's most susceptive to noise and interference.
- Complex hardware is required during FM to PM.