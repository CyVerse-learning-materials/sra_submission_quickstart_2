.. include:: cyverse_rst_defined_substitutions.txt
.. include:: custom_urls.txt

|CyVerse_logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

Validate and submit package to SRA
======================================


I. Validate Submission
------------------------

In this section, you will verify that metadata has been appropriately associated
with your submission package and complete the submission process.

  1. Login to the CyVerse |Discovery Environment|.

  2. Access the |NCBI SRA Submission - BioProject Creation| App at this link or
   search for the 'NCBI SRA Submission - BioProject Creation' App in the search
   bar.

  3. If desired, enter an analysis name or comments.

  4. Under "Parameters" check **'Validate metadata file only?'**.

  5. Under 'Select BioProject Folder' browse to and select the top-level
     BioProject folder. Under 'Select BioProject metadata file' browse to and
     select the previously generated metadata file (.xml).

      .. tip::
        When browsing for the folder, ensure the "Selected folder" is your
        BioProject folder, not a sub-folder.

  6. Under 'Review and Launch' 'Launch Analysis' to begin the validation, and
     click on |analyses icon| (Analyses Icon) to monitor the job progress. When
     status is 'Completed', click on the job name to view results. A successful
     validation will generate two folders:

       - A folder of logs
       - A folder with your username and a long alphanumeric string.  This
         folder will contain the submission.xml metadata file associated with your submission.

      .. tip::

          Although a job returns with the status 'Complete' that does not mean
          that the submission is error-free. In the submission process, NCBI
          will review the submitted files and metadata and may discover errors.

        **For failed validation/submissions**
        For either validation or submission, if the app fails and no
        submission.xml file is created, there are one or more errors in the
        submission package. See the Analysis log files (especially condor-
        stderr-0) for information to assist with error correction.

II. Send submission package to SRA
------------------------------------
In this step, we use the application above, but the option to 'Validate metadata
file only' is left **unchecked**.

  1. Login to the CyVerse |Discovery Environment|.

  2. Access the |NCBI SRA Submission - BioProject Creation| App at this link or
   search for the 'NCBI SRA Submission - BioProject Creation' App in the search
   bar.

  3. If desired, enter an analysis name or comments.


  4. Under 'Select BioProject Folder' browse to and select the top-level
     BioProject folder. Under 'Select BioProject metadata file' browse to and
     select the previously generated metadata file (.xml).

      .. tip::
        When browsing for the folder, ensure the "Selected folder" is your
        BioProject folder, not a sub-folder.

  6. Under 'Review and Launch' 'Launch Analysis' to begin the submission, and
     click on |analyses icon| (Analyses Icon) to monitor the job progress. When
     status is 'Completed', click on the job name to view results. A successful
     validation will generate two folders:

       - A folder of logs
       - A folder with your username and a long alphanumeric string.  This
         folder will contain the submission.xml metadata file associated with your submission.

      .. tip::

          Although a job returns with the status 'Complete' that does not mean
          that the submission is error-free. In the submission process, NCBI
          will review the submitted files and metadata and may discover errors.

        **For failed validation/submissions**
        For either validation or submission, if the app fails and no
        submission.xml file is created, there are one or more errors in the
        submission package. See the Analysis log files (especially condor-
        stderr-0) for information to assist with error correction.


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
