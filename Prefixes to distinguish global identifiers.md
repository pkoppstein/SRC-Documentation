Column 11 of the globalids2Klarner.tsv file provides a secondary global id for the SRC project, in support of integrity-checking.  Identifiers appearing in this column are always prefixed.
If available, a SLERs id is used with the letter K (for "Klarner") as prefix. Otherwise, a colon-prefix is used, as detailed below.

With the above-mentioned exception, numerical global ids are only prefixed when the context requires.

An attempt has been made to ensure that column 14 of legislator.tsv files has an "ftm" id. ("ftm" refers to followthemoney.org, aka CSMSP.) Currently the ftm eid value is used if available.  Prior to December 20, 2018, the ftm "uc" id was used if available.
 
As context requires, the following colon-prefixes are used, with preference generally being given in the order shown:

    eid:  # the followthemoney.org "eid" id
    os:   # OpenStates
    ls:   # LegiScan people_id
    vs:   # VoteSmart
    oc:   # https://www.ourcampaigns.com/CandidateDetail.html?CandidateID=
    src:  # SRC (this project)
 
Note: Prior to 20 December 2018, the prefix uc: was sometimes used for the predecessor of the ftm "eid" id.