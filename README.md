# Readme
Data for the ISTTT24 paper title
" Incorporating Personalization and Bounded Rationality into Stochastic Transit Assignment Model"
for more information 
contact: yujiang@dtu.dk 
# Folder Instructions
1. It contains two folders 
   1. 1993: four-node network 
   2. SiouxFall: Sioux fall network with bus lines
   3. a excel for computing the example in the appendix E. 
# Data files
1. BusCost.csv
   1. LineId: Bus line ID
   2. Cost: travel time of each bus line segment
2. BusFre.csv
   1. LineId: Bus line ID
   2. Fre: frequency of the line, No. buses/hour
   3. Cap: Capacity of the bus, No. pas/bus
3. BusStop.csv
   1. LineId: Bus line ID
   2. Stop: stop node number
4. Graph.csv
   1. No. of nodes in the network
5. OD.csv
   1. ID: OD pair ID
   2. Origin: origin node
   3. Dest：destination node
   4. Demand: Demand level
   5. Strategy: which strategy is used 
      > the strategy index is slightly different from the ones used in the paper. In the code, Strategy S0 refers to the SUE, which it is Strategy S4 in the paper.
   6. TT,WT,CT: Weighting parameters for the three PT attributes
   7. B_TT,B_WT,W_CT: these parameters are not used in the ISTTT24 paper. 
   8. ThetaWin, ThetaLoss: the theta value for the scale parameters associated with the relative advantages and disadvantages. 
   9. Sat_TT, Sat_WT, Sat_CT: Satisfactory bounds for the three PT attributes
