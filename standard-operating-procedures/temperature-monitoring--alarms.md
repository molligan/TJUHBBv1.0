[block:api-header]
{
  "type": "basic",
  "title": "PURPOSE"
}
[/block]
Temperature monitoring is instrumental in ensuring biospecimen quality and longevity. Biospecimens are subject to degradation at the tissue, cell, and molecular levels unless temperatures are kept sufficiently low. Furthermore, large deviations in operating temperatures and repeated freeze-thaw cycles can also negatively affect biospecimen integrity. Therefore, it is important to monitor the temperature of biospecimen storage units and have adequate reporting and recovery procedures if temperature deviations occur.
[block:api-header]
{
  "type": "basic",
  "title": "SCOPE"
}
[/block]
This standard operating procedure (SOP) describes how the temperature of biospecimen storage units should be monitored. Furthermore, this document describes the procedures required if a temperature deviation is encountered.  
[block:api-header]
{
  "type": "basic",
  "title": "REFERENCE TO OTHER TJUHBB SOPS OR POLICIES"
}
[/block]

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
    "0-0": "Biobank Technologist",
    "1-0": "Phlebotomist/ Venipuncture nurse",
    "2-0": "Laboratory Technician/Technologist",
    "0-1": "Maintaining temperature logs; Testing and validating alarm systems",
    "1-1": "Draw Blood from patient and read and understand product inserts",
    "2-1": "Transport and Process blood",
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
  "rows": 1
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
    "h-1": "Quantity",
    "0-0": "Temperature Probes",
    "1-0": "Temperature Transmitters",
    "2-0": "Temperature Receiver (gateway)",
    "3-0": "",
    "4-0": "Buffer BR2 (Binding Buffer)",
    "5-0": "Buffer BR3 (Wash Buffer)",
    "6-0": "Buffer BR4 (Wash Buffer)",
    "7-0": "Buffer BR5 (Elution Buffer)",
    "8-0": "RNAse -Free Water (bottle",
    "9-0": "PAXgene RNA Spin Columns (red)",
    "10-0": "Processing Tubes (2 mL)",
    "11-0": "Secondary BD Hemogard Closures",
    "11-1": "6 x 50",
    "12-0": "Microcentrifuge Tubes (1.5 mL)",
    "13-0": "DNAse I, RNAse-Free (lyophilized)",
    "14-0": "Buffer RDD (white lid)",
    "15-0": "PAXgene Shredder Spin Columns (lilac)",
    "16-0": "Centrifuge capable of 2500 x g, equipped with swing-out rotor and buckets that accommodate 50 ml Processing Tubes",
    "3-1": "",
    "4-1": "18 mL",
    "5-1": "45 mL",
    "6-1": "11 mL",
    "7-1": "6 mL",
    "8-1": "2 x 125 mL",
    "9-1": "2 x 1.4 mL",
    "10-1": "5 x 10",
    "12-1": "50",
    "13-1": "1500 Kunitz units",
    "14-1": "2 x 2 mL",
    "15-1": "5 x 10",
    "0-1": "1 per storage unit",
    "1-1": "1 per storage unit"
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
# Temperature Monitoring
* Temperature monitoring is conducted autonomously through the LabAlert FusionLive software. Temperature probes are placed within the freezer at the same location as the internal temperature probe ( Panasonic NTCPBUNIV) via the freezer port.
* The probe is connected is to the transmitter (Panasonic NTCUNIVZBPS) which relays the temperature of the probe over an independent wireless connection at 15 minute intervals.
* The temperature readout from the transmitter is received by the gateway (Panasonic NTCGATEWAYT) which is connected to the local area network and relays all of the temperature information to LabAlert servers.
* A record of hourly temperatures for every probe are are stored as reports on the LabAlert servers and can be summoned at anytime via the reports tab. (See Figure 1)
[block:image]
{
  "images": [
    {
      "image": [
        "https://www.filepicker.io/api/file/AWQQLnRTPeA9hw0QT0Cv",
        "reports.jpg",
        "627",
        "313",
        "#a88f6c",
        ""
      ],
      "caption": "Figure 1. Reports Tab"
    }
  ]
}
[/block]
* Daily reports are summarized on a weekly basis and printed out in hardcopy. (See Figure 2)

