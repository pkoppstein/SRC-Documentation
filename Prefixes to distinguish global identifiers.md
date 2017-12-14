Identifiers appearing in column 11 of the globalids2Klarner.tsv file are always prefixed.
This column provides a secondary global id for the SRC project, in support of integrity-checking. 

With this exception, numerical global ids are only prefixed when the context requires.
For example, an attempt has been made to ensure that every legislator has an "ftm" id, which is 
currently the ftm uc value if available, or else the ftm eid if available, or some other id.

In column 11 of the globalids2Klarner.tsv file, SLERs ids are preceded by K (for "Klarner").
If the SLERs id was unavailable at the time the entry was created, the following colon-prefixes are used, with preference being given in the order shown:

    eid:  # the followthemoney.org "eid" id
    os:   # OpenStates
    ls:   # LegiScan people_id
    vs:   # VoteSmart
    src:  # SRC
  
These prefixes are used elsewhere as well, as context requires.