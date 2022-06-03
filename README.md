# CIS Controls

## CIS_Controls_Initial_Assessment_Tool_v8.0b_martinsohndk.xlsx
  * Fork of [CIS Critical Security Control v8.0 Assessment Tool by Audit Scripts](https://www.auditscripts.com/free-resources/critical-security-controls/).
  * Controls and their Safeguards are listed in one sheet, instead of one sheet per Control as in the Audit Scripts version. IMO this makes audit, post-audit analysis, and modifications easier.
  * Enriched with CIS data:
    * 'Asset Type', the type of asset each specific Safeguard is relevant for.
    * 'Title', short description of each Control and Safeguard, whereas the full description is in column 'CIS Control Details'.
    * 'CIS Control Details', describing the 18 Controls.
    * Implementation Group details stored in columns instead of previous string eg. '2,3'.
  * [Fixes a bug in policy score of Control #15](https://twitter.com/martinsohndk/status/1488843594429521920).
  * Changed old terms such as 'sub control' to 'Safeguard', and 'Critical Security Controls' to 'CIS Controls'.
  * I take no responsibility in updating this for future CIS Controls versions.
