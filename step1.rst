.. include:: cyverse_rst_defined_substitutions.txt
.. include:: custom_urls.txt

|CyVerse_logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

Create and organize an SRA submission package
===============================================

.. Important::
  **A Reminder on File Names and other SRA Requirements**

  NCBI has extensive requirements for depositing data into the SRA. The CyVerse
  submission pipeline is an attempt to streamline this process, but your
  submission must meet several requirements.

  File names in your submission must:

   - Be unique
   - Not contain special characters (e.g. { } ? * . , etc.) or spaces.

  The |NCBI SRA Submission Quick Start| is the authoritative guide to SRA requirements. It is worth reading through this before submission.


.. important::

    This quickstart assumes you have uploaded your files to the CyVerse Data
    Store. If not, following the |Data Store Guide| directions for uploading
    files to the Data Store. If possible, you may wish to compress these files
    using gunzip/bzip2 prior to upload.



(Optional) Compress files in the CyVerse Data Store using gunzip
-------------------------------------------------------------------
For submission through CyVerse, the sequence files must be compressed. If your
files are compressed (.gz/.bz2) you may skip this step.

  1. Login to the CyVerse |Discovery Environment|.

  2. Click this link to open the
     |pigz-2.3.4 (Compress multiple files with gzip parallely)| App or click
     the |apps icon| (Apps icon) and search for the "pigz-2.3.4" App.

  3. Under "Input(s)" select the individual files (FastQ/SFF/BAM) to compress
     your files.

  4. Click 'Review and Launch ' to compress the file and click the (Analysis
     Icon) button to monitor job status and view results. Once all files are compressed you may wish to gather them into a single folder to begin your submission.

    .. tip::

      Each file (e.g. read_R1.fastq) must be *individually* compressed (e.g.
      read_R1.fastq.gz)

Create SRA submission package and add sequence data
----------------------------------------------------
An SRA submission requires that your sequencing data are organized in a specific
structure of folders and subfolders. It will be helpful if you are familiar
with SRA terminology:

  .. tip::

   **SRA Terminology**

   Adapted from NCBI:

    - **BioProject**: A BioProject is a collection of biological data related to
      a single initiative, originating from a single organization or from a
      consortium.
    - **BioSample**: The BioSample database contains descriptions of biological
      source materials used in experimental assays. Different experimental
      conditions, tissue types, etc. would typically be different BioSamples.


   Your submission will contain the following folders and data:

   .. list-table::
     :header-rows: 1

     * - Folder
       - Description
       - Contents
       - Metadata
     * - BioProject (One per submission)
       - This is the top-level folder and will contain all
         other folder and data.
       - One or more BioSample folders
       - A BioSample Metadata template will specify details like the project
         summary, submitter/investigator information, etc.
     * - BioSample (One or more per submission)
       - BioSample folders, one for each experiment/
         tissue type, etc.
       - One or more BioSampleLibrary folders
       - A species/tissue specific metadata template will describe biological
         information about the sample (e.g. sex, collection location, etc.).
     * - BioSampleLibrary (One or more per submission)
       - These folders will contain the sequencing data.
         Each replicate will have its own library folder.
       - Each BioSampleLibrary folder will contain one either one (single-end)
         or two (paired-end) sequence files.
       - A BioSampleLibrary metadata template will describe information about
         the sequencing run


  1. Login to the CyVerse |Discovery Environment|.

  2. Click on the |data_icon| (Data Icon) to open a data window. In your home
     directory (or any directory your own) create the submission folder; Click
     on the folder button, and create a folder (e.g. name of your project).

  3. Inside your new folder, create the following folders:

      - A top-level folder called **'BioProject'** (this will contain
        additional
        folders for each of your samples)
      - Inside the BioProject folder, create one or more
        **'BioSample_descriptive_name_or_number'** folders. These
        folders will be for each of your samples (e.g., wild type, control),
        each of which may have one or more sequencing runs associated with them.
      - Inside each BioSample folder, create a **'BioSampleLibrary'** folder.
        These will contain all the FastQ reads associated with individual replicates.

     .. tip::

       In our |Example submission| we have two experimental conditions with 3 sequencing replicates each so 2 BioSamples and 3 libraries in each BioSample were created. See the **'BioProject_SRA_Quickstart'** folder in the |Example folder| to see how everything gets organized (e.g. BioProject folder > BioSample > BioSampleLibrary > fastQ sequence reads)

  4. Place your sequence files in the appropriate library folders.


  5. Examine the |Example folder| for reference and ensure your sequencing
     samples are appropriately organized.

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
