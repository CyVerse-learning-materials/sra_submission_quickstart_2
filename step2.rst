.. include:: cyverse_rst_defined_substitutions.txt
.. include:: custom_urls.txt

|CyVerse_logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_


Record metadata and associate with SRA submission
=====================================================

In this section, you will complete **3 metadata templates** and associate these
metadata with your submission.

- **BioProject**: Metadata describing the overall project
- **BioSample**: Metadata describing the source materials sampled
- **BioSampleLibrary**: Metadata describing the sequencing runs

|sra_8|

.. warning::
  The metadata templates are defined by NCBI. Each field must be completed
  *exactly* as described. Any typos or invalid entries will cause your submission
  to be rejected.


I. Complete BioProject Metadata Template
-----------------------------------------
We will complete the BioProject Creation template to begin a new submission.
You can download a completed |example template|.

  1. Login to the CyVerse |Discovery Environment|.

  2. Click on the |data_icon| (Data Icon) to open a data window. Select (check)
     the BioProject folder you created in the previous section. Then click the
     **More Actions** button, and select metadata. Then click the **More Actions** button again and select **View in template**.

  3. You have two choices to complete the metadata:

      - A) Select **NCBI BioProject Creation** OR **BioProject Creation WGS**
           from the list of templates, and then click **select**

           OR

      - B) Click the Download button, and download a CSV file you can complete
           in any spreadsheet editing program (e.g. Excel).

      We will describe completion of the template for option A.

      .. tip::

         Use **NCBI BioProject Creation** for most sequence data, but use the
         **BioProject Creation WGS** only for whole genome sequencing projects.

      .. tip::

       The download will contain two compressed (.zip) CSV files:

       - **blank.csv**: This is the template to complete
       - **guide.csv**: These are the NCBI specified instructions for the template
         On your local computer

       You can edit the blank.csv template using any spreadsheet editor such as
       Excel. Complete the metadata template according to the instructions in
       the guide; save the metadata file as a .csv file (for Excel we recommend saving as 'CSV UTF-8 (Comma delimited)'). You may name this file whatever you wish we suggest a name other than blank to avoid confusion with other templates.

       **Tips for completing metadata templates**

       **Completing the file name or path field**
       The first column of CyVerse metadata templates is the 'file name or path'
       field. What should be entered is a path to the folder the metadata
       should be applied to. You can get this path from the Discovery
       Environment by selecting any folder or file and going to details to get
       the path.

       When copying your path **ensure the name of your top-level BioProject folder is included**

       **Following Guide Instructions**

       The guide gives additional information about the template including if a
       template field is required, and if specific values (taken from
       controlled vocabulary) must be used. Something to remember include:

       - If an items 'required' value is **TRUE** you must provide a value, or
         enter one of the following null values: 'not collected', 'not
         applicable', or 'missing'.
       - When prompted for an **email address** enter the address associated
         with your NCBI account. Notifications will only be sent to this
         address.
       - The **value type** field indicates if the response is a single line of
         of alphanumeric characters (string), a multiline response, or an
         enumerated
         value (Enum). If a field must be an **Enumerated Value (Enum)** only
         use one of the terms specified in the guide
       - **Dates** must be entered in the order specified by NCBI (e.g. Year-
         Month-Day)

       .. warning::

          Excel and other spreadsheet editors may overwrite information (such as
          dates) with formatting. This makes Excel `notorious for use in
          bioinformatics <https://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-1044-7>`_.
          Double check that dates and other entries in your template are not
          accidentally edited by Excel. When editing, you may use the Formatting
          feature (Format menu > Cells) to ensure your sheet is entirely
          formatted as text

          See the |Data Store Guide| for information about applying your metadata to the Data Store folders.

  4. Complete the selected template then click **Save**; you will be returned
     a window that shows you the completed metadata. You must click **Save**
     again to apply your metadata.




II. Complete BioSample Metadata Template
-------------------------------------------

