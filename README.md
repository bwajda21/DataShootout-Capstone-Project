# DataShootout-Capstone-Project
libname AgePop 'C:\Users\student\Documents\Applied anaytics\Libraries\AgePop';
proc sql;
update AgePop.Disease_cases
set age = '45-64'
where age = '45-54';
quit;
proc sql;
update AgePop.Disease_cases
set age = '45-64'
where age = '55-64';
quit;
proc sql;
update AgePop.Disease_cases
set age = '65-84'
where age = '65-74';
quit;
proc sql;
update AgePop.Disease_cases
set age = '65-84'
where age = '75-84';
quit;

#For Census Data
proc sql;
update AgePop.Census_population
set age_group = '0-17'
where age_group = '00_to_04_years';
quit;
proc sql;
update AgePop.Census_population
set age_group = '0-17'
where age_group = '05_to_09_years';
quit;
proc sql;
update AgePop.Census_population
set age_group = '0-17'
where age_group = '10_to_14_years';
Quit;
proc sql;
update AgePop.Census_population
set age_group = '0-17'
where age_group = '14_to_17_years';
Quit;
proc sql;
update AgePop.Census_population
set age_group = '45-64'
where age_group = '45_to_49_years';
Quit;
proc sql;
update AgePop.Census_population
set age_group = '45-64'
where age_group = '50_to_54_years';
Quit;
proc sql;
update AgePop.Census_population
set age_group = '45-64'
where age_group = '55_to_59_years';
Quit;
proc sql;
update AgePop.Census_population
set age_group = '45-64'
where age_group = '60_to_64_years';
Quit;
proc sql;
update AgePop.Census_population
set age_group = '65-84'
where age_group = '65_to_69_years';
Quit;
proc sql;
update AgePop.Census_population
set age_group = '65-84'
where age_group = '70_to_74_years';
Quit;
proc sql;
update AgePop.Census_population
set age_group = '65-84'
where age_group = '75_to_79_years';
Quit;
proc sql;
update AgePop.Census_population
set age_group = '65-84'
where age_group = '80_to_84_years';
Quit;
proc sql;
update AgePop.Census_population
set age_group = '18-24'
where age_group = '18_to_24_years';
quit;
proc sql;
update AgePop.Census_population
set age_group = '25-44'
where age_group = '25_to_29_years';
quit;
proc sql;
update AgePop.Census_population
set age_group = '25-44'
where age_group = '30_to_34_years';
quit;
proc sql;
update AgePop.Census_population
set age_group = '25-44'
where age_group = '35_to_39_years';
quit;
proc sql;
update AgePop.Census_population
set age_group = '25-44'
where age_group = '40_to_44_years';
quit;
proc sql;
update AgePop.Census_population
set age_group = '85+'
where age_group = '85_years_and_over';
quit;

#For Projected Pop
proc sql;
update AgePop.Projected_population
set age_group = '0-17'
where age_group = '00 to 04 years';
Quit;
proc sql;
update AgePop.Projected_population
set age_group = '0-17'
where age_group = '05 to 13 years';
Quit;
proc sql;
update AgePop.Projected_population
set age_group = '0-17'
where age_group = '14 to 17 years';
Quit;





