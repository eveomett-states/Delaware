2018 Delaware precinct and election shapefile.

## RDH Date retrieval
07/12/2020

## Sources
Election results from Delaware Department of Elections (https://elections.delaware.gov/archive/elect18/elect18_general/html/index.shtml)
Precinct shapefile from State of Delaware FirstMap GIS (http://opendata.firstmap.delaware.gov/datasets/delaware-election-boundaries)

## Fields metadata

Vote Column Label Format
------------------------
Columns reporting votes follow a standard label pattern. One example is:
G16PREDCli
The first character is G for a general election, P for a primary, S for a special, and R for a runoff.
Characters 2 and 3 are the year of the election.
Characters 4-6 represent the office type (see list below).
Character 7 represents the party of the candidate.
Characters 8-10 are the first three letters of the candidate's last name.

Office Codes
A## - Ballot amendment, where ## is an identifier
AGR - Commissioner of Agriculture
ATG - Attorney General
AUD - Auditor
CFO - Chief Financial Officer
CHA - Council Chairman
COC - Corporation Commissioner
COM - Comptroller
CON - State Controller
COU - City Council Member
CSC - Clerk of the Supreme Court
DEL - Delegate to the U.S. House
GOV - Governor
H## - U.S. House, where ## is the district number. AL: at large.
HOD - House of Delegates, accompanied by a HOD_DIST column indicating district number
HOR - U.S. House, accompanied by a HOR_DIST column indicating district number
INS - Insurance Commissioner
LAB - Labor Commissioner
LND - Commissioner of Public/State Lands
LTG - Lieutenant Governor
MAY - Mayor
MNI - State Mine Inspector
PSC - Public Service Commissioner
PUC - Public Utilities Commissioner
RGT - State University Regent
SAC - State Appeals Court
SBE - State Board of Education
SOC - Secretary of Commonwealth
SOS - Secretary of State
SPI - Superintendent of Public Instruction
SPL - Commissioner of School and Public Lands
SSC - State Supreme Court
TAX - Tax Commissioner
TRE - Treasurer
UBR - University Board of Regents/Trustees/Governors
USS - U.S. Senate

Party Codes
D and R will always represent Democrat and Republican, respectively.
See the state-specific notes for the remaining codes used in a particular file; note that third-party candidates may appear on the ballot under different party labels in different states.

## Fields
G18USSDCAR - Thomas R. Carper (Democratic Party)
G18USSRARL - Robert B. Arlett (Republican Party)
G18USSGTHE - Emitri G. Theodoropoulos (Green Party)
G18USSLFRO - Nadine M. Frost (Libertarian Party)

G18HALDROC - Lisa Blunt Rochester (Democratic Party)
G18HALRWAL - Scott Walker (Republican Party)

G18ATGDJEN - Kathleen Jennings (Democratic Party)
G18ATGRPEP - Bernard V. Pepukayi, Sr. (Republican Party)

G18TREDDAV - Colleen Davis (Democratic Party)
G18TRERSIM - Kenneth A. Simpler (Republican Party)
G18TREGCHA - David B. Chandler (Green Party)

G18AUDDMCG - Kathleen K. McGuiness (Democratic Party)
G18AUDRSPA - James Spadola (Republican Party)

## Processing Steps
Precincts 17-02, 16-31, and 16-41 are the reporting units for UOCAVA votes from New Castle, Kent, and Sussex Counties, respectively. These were distributed by candidate to precincts based on their share of the precinct-level reported vote.

Precincts 02-09/10-09, 05-09/11-09, 08-09/12-09/13-09 were split in the shapefile to reflect changes made prior to the 2018 election.