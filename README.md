# Neural-Network-Analysis-of-Heat-pipe-using-Hybrid-Nano-Fluids

## Objective of the project
* The main objective of this project is to analyze the performance of a
heat pipe by __Deep Convolution Neural Network (DCNN)__

* This method reduces the time and cost of analyzing any thermal device
by experimental analysis.

## INTRODUCTION – HEAT PIPE

A heat pipe is an ingeniously designed device engineered to efficiently transfer heat from a heat source to a heat sink. This transfer is achieved through the evaporation and condensation of a working fluid contained within a sealed system.

The structure of a heat pipe is divided into three distinct sections:

* __Evaporator Section__: This is the heating zone of the pipe, where the working fluid absorbs heat from the external source, causing it to evaporate.

* __Adiabatic Section__: Also known as the transport section, this part of the pipe is where the vaporized fluid, now carrying the absorbed heat, travels without significant loss or gain of heat.

* __Condenser Section__: In this cooling zone, the vapor releases its heat to the external sink and condenses back into a liquid form.

At its core, a heat pipe is essentially a sealed container, often tube-shaped, lined with a wicking material along its inner walls. This wicking material plays a crucial role in the effective functioning of the heat pipe by facilitating the return of the condensed fluid back to the evaporator section, thereby maintaining a continuous cycle of heat transfer

## Operating Principles of Heat Pipe:

A heat pipe stands out as a remarkably efficient yet simple mechanism capable of transferring substantial amounts of heat across considerable distances. What distinguishes this device is its ability to maintain a nearly constant temperature throughout the process, and it accomplishes this feat without the need for any external power input.

At the heart of a heat pipe's operation are two critical factors: the choice of fluid and the internal operating pressure. These elements are intricately linked to the heat pipe's operating temperature.

* __Selection of Fluid__: The working fluid inside a heat pipe is chosen based on its ability to undergo phase changes (evaporation and condensation) efficiently at the desired operating temperatures. The fluid must have suitable thermodynamic properties, ensuring it can evaporate when absorbing heat at the source and condense when releasing heat at the sink.

* __Operating Pressure__: The pressure within the heat pipe is precisely controlled and tailored to complement the characteristics of the chosen fluid. This pressure regulation is crucial as it directly influences the boiling and condensation points of the fluid, thereby dictating the efficiency and effectiveness of the heat transfer process.

By balancing these two aspects – the fluid type and the operating pressure – a heat pipe can function optimally within its intended temperature range, making it an invaluable tool in a myriad of thermal management applications.

## Typical Heat Pipe
<img src = https://github.com/sivkhiran/Images/blob/main/Heat%20Pipe.png width="500" />

## Details Of Our Heat pipe: 

<img src = https://github.com/sivkhiran/Images/blob/main/Heat%20Pipe%20Details.png width="800" />

## Working Fluids Used:

The first consideration in the identification of the working fluid is
the operating vapor temperature range.

The prime requirements are:

1. Compatibility with wick and wall materials

2. Good thermal stability

3. High latent heat (2.24 x 106 )

4. High thermal conductivity (0.68 W/mK )

5. Low liquid viscosities (2.28 x 10-4 )

6. Low vapour viscosities (1.28 Kg/m3 )

6. High surface tension (5.84 x 10-2 N/m)

Working Fluid used in this study are <img src = https://github.com/sivkhiran/Images/blob/main/Silver.png width ="150" /> &
<img src = https://github.com/sivkhiran/Images/blob/main/Al.png width ="150" />  hybrid Nano fluid. 

* __Ag - Silver__
* __Al2O3 - Aluminium Oxide__

## Nano Fluids Preparations: 

__Silver Nanoparticles (Ag)__ and its Preperation

Silver nano-particles are nano particles of silver of between __1 nm and 100 nm__ in
size.

Silver nanoparticles are prepared by the following methods

* Synthesis Methods

  * Wet Chemistry Method

  * Monosaccharide Reduction

  * __Sodium Citrate Reduction__

  * Reduction via Sodium Borohydride

  * Light – Mediated Growth

  * Silver Mirror Reaction

* Ion Implantation

* Biological Synthesis

__SODIUM CITRATE REDUCTION METHOD HAS BEEN ADOPTED
FOR THE PREPARATION OF SILVER NANOPARTICLE.__

