NEURON mod files for the I-A and I-K currents from the paper:
Zhou FM, Hablitz JJ.
Layer I neurons of the rat neocortex. II. Voltage-dependent outward currents.
J Neurophysiol 1996 76:668-82.

Running the kinetics.hoc simulation file will show 
the activation and inactivation steady-states, the time constants, 
and a family of curves generated modeling the same protocols 
used for Figs.6A-10A of the paper.

Note that although m^4*h (for I-A) was used in the 
paper to model the specific time course of current traces 
obtained from one cell (Fig.15), m*h was found to give better
results for the experimental protocol shown in Fig.6A
and better agreement with fig.5C.  
The voltage dependence for the time constants was
based on the values reported in the paper to 
to fit specific current traces (Fig.11 and Fig.15),
which are plotted with markers here.
No inactivation is implemented for K-DR.
Kinetics of Layer I neurons were reported not to be significantly 
different from Layer II/III pyramidal neurons.

Under unix systems:
to compile the mod files use the command 
nrnivmodl 
and run the simulation hoc file with the command 
nrngui kinetics.hoc

Under Windows using NEURON 5.1:
to compile the mod files use the "mknrndll" command.
A double click on the simulation file
kinetics.hoc 
will open the simulation window.

Questions on the model parameters should be directed to the 
authors.

Questions on how to use this model with NEURON
should be directed to michele@pa.ibf.cnr.it
