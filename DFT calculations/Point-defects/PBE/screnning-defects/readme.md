---
# Guide to Kohn-Sham states
Examine in detail: [LSPD package](https://github.com/JosephPVera/Localized-States/tree/main).

Plot the Kohn-Sham states: [eigenplot.py](https://github.com/JosephPVera/DFT-calculations/blob/main/DFT/scripts/eigenplot.py).
![Alt text](https://github.com/JosephPVera/Investigation-cBN/blob/main/DFT%20calculations/Point-defects/PBE/screnning-defects/Guide/images/guide.png)

# Localized states
Get information within the gap with [localized.py](https://github.com/JosephPVera/DFT-calculations/blob/main/DFT/scripts/localized.py) (it can be extended) and plot the below figures with [locplot.py](https://github.com/JosephPVera/DFT-calculations/blob/main/DFT/scripts/locplot.py). The **locplot.py** script takes the sum of the 5 heaviest values (most contribution) ​​in each band per k-point (sum vs energies), it also can be change for check the total contribution (tot) for each band per k-point (tot vs energies).
1. Spin up
![Alt text](https://github.com/JosephPVera/Investigation-cBN/blob/main/DFT%20calculations/Point-defects/PBE/screnning-defects/Guide/images/Spin_up-kpoint_1.png)
2. Spind down
![Alt text](https://github.com/JosephPVera/Investigation-cBN/blob/main/DFT%20calculations/Point-defects/PBE/screnning-defects/Guide/images/Spin_down-kpoint_4.png)
