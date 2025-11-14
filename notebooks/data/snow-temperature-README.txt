Description:
	This folder contains data files from two Campbell Scientific CR10X dataloggers which were installed at two sites on Grand Mesa to measure snow temperature profiles as part of the SnowEx 2020 field campaign.
	
	"Grand Mesa 1" (GM1) measured snow surface temperature with an Apogee SI-111 thermal infrared radiometer mounted on a tripod at a height of about 127 cm above the snow surface. The radiometer pointed 45 degrees off-nadir at the snow surface just to the west of the tripod. Five Campbell Scientific temperature probes were mounted vertically along a wooden stake with zip ties, at depths of 5, 10, 15, 20, and 30 cm below the snow surface. (CR10X_GM1_final_storage_1.dat) 
	
	"Grand Mesa 2" (GM2) measured snow temperatures with five temperature probes mounted vertically on a wooden stake with zip ties at depths of 5, 10, 15, 20, and 30 cm below the snow surface. This location was just outside the fence perimeter of the Mesa West met station (northwest of the met station tower). Snow surface temperature is measured at the Mesa West station by its own set of thermal infrared radiometers, which can provide snow surface temperature adjacent to this vertical profile of snow temperature. The Mesa West station should also be able to provide similar snow temperatures below the surface with its own string of temperature sensors.

Date/times: 
	GM1: 2-5-2020 11:12 AM MST (UTCâˆ’07:00) - 2-12-2020 3:36 PM MST (UTCâˆ’07:00)
	GM2: 2-5-2020 12:35 PM MST (UTCâˆ’07:00) - 2-12-2020 2:36 PM MST (UTCâˆ’07:00)

Locations: 
	GM1 was located at Pit ID 2S10
	GM2 was located at the Mesa West met station 


File formats:
*.dat - comma-separated values from the Campbell Scientific CR10X Dataloggers
*.xlsx - MS Excel worksheet

Columns:
	GM1:
		'table', 'year', 'doy', 'time',
		'rad_avg', 'rad_max', 'rad_min', 'rad_std',
		'sb_avg', 'sb_max', 'sb_min', 'sb_std',
		'temp1_avg', 'temp1_max', 'temp1_min', 'temp1_std',
		'temp2_avg', 'temp2_max', 'temp2_min', 'temp2_std',
		'temp3_avg', 'temp3_max', 'temp3_min', 'temp3_std',
		'temp4_avg', 'temp4_max', 'temp4_min', 'temp4_std',
		'temp5_avg', 'temp5_max', 'temp5_min', 'temp5_std',
		'batt_a','batt_b'
	GM2:
		'table', 'year', 'doy', 'time',
		'temp1_avg', 'temp1_max', 'temp1_min', 'temp1_std',
		'temp2_avg', 'temp2_max', 'temp2_min', 'temp2_std',
		'temp3_avg', 'temp3_max', 'temp3_min', 'temp3_std',
		'temp4_avg', 'temp4_max', 'temp4_min', 'temp4_std',
		'temp5_avg', 'temp5_max', 'temp5_min', 'temp5_std',
		'batt_a','batt_b'



Resources:
	An example jupyter notebook for reading and plotting the data is available on github:
		https://github.com/spestana/snowex2020-snow-temp