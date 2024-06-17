2016 Delaware precinct and election results shapefile.

## RDH Date retrieval
11/26/2020

## Sources
Election results from Delaware Department of Elections (https://elections.delaware.gov/archive/elect16/elect16_general/html/index.shtml)
Precinct shapefile from State of Delaware FirstMap GIS (http://opendata.firstmap.delaware.gov/datasets/delaware-election-boundaries)

## Fields metadata

Vote Column Label Format
------------------------
Columns reporting votes follow a standard label pattern. One example is:
G16PREDCli
The first character is G for a general election, P for a primary, C for a caucus, R for a runoff, S for a special.
Characters 2 and 3 are the year of the election.
Characters 4-6 represent the office type (see list below).
Character 7 represents the party of the candidate.
Characters 8-10 are the first three letters of the candidate's last name.

Office Codes
AGR - Commissioner of Agriculture
ATG - Attorney General
AUD - Auditor
COM - Comptroller
COU - City Council Member
DEL - Delegate to the U.S. House
GOV - Governor
H## - U.S. House, where ## is the district number. AL: at large.
HOD - House of Delegates, accompanied by a HOD_DIST column indicating district number
HOR - U.S. House, accompanied by a HOR_DIST column indicating district number
INS - Commissioner of Insurance
LAB - Commissioner of Labor
LTG - Lieutenant Governor
LND - Commissioner of Public Lands
PRE - President
PSC - Public Service Commissioner
PUC - Public Utilities Commissioner
RGT - State University Regent
RRC - Railroad Commissioner
SAC - State Court of Appeals
SOS - Secretary of State
SOV - Senate of Virginia, accompanied by a SOV_DIST column indicating district number
SPI - Superintendent of Public Instruction
SSC - State Supreme Court
TRE - Treasurer
USS - U.S. Senate

Party Codes
D and R will always represent Democrat and Republican, respectively.
See the state-specific notes for the remaining codes used in a particular file; note that third-party candidates may appear on the ballot under different party labels in different states.

## Fields

G16PREDCLI - Hillary Clinton (Democratic Party)
G16PRERTRU - Donald J. Trump (Republican Party)
G16PREGSTE - Jill Stein (Green Party)
G16PRELJOH - Gary Johnson (Libertarian Party)

G16HALDROC - Lisa Blunt Rochester (Democratic Party)
G16HALRREI - Hans Reigle (Republican Party)
G16HALGPER - Mark J. Perri (Green Party)
G16HALLGES - Scott A. Gesty (Libertarian Party)

G16GOVDCAR - John Carney (Democratic Party)
G16GOVRBON - Colin Bonini (Republican Party)
G16GOVGGRO - Andrew Groff (Green Party)
G16GOVLGOW - Sean Louis Goward (Libertarian Party)

G16LTGDHAL - Bethany Hall-Long (Democratic Party)
G16LTGRGUN - La Mar Gunn (Republican Party)

G16INSDNAV - Trinidad Navarro (Democratic Party)
G16INSRCRA - Jeffrey E. Cragg (Republican Party)

## Processing Steps
Precincts 17-02, 16-31, and 16-41 are the reporting units for UOCAVA votes from New Castle, Kent, and Sussex Counties, respectively. These were distributed by candidate to precincts based on their share of the precinct-level reported vote.