You will next need to select the appropriate BioSample template (organism/sample
specific) and apply this to **all of your BioSample folders.** Most of the
information may be the same for each BioSample, with differences including
things like treatments and/or tissue sources. You can view a completed |example biosample template|.


  1. Login to the CyVerse |Discovery Environment|.

  2. Click on the |data_icon| (Data Icon) to open a data window. Select (check)
     the BioProject folder you created in the previous section. Then click the
     **More Actions** button, and select metadata. Then click the **More Actions** button again and select **View in template**.

  3. You have two choices to complete the metadata:

      - A) Select a NCBI BioSample template appropriate to your organism - use
          'WGS' templates for whole genome sequencing projects.

           OR

      - B) Click the Download button, and download a CSV file you can complete
           in any spreadsheet editing program (e.g. Excel).

      We will describe completion of the template for option A.

   4. Complete the selected template then click **Save**; you will be returned
      a window that shows you the completed metadata. You must click **Save**
      again to apply your metadata.


   5. Press the back button and/or return to the data window displaying **All**
      of your BioSample folders. Select (check) again the BioSample folder you
      have annotated with metadata. Click **More Actions** and then
      **Metadata** to show a display of the current metadata annotations. Next,
      click **More Actions** and select **Copy Metadata**. You will be shown
      a window where you can select folders to apply the same metadata too.
      Select the other BioSample folders and apply the BioSample template to these folders as well.

      .. warning::

        Step 5 above assumes your other BioSamples are very similar (e.g. the
        same organism). If this is not the case, you may need to apply a separate BioSample template to each BioSample individually.

    6. For each BioSample folder, you will likely need to edit slightly the
       metadata (e.g. sample name, developmental stage) whatever differences
       exists between samples. For each BioSample folder, select the folder(s),
       click **More Actions** and select **Metadata** to view the metadata
       copied and applied in step 5 above. Use the edit (pencil) to edit any
       necessary fields.

III. Complete BioSampleLibrary Metadata Template
----------------------------------------------------

This final template will need to be completed for **every** BioSampleLibrary
folder. You can view a completed |example library template|.


  1. Login to the CyVerse |Discovery Environment|.

  2. Click on the |data_icon| (Data Icon) to open a data window. Select (check)
     the BioSampleLibrary folder you created in the previous section. Then
     click the **More Actions** button, and select metadata. Then click the
     **More Actions** button again and select **View in template**.

  3. You have two choices to complete the metadata:

      - A) Select **NCBI SRA Library** OR **NCBI WGS Library**
           from the list of templates, and then click **select**

           OR

      - B) Click the Download button, and download a CSV file you can complete
           in any spreadsheet editing program (e.g. Excel).

      We will describe completion of the template for option A.

            .. tip::

               Use **NCBI SRA Library** for most sequence data, but use the
               **NCBI WGS Library** only for whole genome sequencing projects.


   4. Complete the selected template then click **Save**; you will be returned
      a window that shows you the completed metadata. You must click **Save**
      again to apply your metadata.


   5. Press the back button and/or return to the data window displaying **All**
      of your BioSampleLibrary folders. Select (check) again the
      BioSampleLibrary folder(s) you have annotated with metadata. Click **More
      Actions** and then **Metadata** to show a display of the current metadata
      annotations. Next, click **More Actions** and select **Copy Metadata**.
      You will be shown a window where you can select folders to apply the same
      metadata too. Select the other BioSampleLibrary folders and apply the
      BioSampleLibrary template to these folders as well.

      .. warning::

        Step 5 above assumes your other BioSampleLibraries are very similar
        (e.g. the same organism). If this is not the case, you may need to
        apply a separate BioSampleLibrary template to each BioSampleLibrary
        individually.

    6. For each BioSampleLibrary folder, you will likely need to edit slightly
       the metadata (e.g. sample name, developmental stage) whatever differences
       exists between samples. For each BioSampleLibrary folder, select the
       folder, click **More Actions** and select **Metadata** to view the
       metadata copied and applied in step 5 above. Use the edit (pencil) to
       edit any necessary fields.

IV. Generate summary metadata file
------------------------------------

We will now generate a file that captures the metadata for the entire
submission. In the next step, we will validate our results. You view an example
of this |submission metadata file|.

  1. Login to the CyVerse |Discovery Environment|.

  2. Click on the |data_icon| (Data Icon) to open a data window. Select (check)
     the top level BioProject folder you created in the previous section. Then
     click the **More Actions** button, and select **Save metadata to file**;
     save the file with a descriptive name and a .xml ending (this make take a
     few minutes to generate).

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
