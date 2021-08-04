### Quotes
>This paper shows the implementation of [[ModelingToolkit.jl]]. This is a library in #Julia. It seems to replace #Modelica. Moreover, it makes use of #MachineLearning techniques to reduce the computational burden. 
 
> To incorporate machine learning, we describe the continuous-time echo state network ([[CTESN]] ) architecture as an approximation transformation of time series data to a [[DAE]] component.

>  We showcase the [[CTESN]] as a methodology for translating a Room Air Conditioner model from a Functional Mock-up Unit ([[FMU]]) binary to an accelerated [[ModelingToolkit.jl ]]model.

Apparently at the time being, it is not possible to directly use [[FMU]]s
>   For each independent simulation, the fmpy package2 was used to run the FMU in ModelExchange with CVODE (Cohen, Hindmarsh, and Dubois 1996) or co-simulation with the FMUs exported solver. The resultant time series was then fitted to cubic splines. Integration with state-of-the-art solvers from DifferentialEqua- tions.jl (Rackauckas and Nie 2017) for simulating ModelExchange FMUs is planned in future releases.
### Notes
Of particular interest is the [[CTESN]] surrogate modeling technique which aims at catching the behavior of a phenomenon with respect of time (similarly to [[Manifold Learning]] [[DMD]]). To catch the dependence with respect to the other parameters it uses [[Radial basis functions]].




