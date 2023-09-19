# Readme 
## Processing of OH 2022 General Election Precinct Level Results Disaggregated to Census Block Level

### Directory explanation
- oh_22_disag_v1.ipynb: disaggregation script for statewide results
- internal_use_only/: WIP - not used to produce any files

### Additional Notes
At the precinct level we provide congressional and legislative district results at the precinct level split by district. In order to disaggregate results for those contests, those precinct files should be used. In running our script, however, some of the disaggregated shapes produced are so small that they do not receive a block assignment and as a result the precinct and state totals do not match pre vs. post disaggregation. 

To create such a file in the future, we/a user would need to run a reverse-maup assignment for those specific cases (of which there are 3 impacted precincts in the congressional file, 38 in SLDL, and 8 in SLDU). 

Please reach out to info@redistrictingdatahub.org for more information.