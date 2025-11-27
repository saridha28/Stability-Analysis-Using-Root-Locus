# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:
<img width="814" height="836" alt="image" src="https://github.com/user-attachments/assets/d6c3cccd-65af-41f8-851d-4c4a9c6fd594" />
<img width="438" height="824" alt="image" src="https://github.com/user-attachments/assets/47073998-7221-4b2a-9d30-07636c55d0d7" />
<img width="423" height="705" alt="image" src="https://github.com/user-attachments/assets/8e98e72e-adc8-46c3-93a9-6103f3318481" />

## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
	From the value of K, analyse the stability.

## Program: 
```
num=[1]
den=[1 15 50 0]
sys=tf(num,den)
rlocus(sys)
[k poles]=rlocfind(sys)
```
## Output:
<img width="702" height="629" alt="image" src="https://github.com/user-attachments/assets/55096823-c15c-4b5a-be8f-cc2d7afc9e88" />

## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is 406.6838 