[block:image]
{
  "images": [
    {
      "image": [
        "https://www.filepicker.io/api/file/OaPuvutXRGWJ6ikuyU4i",
        "dailySummary.jpg",
        "1045",
        "500",
        "#2465c4",
        ""
      ],
      "caption": "Figure 2. Daily Summary"
    }
  ]
}
[/block]

[block:callout]
{
  "type": "warning",
  "body": "If a temperature probe or transmitter malfunctions and gateway does not receive a signal for greater than 15 minutes, an alert will be sent through SMS message and email to the biobank technologist.",
  "title": "Receiver or Probe Malfunction"
}
[/block]

[block:callout]
{
  "type": "warning",
  "title": "Gateway Malfunction",
  "body": "If the FusionLive servers do not receive a signal from the gateway for greater than 15 minutes, an alert will be sent through SMS message and email to the biobank technologist."
}
[/block]
# Alarms
* If temperature deviations occur outside the specified range, a warning will be issued initially. This warning is received by the biobank technologist through SMS message and email. 
* If the temperature deviation continues past the alarm threshold, the biobank technologist will be alerted via SMS message and email. 
* Simultaneously, a ticket will be created that will require documentation regarding the cause of the alarm as well as any actions taken (see Figure 3). These tickets can be found under the "Tickets" tab at the bottom of the screen.
[block:image]
{
  "images": [
    {
      "image": [
        "https://www.filepicker.io/api/file/CVVt8XNWQfKHhqruUPZl",
        "Tickets.jpg",
        "1105",
        "143",
        "#9d8360",
        ""
      ],
      "caption": "Figure 3. Ticket Log"
    }
  ]
}
[/block]
* If a ticket is created, the technologist should double-click on the ticket to document and close the ticket. This can be seen in the Figure 4 below.
[block:image]
{
  "images": [
    {
      "image": [
        "https://www.filepicker.io/api/file/x2BSWhfSe2qPdlO9VlfA",
        "TicketAction.jpg",
        "782",
        "364",
        "#907c60",
        ""
      ],
      "caption": "Figure 4. Ticket Documentation"
    }
  ]
}
[/block]
* The following fields are required documentation for any ticket created.
    * Ticket Cause - Document the underlying cause of the alarm
    * Ticket Action - Document any actions that were required to either stop the alarm and/or prevent future alarms of a similar type from occurring.
    * Acknowledge - Document that the alarm was acknowledged by the technologist.
* If any report costs are incurred or if the equipment being monitored is still in warranty, these can be optionally documented as well.
[block:callout]
{
  "type": "danger",
  "title": "Alarms",
  "body": "The alarms must be attended to promptly as to ensure the viability of all biospecimens. If an alarm is received, a technologist is required to physically evaluate the alarm within 1 hour of receiving the alarm. The technologist must document the alarm report, the cause of the alarm, and any actions taken."
}
[/block]
 
[block:api-header]
{
  "type": "basic",
  "title": "APPLICABLE REFERENCES, REGULATIONS AND GUIDELINES"
}
[/block]
* Declaration of Helsinki
http://www.wma.net/en/30publications/10policies/b3/index.html

* Tri-Council Policy Statement 2; Ethical Conduct for Research Involving Humans; Medical Research Council of Canada; Natural Sciences and Engineering Council of Canada; Social Sciences and Humanities Research Council of Canada, December 2010.   
http://www.pre.ethics.gc.ca/eng/policy-politique/initiatives/tcps2-eptc2/Default/

* Human Tissue and Biological Samples for use in Research. Operational and Ethical Guidelines. Medical Research Council Ethics
http://www.mrc.ac.uk/Utilities/Documentrecord/index.htm?d=MRC002420

* Best Practices for Repositories I. Collection, Storage and Retrieval of Human Biological Materials for Research. International Society for Biological and Environmental Repositories (ISBER).
http://www.isber.org/Search/search.asp?zoom_query=best+practices+for+repositories

* US National Biospecimen Network Blueprint
http://biospecimens.cancer.gov/resources/publications/reports/nbn.asp

* PAXgene Blood RNA Kit Handbook: For isolation of genomic DNA from 8.5 ml human whole blood. October 2009

[block:api-header]
{
  "type": "basic",
  "title": "APPENDICES"
}
[/block]
* Appendix A– Blood Collection and Processing Worksheets
[block:api-header]
{
  "type": "basic",
  "title": "REVISION HISTORY"
}
[/block]