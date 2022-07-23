Plume model data

% Flowline coordinates file
Contains polar stereographic coordinates of selected flowlines as plotted on Figure 2 
Column 1: xf [m]
Column 2: yf [m]
Abbreviations: 
IIS = Institute Ice Stream
RuIS = Rutford Ice Stream
SFG = Support Force Glacier
TIS = Talutis Ice Stream
MA = MacAyeal
ME = Mercer

% Ice shelf profiles for realistic flowlines listed in Table 3
Contains ice shelf profile data for the realistic flowlines (required as input to the plume model)
Column 1: horizontal distance from grounding line [m]
Column 2: ice base depth [m]

% Plume model outputs_idealised flowlines
Contains plume model outputs for idealised geometries
Column 1: distance along flowline (m)
Column 2: melt rate (m/yr)
Column 3: plume thickness (m)
Column 4: plume velocity (m/s)
Column 5: plume temperature (deg C)
Column 6: plume salinity (psu)
Column 11: heat exchange velocity (m/s)
Column 12: salt exchange velocity (m/s)
Column 15: elevation (negative) of ice shelf base (m)

Reference geometry
	IC0: IDEALISEDModelRun1.dat
	IC1: IDEALISEDModelRun3.dat
	IC2: IDEALISEDModelRun2.dat
	IC3: IDEALISEDModelRun4.dat
	IW0: IDEALISEDModelRun5.dat
	IW1: IDEALISEDModelRun7.dat
	IW2: IDEALISEDModelRun6.dat
	IW3: IDEALISEDModelRun8.dat

Deep geometry
	IC0: IDEALISEDModelRun21.dat
	IC2: IDEALISEDModelRun22.dat
	IC3: IDEALISEDModelRun100.dat
	IW0: IDEALISEDModelRun23.dat
	IW2: IDEALISEDModelRun24.dat
	IW3: IDEALISEDModelRun101.dat

Shallow geometry
	IC0: IDEALISEDModelRun17.dat
	IC2: IDEALISEDModelRun18.dat
	IC3: IDEALISEDModelRun98.dat
	IW0: IDEALISEDModelRun19.dat
	IW2: IDEALISEDModelRun20.dat
	IW3: IDEALISEDModelRun99.dat

Steep geometry
	IC0: IDEALISEDModelRun9.dat
	IC2: IDEALISEDModelRun10.dat
	IC3: IDEALISEDModelRun94.dat
	IW0: IDEALISEDModelRun11.dat
	IW2: IDEALISEDModelRun12.dat
	IW3: IDEALISEDModelRun95.dat

Flat geometry
	IC0: IDEALISEDModelRun13.dat
	IC2: IDEALISEDModelRun14.dat
	IC3: IDEALISEDModelRun96.dat
	IW0: IDEALISEDModelRun15.dat
	IW2: IDEALISEDModelRun16.dat
	IW3: IDEALISEDModelRun97.dat


% Plume model outputs_realistic flowlines
Plume model outputs for realistic geometries
Column 1: distance along flowline (m)
Column 2: melt rate (m/yr)
Column 3: plume thickness (m)
Column 4: plume velocity (m/s)
Column 5: plume temperature (deg C)
Column 6: plume salinity (psu)
Column 11: heat exchange velocity (m/s)
Column 12: salt exchange velocity (m/s)
Column 15: elevation (negative) of ice shelf base (m)

Larsen
	RC0: REALISTICModelRun113.dat
	RC1: REALISTICModelRun25.dat
	RC2: REALISTICModelRun26.dat
	RC3: REALISTICModelRun29.dat
	Along-plume path tidal currents: REALISTICModelRuns_Tide26

Talutis (TIS)
	RC0: REALISTICModelRun109.dat
	RC1: REALISTICModelRun2.dat
	RC2: REALISTICModelRun3.dat
	RC3: REALISTICModelRun6.dat
	Along-plume path tidal currents: REALISTICModelRuns_Tide3

Rutford (RuIS)
	RC0: REALISTICModelRun119.dat
	RC1: REALISTICModelRun92.dat
	RC2: REALISTICModelRun93.dat
	RC3: REALISTICModelRun107.dat
	Along-plume path tidal currents: REALISTICModelRuns_Tide93

Institute (IIS)
	RC0: REALISTICModelRun117.dat
	RC1: REALISTICModelRun60.dat
	RC2: REALISTICModelRun61.dat
	RC3: REALISTICModelRun64.dat
	Along-plume path tidal currents: REALISTICModelRuns_Tide61

Support Force (SFG)
	RC0: REALISTICModelRun118.dat
	RC1: REALISTICModelRun67.dat
	RC2: REALISTICModelRun68.dat
	RC3: REALISTICModelRun71.dat
	Along-plume path tidal currents: REALISTICModelRuns_Tide68

Amery
	RC0: REALISTICModelRun112.dat
	RC1: REALISTICModelRun18.dat
	RC2: REALISTICModelRun19.dat
	RC3: REALISTICModelRun22.dat
	Along-plume path tidal currents: REALISTICModelRuns_Tide19

MacAyeal (MA)
	RC0: REALISTICModelRun111.dat
	RC1: REALISTICModelRun11.dat
	RC2: REALISTICModelRun12.dat
	RC3: REALISTICModelRun15.dat
	Along-plume path tidal currents: REALISTICModelRuns_Tide12

Mercer (ME)
	RC0: REALISTICModelRun120.dat
	RC1: REALISTICModelRun101.dat
	RC2: REALISTICModelRun102.dat
	RC3: REALISTICModelRun108.dat
	Along-plume path tidal currents: REALISTICModelRuns_Tide102

Thwaites
	RW0: REALISTICModelRun114.dat
	RW1: REALISTICModelRun32.dat
	RW2: REALISTICModelRun33.dat
	RW3: REALISTICModelRun36.dat
	Along-plume path tidal currents: REALISTICModelRuns_Tide33

Dotson
	RW0: REALISTICModelRun115.dat
	RW1: REALISTICModelRun39.dat
	RW2: REALISTICModelRun40.dat
	RW3: REALISTICModelRun106.dat
	Along-plume path tidal currents: REALISTICModelRuns_Tide40

Abbot
	RW0: REALISTICModelRun110.dat
	RW1: REALISTICModelRun46.dat
	RW2: REALISTICModelRun47.dat
	RW3: REALISTICModelRun50.dat
	Along-plume path tidal currents: REALISTICModelRuns_Tide47

Cosgrove
	RW0: REALISTICModelRun116.dat
	RW1: REALISTICModelRun53.dat
	RW2: REALISTICModelRun54.dat
	RW3: REALISTICModelRun57.dat
	Along-plume path tidal currents: REALISTICModelRuns_Tide54












