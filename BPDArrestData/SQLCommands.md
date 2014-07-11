These are the SQL Commands I used to create my Table in SQL Workbench.

-- BPDArrests
-- Baltimore Police Department Arrest Records
 CREATE TABLE bpdarrests (
 
-- ID Number of Arrest
ArrestID int(8),

-- Age of Indiviual Arrested 
AgeofArrestee int(3),

-- Sex of Individual Arrested
Sex varchar(2),

-- Race of Individual Arrested 
Race varchar(1),

-- Date of the Arrest 
ArrestDate varchar(10),

-- Time of the Arrest 
ArrestTime varchar(5),
-- Location of the Arrest 
ArrestLocation varchar(42),

-- Offense of the Incident Reported 
IncidentOffense varchar(42),

-- Location of the Incident 
IncidentLocation varchar(42),

-- Charge Code 
Charge varchar(6),

-- Description of Charge 
ChargeDescription varchar(140),

-- District 
District varchar(42),

-- Post 
Post integer(3),

-- Neighborhood 
Neighborhood varchar(42),

-- Location Latitude/Longitude 
LatLongLocation float(42),
);

After 2 hours of trouble shooting with Rachel (who was unfamiliar with this specific workbench interface.)

I figured out that integers don't need character limits
some of my fields didn't need to be integers. 

I also had to help Aurea on the search for data.