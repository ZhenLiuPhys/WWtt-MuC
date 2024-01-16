This repository contains all the code used to generate the plots and figures in arXiv:2308.06323.
If you have any questions, please contact: Ishmam Mahbub (mahbu008@umn.edu)

Go to Code/Figure_generator/ and download all files in each folder with appropriate figure number,
then run the .nb file to reproduce the figures

Codes for electroweak PDF can be found in Code/Electroweak PDF/

Below are some general comments regarding how to generate each figures, more detailed comments can be found in their respective folders:

Fig. 2:  Each panel in the figure are generated seperately and combined manually. 
         For example, to generate partonic distribution for WW>tt, goto
         Code/Figure_generator/Figure2/WWtt/ and run Plot_partonic.nb. 
         Similarly, for other channels of interest, run Plot_partonic.nb in their 
         respective folder in Code/Figure_generator/Figure2/

Fig. 3: 3 TeV: Code/Figure_generator/Figure3/3TeV/Plot_Convolute 2.nb 
        10 TeV:  Code/Figure_generator/Figure3/10TeV/Plot_Convolute.nb 

Fig. 4: 3 TeV: Code/Figure_generator/Figure4/3TeV/Angle_dist 3tev.nb 
        10 TeV: Code/Figure_generator/Figure4/10TeV/Angle_dist 2.nb

Fig. 5: To generate the left panel first run
        Code/Figure_generator/Figure 5/Plot_partonic.nb and then run 
        Code/Figure_generator/Figure 5/Plot_partonic copy.nb
        To generate right panel first run
        Code/Figure_generator/Figure 5/angular/Plot_partonic_linear.nb and then 
        Code/Figure_generator/Figure 5/angular/Plot_partonic.nb

Fig. 6: 3 TeV: Code/Figure_generator/Figure 6/3TeV Plot/Overlay copy.nb
        10 TeV: Code/Figure_generator/Figure 6/Overlay copy.nb

Fig. 7: 

Fig. 8: 

Fig. 9: left panel: Code/Figure_generator/Figure 9/Plot_partonic.nb
        right panel: Code/Figure_generator/Figure 9/Angular/Plot_partonic.nb

Fig. 10: 3 TeV: Code/Figure_generator/Figure 10/3TeV/Overlay copy.nb
         10 TeV: Code/Figure_generator/Figure 10/10 TeV/Overlay copy.nb

Fig. 11: 3 TeV: Code/Figure_generator/Figure 11/3 TeV/chi-square.nb
         10 TeV: Code/Figure_generator/Figure 11/10 TeV/chi-square.nb

Fig. 12: 

Fig. 13: Code/Figure_generator/Figure 13/Overlay copy.nb





