.. include:: cyverse_rst_defined_substitutions.txt
.. include:: custom_urls.txt

|CyVerse_logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_


Confirm submission to SRA and fix errors
===========================================

CyVerse systems connect to SRA systems and create the submission folder on the
SRA side.  Files are transferred and a 'submit.ready' file is sent to the SRA to
signal that the submission package is complete and they can begin processing.
The SRA system validates the submission package and generates a report.xml file
containing any errors detected. The SRA system sends notification email(s) to
the contact email provided in the BioProject metadata template, and to the
CyVerse team to notify of either a successful or failed submission.

If your SRA submission is successful
--------------------------------------
You will receive an email ("Submission ownership transfer") at the email address
provided in the package metadata (also associated with your NCBI account).
After ownership transfer, you can view the |submission progress| at NCBI.
You may need to log in with the NCBI credentials for the account you used in the
submission metadata.


If your SRA submission contains errors
----------------------------------------
You will receive an email at the email address provided in the package metadata
(also associated with your NCBI account) informing you about the error. you can
retrieve the submission report.xml file from SRA servers with the 'NCBI SRA
Submission Report Retrieval' App in the DE, make corrections, and resubmit.
This will typically involve making edits to the metadata as covered in the
previous sections.

    .. tip::

      **Fixing errors in metadata entries**

      To fix metadata entries, it is not *not* necessary to download/edit/upload
      templates. For a folder you wish to correct, select the folder in a Data
      window and from the "Metadata" menu select 'Edit/View metadata'; select
      any entry you wish to edit and then click the 'Edit' button. Save your edit
      and then click 'Save' again to save the metadata file.


      **Other tips**

      - Remember to save a new metadata file from the top level of the
        submission package before resubmitting. It is best practice to name
        this file differently from the previous metadata file.
      - During error correction, only make changes to SRA-detected errors. All
        other changes will be ignored by the SRA during resubmission. If
        additional changes are required, they can be made using the NCBI website
        after successful submission.
      - If no report.xml is retrieved, this does not necessarily mean your
        submission failed. The SRA system may not have generated it yet. Make
        sure to wait for notification from the SRA that the submission has been
        received and processed.


**Next Steps:**

Once you have verified your files are available to the SRA, you can consider
deleting these files from the CyVerse Data Store.

----------

Additional information, help
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

  The |NCBI SRA Submission Quick Start| is the authoritative guide to SRA
  requirements. It is worth reading through this to get additional/updated
  information. 

----

**Fix or improve this documentation**

- Search for an answer:
  |CyVerse Learning Center|
- Ask us for help:
  click |Intercom| on the lower right-hand side of the page
- Report an issue or submit a change:
  |Github Repo Link|
- Send feedback: `learning@CyVerse.org <learning@CyVerse.org>`_

----

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_
