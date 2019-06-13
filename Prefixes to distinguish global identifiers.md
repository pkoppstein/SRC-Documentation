Column 11 of the globalids2Klarner.tsv file provides a secondary global id for the SRC project, in support of integrity-checking.  Identifiers appearing in this column are always prefixed.
If available, a SLERs id is used with the letter K (for "Klarner") as prefix. Otherwise, a colon-prefix is used, as detailed below.

With the above-mentioned exception, numerical global ids are only prefixed when the context requires.

An attempt has been made to ensure that column 14 of legislator.tsv files has an "ftm" id. ("ftm" refers to followthemoney.org, aka CSMSP.) Currently the ftm eid value is used if available.  Prior to December 20, 2018, the ftm "uc" id was used if available.
 
As context requires, the following colon-prefixes are used, with preference generally being given in the order shown:

    eid:  # the followthemoney.org "eid" id
    os:   # OpenStates "leg_id" (see below)
    ls:   # LegiScan "people_id"
    vs:   # https://votesmart.org/candidate/
    oc:   # https://www.ourcampaigns.com/CandidateDetail.html?CandidateID=
    tx:   # https://www.lrl.texas.gov/legeLeaders/members/memberDisplay.cfm?memberID=
    src:  # SRC (this project)
 
Note: Prior to 20 December 2018, the prefix uc: was sometimes used for the predecessor of the ftm "eid" id.

### OpenStates ###
OpenStates "leg_id" values have the form STCnnnnnn where ST is the two-letter state abbreviation and C is generally either L or U, e.g. `DCL000021`.  

It used to be the case that the leg_id could be used for online lookups having the form illustrated by:

    https://openstates.org/AZ/legislators/AZL000001

archive.org does make it possible to retrieve the relevant legislator page using this form.

The `leg_id` was used in the bulk data files, the so-called "legacy JSON files" available from:
 
    https://docs.openstates.org/en/latest/data/legacy-json.html

These legacy files are (or were) named following the schema illustrated by: 2017-06-30-az-json.zip

Version 2 of the OpenStates API (https://docs.openstates.org/en/latest/api/v2/) does return the leg_id value if there is one.

### Other Prefixes ###
These are reserved for future possible use in global identifiers:

    sd:   # http://sdlegislature.gov/Legislators/Historical_Listing/LegislatorDetail.aspx?MemberID=