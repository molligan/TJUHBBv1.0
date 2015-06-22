[block:api-header]
{
  "type": "basic",
  "title": "PURPOSE"
}
[/block]
Tumor biobanks are intended to manage the safekeeping of clinical data and other sample associated data in their custody.  TJUHBB has policies regarding security safeguards to protect data and personal information stored in its database against failure, loss and damage.  Failure may occur due to user error (modifying or destroying the data on its own or through a user choice), media failure (failure of equipment such hard drive) or a catastrophic event such as a fire, flood, power outage, virus, or deliberate hacking.  The backup process must ensure the database can be completely and accurately recovered. TJUHBBstrives to ensure data can be fully recovered on a daily basis. The aim is to limit data loss to no more than one day. 
[block:api-header]
{
  "type": "basic",
  "title": "SCOPE"
}
[/block]
This standard operating procedure (SOP) outlines general elements and features that should be in place to ensure that information stored in a database can be recovered accurately, completely and in a timely manner.
[block:api-header]
{
  "type": "basic",
  "title": "REFERENCE TO OTHER TJUHBB SOPS OR POLICIES"
}
[/block]

* TJUHBB Policy: POL 4 Privacy and Security
* TJUHBB Policy: POL 7 Material and Information Handling 
[block:api-header]
{
  "type": "basic",
  "title": "ROLES AND RESPONSIBILITIES"
}
[/block]
This SOP applies to all qualified tumor biobank personnel and clinical staff at the collection centers that are involved in recruiting patients and the acquisition of informed and voluntary consent.  This may include the following personnel:
[block:parameters]
{
  "data": {
    "h-0": "Tumor Biobank Personnel",
    "h-1": "Responsibility",
    "0-0": "Information Technology (IT) Staff",
    "1-0": "Tumor Biobank Director, Manager, or Principal Investigator.",
    "2-0": "Tumor Biobank management",
    "0-1": "Conducts backup/restores database according to specific biobank plan.",
    "1-1": "Participates in development of biobank backup and recovery plan. Outlines recovery expectations.",
    "2-1": "Ensures adequate backup systems are in place",
    "3-0": "Pathology Coordinator/Assistant",
    "4-0": "Operating Room Nurse",
    "5-0": "Laboratory Technician/technologist",
    "6-0": "Histology Technician/technologist",
    "3-1": "See Procedures (section 7)",
    "4-1": "See Procedures (section 7)",
    "5-1": "See Procedures (section 7)",
    "6-1": "See Procedures (section 7)"
  },
  "cols": 2,
  "rows": 3
}
[/block]

[block:api-header]
{
  "type": "basic",
  "title": "MATERIALS, EQUIPMENT AND FORMS"
}
[/block]
The materials, equipment and forms listed in the following list are recommendations only and may be substituted by alternative/equivalent products more suitable for the site-specific task or procedure.
[block:parameters]
{
  "data": {
    "h-0": "Materials & Equipment",
    "h-1": "Materials & Equipment (Site Specific)",
    "0-0": "Database back up system",
    "1-0": "Removable backup media",
    "2-0": "Offsite storage location",
    "3-0": "Unused samples from participant revoking consent"
  },
  "cols": 2,
  "rows": 3
}
[/block]

[block:api-header]
{
  "type": "basic",
  "title": "DEFINITIONS"
}
[/block]
See the TJUHBB Glossary.
[block:api-header]
{
  "type": "basic",
  "title": "PROCEDURES"
}
[/block]
The facility must employ backup systems to protect the data stored on the database from damage and loss.  In the case of user error, media failure or catastrophic events, the system should ideally be able to recover the information to or near the point before failure occurred.  There should also be confidence that the information is complete and free of corruption. 

# Database Backup – General Description of Process

* Each biobank should develop a backup strategy based on:
    * Database size
    * Backup media available
    * Database Management System (DBMS) used
    * Recovery requirements (Acceptable data loss)
    * Error detection. Undiscovered problems with data integrity that may require recovery from one or more older archive sets to locate and correct the problem.
* Upon development of an acceptable backup plan, IT staff at the biobank should implement and monitor regular backups.
* Send regular backup copies to offsite storage in case of fire, flood, earthquake or other natural disasters which may destroy on-site archives. 
* Test data recovery at specific intervals as specified in the backup/recovery plan and record results.  Test both individual records and full database recovery.  Be sure to test offsite archival sets as well.

# Database Backup – Routine Process

* An automated database dump occurs nightly on the local biobank servers.
* The biobank servers are backed-up nightly by JeffIT to a dedicated SAN.
* The back-ups are then transferred to tape for long-term storage.
 
# Database Backup - Frequency

* The database is backed up nightly. In the event of catastrophic hardware failure, at most one day of data entry or changes may be lost. 

# Offsite Storage
* Both off-site and tape storage are used for archival purposes.
* Off-site storage occurs nightly.

# Database Backup – Recovery Plan
* In the event of a catastrophic database failure, the technologist should alert the database personnel at the Kimmel Cancer Center.
* The most recent backup (i.e. mirrored backup of the prior day) should be re-instantiated and any new information that was lost during the current day should attempt to be re-entered into the database.
* The event should be documented using the Hardware/Software Failure sheet and an investigation should be conducted to find an underlying reason for the failure.
* Measures should be taken to ensure that future failures do not occur for similar reasons. 
[block:api-header]
{
  "type": "basic",
  "title": "APPLICABLE REFERENCES, REGULATIONS AND GUIDELINES"
}
[/block]
* Tri-Council Policy Statement 2; Ethical Conduct for Research Involving Humans; Medical Research Council of Canada; Natural Sciences and Engineering Council of Canada; Social Sciences and Humanities Research Council of Canada, December 2010.    
http://www.pre.ethics.gc.ca/eng/policy-politique/initiatives/tcps2-eptc2/Default/

* Best Practices for Repositories I. Collection, Storage and Retrieval of Human Biological Materials for Research. International Society for Biological and Environmental Repositories (ISBER).
http://www.isber.org/Search/search.asp?zoom_query=best+practices+for+repositories

* US National Biospecimen Network Blueprint
http://biospecimens.cancer.gov/resources/publications/reports/nbn.asp

[block:api-header]
{
  "type": "basic",
  "title": "APPENDICES"
}
[/block]
None
[block:api-header]
{
  "type": "basic",
  "title": "REVISION HISTORY"
}
[/block]