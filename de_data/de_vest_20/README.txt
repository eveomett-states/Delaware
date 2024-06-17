2020 Delaware precinct and election results shapefile.

## RDH Date retrieval
06/07/2021

## Sources
Election results from Delaware Department of Elections (https://elections.delaware.gov/archive/elect20/elect20_election_index.shtml)
Precinct shapefile from State of Delaware FirstMap GIS (http://opendata.firstmap.delaware.gov/datasets/delaware-election-boundaries)

## Fields metadata

Vote Column Label Format
------------------------
Columns reporting votes follow a standard label pattern. One example is:
G20PRERTRU
The first character is G for a general election, C for recount results, P for a primary, S for a special, and R for a runoff.
Characters 2 and 3 are the year of the election.
Characters 4-6 represent the office type (see list below).
Character 7 represents the party of the candidate.
Characters 8-10 are the first three letters of the candidate's last name.

Office Codes

ATG - Attorney General
AUD - Auditor
COC - Corporation Commissioner
COU - City Council Member
DEL - Delegate to the U.S. House
GOV - Governor
H## - U.S. House, where ## is the district number. AL: at large.
INS - Insurance Commissioner
LTG - Lieutenant Governor
PRE - President
PSC - Public Service Commissioner
SAC - State Appeals Court (in AL: Civil Appeals)
SCC - State Court of Criminal Appeals
SOS - Secretary of State
SPI - Superintendent of Public Instruction
USS - U.S. Senate

Party Codes
D and R will always represent Democrat and Republican, respectively.
See the state-specific notes for the remaining codes used in a particular file; note that third-party candidates may appear on the ballot under different party labels in different states.

## Fields

G20PREDBID - Joseph R. Biden (Democratic Party)
G20PRERTRU - Donald J. Trump (Republican Party)
G20PRELJOR - Jo Jorgensen (Libertarian Party)
G20PREGHAW - Howie Hawkins (Green Party of Delaware)

G20USSDCOO - Christopher A. Coons (Democratic Party)
G20USSRWIT - Lauren Witzke (Republican Party)
G20USSLFRO - Nadine M. Frost (Libertarian Party)
G20USSITUR - Mark W. Turley (Independent Party of Delaware)

G20HALDROC - Lisa Blunt Rochester (Democratic Party)
G20HALRMUR - Lee Murphy (Republican Party)
G20HALLROG - David L. Rogers (Libertarian Party)
G20HALIPUR - Catherine S. Purcell (Independent Party of Delaware)

G20GOVDCAR - John C. Carney Jr. (Democratic Party)
G20GOVRMUR - Julianne E. Murray (Republican Party)
G20GOVLMAC - John J. Machurek (Libertarian Party)
G20GOVIDEM - Kathy S. DeMatteis (Independent Party of Delaware)

G20LTGDHAL - Bethany Hall-Long (Democratic Party)
G20LTGRHAL - Donyale Hall (Republican Party)

G20INSDNAV - Trinidad Navarro (Democratic Party)
G20INSRPIL - Julia Pillsbury (Republican Party)


## Processing Steps

Precincts 17-02, 16-31, and 16-41 are the reporting units for UOCAVA votes from New Castle, Kent, and Sussex Counties, respectively. These were distributed by candidate to precincts based on their share of the precinct-level reported vote.

Precincts 10-02/13-02 were merged and precincts 02-09/10-09, 05-09/11-09, 08-09/12-09/13-09 were split in the shapefile to reflect changes made prior to the 2020 election.
