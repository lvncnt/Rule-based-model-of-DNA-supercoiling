# Rule-based-model-of-DNA-supercoiling

## Introduction

The two strands of DNA form a double helix structure, which can further twist with itself
and form supercoils. The sup erhelical density of a DNA region can be measured by u sing the
following equation:

          σ = ∆LK /LKrelaxed
          
where ∆LK is the difference between the linking numb er of a DNA (LK) and the linking
numb er of its relaxed form (LKrelaxed). Its degree is essential for many biological processes,
like protein-DNA interaction and transcription. Accordingly, a group of enzymes called topoisomerase is responsible for regulating the DNA supercoiling process. For example, there are three
topoisomerases identified in M.genitalium: DNA gyrase, topoisomerase I and topoisomerase IV.
Among them, topoisomerase I can relax negatively supercoiled DNA, whereas DNA gyrase and
topoisomerase IV can act on positively supercoiled DNA and induce negative supercoils.

## Rule-based modeling

The rule-based model of DNA supercoiling was constructed using the [`BioNetGen(BNGL) Language`][1]. 

## Simulation of the model
The model was then run for 500 s using the NFsim reaction simulator in [`Virtual Cell 5.4`][2].
 
![alt tag](https://raw.githubusercontent.com/lvncnt/Simulation-of-DNA-Supercoiling/master/Figure/plot1.png)

![alt tag](https://raw.githubusercontent.com/lvncnt/Simulation-of-DNA-Supercoiling/master/Figure/plot2.png)

[1]: http://bionetgen.org/index.php/Main_Page
[2]: http://vcell.org/
 
