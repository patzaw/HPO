<!----------------------------------------------------------------------------->
<!----------------------------------------------------------------------------->
## Version 0.20 -- Release notes

### Data source changes

   - phenotype.hpoa instead of phenotype_annotation.tab
   - much less synonyms

### Data model changes

   - phenotype frequency included
   - obsolete id isolated

<!----------------------------------------------------------------------------->
<!----------------------------------------------------------------------------->
## Version 0.13 -- Release notes

### Implementation changes

   - Considering [Term] def only
   
<!----------------------------------------------------------------------------->
<!----------------------------------------------------------------------------->
## Version 0.12 -- Release notes

### Implementation changes

   - `write_tsv`: quote="all", na="<NA>"

<!----------------------------------------------------------------------------->
<!----------------------------------------------------------------------------->
## Version 0.10 -- Release notes

### Implementation changes

	- Adapt collections to new TKCat

<!----------------------------------------------------------------------------->
<!----------------------------------------------------------------------------->
## Version 0.9 -- Release notes

### DESCRIPTION changes

   - Author information

### Implementation changes
   
   - Remove trailing spaces


<!----------------------------------------------------------------------------->
<!----------------------------------------------------------------------------->
## Version 0.8 -- Release notes

### Implementation changes
   
   - Dealing with "#" header in the *phenotype_annotation.tab* source file


<!----------------------------------------------------------------------------->
<!----------------------------------------------------------------------------->
## Version 0.7 -- Release notes

### Implementation changes
   
   - json data model


<!----------------------------------------------------------------------------->
<!----------------------------------------------------------------------------->
## Version 0.6 -- Release notes

### Data model changes
   
   - Add collections


<!----------------------------------------------------------------------------->
<!----------------------------------------------------------------------------->
## Version 0.5 -- Release notes

### Data model changes

   - new "HPO_synonyms" table
   - new "level" field in the "HPO_hp" table

### Implementation changes

	- Using tibbles

<!----------------------------------------------------------------------------->
<!----------------------------------------------------------------------------->
## Version 0.4 -- Release notes

### Data model changes

   - new "HPO_parents" table
   - new "HPO_descendants" table
   - remove "parent" field from the "HPO_hp" table
   - new "level" field in the "HPO_hp" table

### Implementation changes

	- Using the "here" package for locating files

<!----------------------------------------------------------------------------->
<!----------------------------------------------------------------------------->
## Version 0.3 -- Release notes

### Implementation changes

	- Tables are exported with " quotes for delimiting fields and escaped when needed by doubling them
