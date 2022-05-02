# Multiuser Quantum Cryptography Protocol for Secure Communications
Implementation based on literature review of:<br>
*
<a href="https://www.nature.com/articles/s41598-019-56706-2" target="_blank">
Quantum Random Number Generator
</a><br>
*
<a href="https://www.nature.com/articles/srep45928#Sec5" target="_blank" >
Quantum Key Distribution Protocol for Multiuser Applications
</a>

Run this to install all dependencies: 
```
python -m pip install -r requirements.txt
```
## Description of Notebooks:
* mqkd_keygen.ipynb - Simple simulation of the Key Distribution Circuit
* mqkd_keygen_on_real_hardware.ipynb - Key Distribution Circuit on a real hardware
* mqkd_keygen_with_err_correction.ipynb - Key Distribution with Noise related Error Correction
* mqkd_keygen_with_eavesdropper.ipynb - Key Distribution with Eavesdropper Detection
* qkd_random_gen.ipynb - Quantum Random Number Generator Circuit