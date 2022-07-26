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


% Tidal current profiles for realistic flowlines listed in Table 3
As obtained from plume model output (input data from CATS2008 at 10 points along flowline interpolated onto plume model coordinates when running the plume model)