Silver nanofluid solutions were prepared through the reduction of silver nitrate in an aqueous solution using citrate. __10 mg of AgNO₃__ was dissolved in 50 ml of double-distilled water, and this solution was brought to a boil. Subsequently, a 1% solution of sodium citrate was added dropwise over a period of 10 minutes. The solution was maintained at a boil for approximately 1 hour. The final product exhibited a greenish-yellow color and had an absorption maximum at 444 nm.

<img src = https://github.com/sivkhiran/Images/blob/main/Silver%20Nano%20Fluid.png width="300" />

__Aluminium Oxide (Alumina) Nanoparticles (Al₂O₃) and Its Preperation__

Aqueous solutions of aluminum nitrate and urea were prepared at the desired concentrations. These solutions were then mixed together and heated until the temperature reached 100°C. The reaction produced aluminum hydroxide, a gelatinous precipitate, which was subsequently filtered and heated to temperatures above 250°C.

The final product obtained was alumina nanoparticles in powder form.

The __Alumina__ nanoparticles were then mixed with distilled water and placed in an ultrasonic vibrator to form an alumina nanofluids.

<img src = https://github.com/sivkhiran/Images/blob/main/Alumina%20fluid.png width="300" />

## Experimental Analysis of Heat Pipe using Hybrid Nano Fluids 

A heat pipe charged with hybrid nanofluid was investigated for its performance by
varying parameters such as

* __Heat input__,

* __Fluid Ratio__,

* __Inclination__, and

* __Flow rate__.

The __heat inputs__ are varied from __40 to 100 W__, two __fluid ratios__ such as __80:20, and
60:40__, __the inclination angle of are 0°, 30°, and 45°__, and the __flow rates__ of __200 and 300
ml/min__. The two __nanofluids used in this investigation are silver nanofluid and
Al₂O₃__. They were mixed in the ratio of __60:40 and 80:20__ and prepared as hybrid
nanofluid and used in this investigation.

<img src = https://github.com/sivkhiran/Images/blob/main/0%20Degree%20.png width="600" />
<img src = https://github.com/sivkhiran/Images/blob/main/30%20Degree.png width="600" />
<img src = https://github.com/sivkhiran/Images/blob/main/45%20Degree.png width="600" />


## Deep Convolutional Neural Network 

__Deep Convolutional Neural Networks (DCNN)__ is the most admired deep
learning architecture. Researchers are using deep learning to solve many
problems since they are computationally efficient. It utilizes effective
convolution operation followed by pooling operation and performs sharing
of parameters.

__WHAT WE DO :__

We will be generating a DCNN MODEL using python language which will be
predicting the output data.

For this , the computer first require data which is already available to learn how the
process is being done and what is actually undergone to get such output .

The code contains two major parts

1. Training

2. Testing

__TRAINING:__

Training is basically the process, where we provide the available data to the
computer through which it learns the process.

__TESTING:__

Testing is the process where we just give the input values and the computer
predicts the output with the help of training it has undergone.

<img src = https://github.com/sivkhiran/Images/blob/main/Input%20Parameters.png width="600" />

After importing the training and test data, we decided to use the __Keras__ model and set the __epochs to 300__, as it demonstrated a lower percentage of error compared to others.

<img src = https://github.com/sivkhiran/Images/blob/main/Epoches%20300.png width="600" />
<img src = https://github.com/sivkhiran/Images/blob/main/Error%20%25.png width="600" />

## Conclusion

In this project work, an analysis of a heat pipe using a hybrid nanofluid was conducted using neural network techniques.

A __Deep Convolutional Neural Network (DCNN)__ was adopted for the analysis. The __experimental analysis clearly revealed that while the surface temperature of the heat pipe increases with an increase in input heat, it gradually decreases when moving away from the evaporator section__.

Using the experimental data, a DCNN model was developed for the heat pipe utilizing the hybrid nanofluid. This model has been validated against a set of experimental data.

The __DCNN model__, with a __precision of 0.991, accurately predicts the outlet temperature of the heat pipe__ using a hybrid nanofluid composed of Ag and Al₂O₃. The model takes into account different inclinations of the heat pipe, flow rates, fluid ratios, and heat inputs.

The temperatures predicted by the model have been used to estimate the efficiency of the heat pipe. A __coefficient of determination of 0.991 obtained in the DCNN model__ strongly indicates that the DCNN approach can be effectively extended to predict the performance of heat pipes.

The analysis shows that the efficiency of the heat pipe increases with a decrease in the water inlet temperature, while it decreases with an increase in heat input. Furthermore, it is __evident from the analysis that the water outlet temperature increases with an increase in fluid ratio and also rises with an increase in the water inlet temperature__.
