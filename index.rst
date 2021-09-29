.. include:: cyverse_rst_defined_substitutions.txt
.. include:: custom_urls.txt

|CyVerse_logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

Submit High-throughput Sequencing Reads to NCBI Sequence Read Archive (SRA)
============================================================================

Goal
----
This workflow enables CyVerse users to make submissions to the |NCBI Sequence Read Archive (SRA)|. A submission included compressed sequenced files
(FASTQ.gz, SFF.gz, and BAM.gz) and an XML metadata file, organized into a
package. If you need to submit an alternative file format (HD5,
SOLiD, and SRF) please email support@cyverse.org

----

.. toctree::
	:maxdepth: 2

	Quickstart home <self>
	Create and organize an SRA submission package <step1.rst>
	Record metadata and associate with SRA submission <step2.rst>
	Validate and submit package to SRA <step3.rst>
	Confirm submission to SRA and fix errors <step4.rst>

Quick Start Maintainer(s)
----------------------------

Who to contact if this quick start needs fixing. You can also email
`learning@CyVerse.org <learning@CyVerse.org>`_

.. list-table::
    :header-rows: 1

    * - Maintainer
      - Institution
      - Contact
    * - Jason Williams
      - CyVerse / CSHL
      - williams@cshl.edu

----


Prerequisites
-------------


.. Note::
  To complete this tutorial, you must upload your FASTQ/SFF/BAM files to the CyVerse Data Store. See the |Data Store Guide| for instructions on how to upload your files (for example, using |Cyberduck|). Also, you will need detailed metadata about the sample being submitted ( e.g. collection/accession information, cell line/tissue metadata, etc.) and the sequencing platform used (e.g. library preparation strategy, sequencing instrument, etc.). These requirements will vary for the organism sequenced and are discussed in detail in the metadata section of this quickstart.


Downloads, access, and services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

*In order to complete this tutorial you will need access to the following services/software*


 .. list-table::
   :header-rows: 1

   * - Prerequisite
     - Preparation/Notes
     - Link/Download
   * - CyVerse account
     - You will need a CyVerse account to complete this exercise
     - |CyVerse User Portal|
   * - NCBI Account
     - Submissions will be sent to NCBI
     - |NCBI Account Registration|
   * - Cyberduck (optional)
     - Standalone software for upload/download to Data Store
     - |Cyberduck|


.. Note::
  **Register for an NCBI Account**

	If you do not have an NCBI account (you can check for an existing account logging in at |NCBI Account|.

Platform(s)
~~~~~~~~~~~

*We will use the following CyVerse platform(s):*

 ..
   #### comment: delete any row not needed in this table ####

.. list-table::
    :header-rows: 1

    * - Platform
      - Interface
      - Link
      - Platform Tour
    * - Data Store
      - GUI/Command line
      - |Data Store|
      - |Data Store Guide|
    * - Discovery Environment
      - Web/Point-and-click
      - |Discovery Environment|
      - |Discovery Environment Guide|

Input and example data
~~~~~~~~~~~~~~~~~~~~~~

*In order to complete this quickstart you will need to have the following inputs prepared*

.. list-table::
    :header-rows: 1

    * - Input File(s)
      - Format
      - Preparation/Notes
      - Example Data
    * - FastQ/SFF/BAM files
      - FastQ/SFF/BAM compressed (.gz/.bz2).
      - For additional details see the |SRA File Format Guide|
      - |Sample truncated sample FastQ files|

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
`Learning Center Home <http://learning.cyverse.org/>`__
