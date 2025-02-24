.. _template_fb:

====================================================================
Creating templates using eformsign for Microsoft Office
====================================================================

----------------
About Templates
----------------

Templates are **electronic documents** used for the eformsign service. They are e-documents transformed from existing
paper forms such as applications, contracts, and agreements. You can create and upload templates in the eformsign service with its **Web form designer** or **eformsign for Microsoft Office**. 


.. tip::

   Using Templates is useful for documents that need to be sent often or regularly. If the tempate is registered once, you don't have to upload the document file whenever you need to sent the document. You can just easily create and sent documents using the template. 


.. note::

   For information about setting and managing templates with Web form designer, please refer to `Creating templates using Web Form Designer <chapter6.html#template_wd>`__.



To create and send electronic documents via eformsign, you have to create a template first which can be transformed into an e-document.

**How to create a template with eformsign for Microsoft Office**
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

To create a template with eformsign for Microsoft Office, you must first download eformsign for Microsoft Office.

.. note::

   For more information about eformsign for Microsoft Office, please refer to `Introduction to eformsign for Microsoft Office <chapter5.html#formbuilder>`__.

MS Office files such as Word, Excel, and PowerPoint can be uploaded as a template using the eformsign Microsoft Office Add-in.

1. Open a Word, Excel, or PowerPoint file.

2. Go to the **eformsign** ribbon menu in the file.

3. Choose a location you want to add a field.

4. Select a field type.

5. Adjust the size and position of the field.

6. Click the **Execute** button to preview the field.

7. Click the **Upload** button to upload the file as a template.

8. Click **Create template** and set details for the template.

.. figure:: resources/en-formbuilder-execute.png
   :alt: Formbuilder menu




**Template settings**
You can set the details for the template.

-  **General**
   Set the template name, abbreviation, document name, document number, etc.

-  **Set permissions**
   Grant members or groups the permission to use and edit the template and to create documents from it and manage them.

-  **Workflow**
   Sets the workflow for the document from its creation to completion.

-  **Field**
   Sets the default values and auto-filled values for fields.

-  **Notification settings**
   Sets the recipients, and the content of the notification messages for notifying changes in the status of documents created from the template.

.. _workflow:

--------------------
Workflow Overview
--------------------

A **workflow** is a document process from its creation to completion.

The workflow for each template can be set by template managers by going to **Template settings** > **Workflow**.

By default, all workflows have **Start** and **Complete** steps. You can add as many **Recipient**, and **Need to view** steps as you want for each workflow.

.. figure:: resources/en-workflow-steps-form-builder.png
   :alt: Workflow steps
   :width: 400px

-  **Recipient:**
   Signs and fills out documents.

-  **Need to view:**
   Only views documents.





.. _template_setting:

-------------------
Template Settings
-------------------


You can set detailed configurations for each template you create.

.. note::

   Only the **Company administrator** or **Template managers** can perform this action.

   This action can be performed in web browsers of computers and mobile devices, and also in mobile apps.

**How to go to the template settings screen**

1. In the sidebar menu, click the **Manage templates** menu.

2. Click the name or settings icon (|image1|) of the desired template.

   |image2|

.. _general_fb:

General
~~~~~~~~

.. figure:: resources/en-manage-template-settings-fb.png
   :alt: Template Settings > General
   :width: 350px


**Configure basic settings for the template**
----------------------------------------------------


Set basic information about the template including the template name, category, validity period, etc.

**Form file**
   The name of the form file which is uploaded to eformsign from Word, PowerPoint, or Excel using eformsign for Microsoft Office. To change the form file name, you need to change the file name of the uploaded Word, PowerPoint, or Excel file and then update it.

**Template name**
   The template name will be displayed in the **Manage templates** and **New from template** pages.

   The recommended length of the template name is about 11 characters, including spaces. If the name is longer than 11 characters, you can see the full name by hovering the mouse over the name.



**Template abbreviation**
   A short name that briefly descries the template. It is recommended to use two or three words.

   **Template abbreviation** can be used in the document number, document name, mail template, etc.

   .. figure:: resources/en-manage-template-settings-document-naming-abb.png
      :alt: Template Abbreviation


**Category**
   Category is used to sort templates by type. With the category name, you can filter templates in the **Manage templates** menu, and can filter documents in the **Documents** menus and the **Manage documents** menu. You can choose from an existing category or create a new category by entering a new name.

   You can set multi-level categories with a separator ( **/** ). For example, if you set a category as **HR Team/Vacation**, the Vacation category in the HR category is created.

**Description**
   Enter additional comments about the template. This description is displayed under the template name in the **New from template.**

**Template availability**
   Sets the time period in which documents can be created from this template. By default, the start date is set to the uploaded date and you can change the date.

   When **No expiry date** is checked, documents can be created without a time limit. If you check **No expiry date**, documents can be created without a time limit. If you uncheck it and set the date, then documents can be created from the template up to that date.

**Document settings**
----------------------------------

Configure additional settings including document naming rules for documents created from the template.

**Document naming rule**
   Sets the document name when creating the document from the template. If a document naming rule is not set, the template name will be the document name.

**Allow document name change**
   If **Allow document name change** is checked, the document creator can change the document name.

**Generate a document number**
   If **Generate a document number** is checked, documents are automatically numbered. You can select the document number format and the workflow step in which document numbers are generated.

   |image3|

**Skip pop-up window when sending documents**
   Use it when many documents are created and submitted. If this option is unchecked, a pop-up window for entering a message will appear when sending a document. When **Skip pop-up window when sending documents** is checked, the pop-up window does not appear and the page proceeds to the next step.


**Document retention period**
   Sets the retention period for documents created from the template. If this is not set, then the document retention period for the template follows the company-wide settings.

   .. note::

      The retention period can be set from a minimum of 1 day to a maximum of 15 years.

      **Maximum retention period by year/month/day**
      
      - 15 years
      - 180 months
      - 5,475 days

      💡For information on how to set the company-wide document retention period, go to `Document retention period <chapter2.html#retention>`_.




.. _document_naming:

General > Setting the Document Naming Rule
----------------------------------------------------

In **Template settings**, you can set the document naming rule for documents created from a template.

You can make a piece of information entered into a document or document-related information to be automatically entered into the document name. If you set the document naming rule, then the document name is automatically entered based on the information of the document.
As well, you can see this name in all document pages (In progress, Action required and Completed) and the **Manage document** page.

.. note::

   Only the **Company administrator** or **Template managers** can perform this action.

.. figure:: resources/en-manage-documents-document-list.png
   :alt: Manage Documents > Documents List
   :width: 700px


**How to set the document naming rule**
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: resources/en-document-naming-rule.png
   :alt: Template Settings > Setting the Document Naming Rule
   :width: 600px


1. In the sidebar menu, click the **Manage templates** menu.

2. Click on the settings icon (|image4|) of the desired template to go to the **Template settings** page.

3. Enter the desired naming rule in the **Document naming rule** field in the **General** tab by adding reserved words.

4. Click the **Save** button on the top right corner to save the changes.



.. _reserved_words:

**How to use reserved words Templates**
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^


.. figure:: resources/en-document-naming-rule-reserved.png
   :alt: Setting Document Naming Rules Using Reserved Words


-  **Component ID**\ : Adds a piece of information in the document into the document name.

   Click the **Add reserved word** button, and click **Component ID**\  to display the list of field IDs and then select the desired field ID. The information in that particular field will be added to the document name.


-  **General info**\ : Adds document-related information into the document name.

   Click **General info**\  to display the list of information type and then select the desired information. Information types are as follows.

   +-----------------------+-----------------------------------------------+
   | Information types     | Description                                   |
   +=======================+===============================================+
   |Current_date           | The date in which the document is created     |
   |                       | (e.g. Feb 20, 2020)                           |
   +-----------------------+-----------------------------------------------+
   |Current_time           | The time in which the document is created     |
   |                       | (e.g. 02:59 pm)                               |
   +-----------------------+-----------------------------------------------+
   |Current_datetime       | The date and time in which the document is    |
   |                       | created (e.g. Feb 20, 2020, 02:59 pm)         |
   +-----------------------+-----------------------------------------------+
   |Creator_ID             | The ID of the member who created the document |
   +-----------------------+-----------------------------------------------+
   |Creator_name           | The name of the member who created the        |
   |                       | document                                      |
   +-----------------------+-----------------------------------------------+
   |Creator_dept           | The department of the member who created the  |
   |                       | document                                      |
   +-----------------------+-----------------------------------------------+
   |Creator_company Name   | The name of the company in which the member   |
   |                       | who created the document belongs to           |
   +-----------------------+-----------------------------------------------+
   |Template_name          | The template name entered in Template         |
   |                       | settings > General                            |
   +-----------------------+-----------------------------------------------+
   |Template_abbreviation  | The template abbreviation entered in Template |
   |                       | settings > General                            |
   +-----------------------+-----------------------------------------------+
   |Document_ID            | A unique ID for the document, represented by  |
   |                       | a 32-digit alphanumeric combination           |
   +-----------------------+-----------------------------------------------+
   |Document_number        | The number generated when the Generate a      |
   |                       | document number option is enabled in General  |
   +-----------------------+-----------------------------------------------+
   |Company                | The company name entered in Manage company >  |
   |                       | Company profile                               |
   +-----------------------+-----------------------------------------------+
   |Company_address        | The address entered in Manage company >       |
   |                       | Company profile                               |
   +-----------------------+-----------------------------------------------+
   |Company_contact_no     | The contact information entered in Manage     |
   |                       | company > Company profile                     |
   +-----------------------+-----------------------------------------------+
   |Company_registration_no| The business registration number entered in   |
   |                       | Manage company > Company profile              |
   +-----------------------+-----------------------------------------------+
   |Company_homepage       | The homepage URL entered in Manage company >  |
   |                       | Company profile                               |
   +-----------------------+-----------------------------------------------+

.. tip::

   Check the status of the **Allow document name change** field.

   Even if the document naming rule is set, if the **Allow document name change** option is checked, the document creator can arbitrarily change the document name. If you do not want the document name to be changed, then make sure to uncheck the **Allow document name change** option.

.. figure:: resources/en-allow-document-name-change.png
   :alt: Checking the Allow Document Name Change Option


.. _docnumber_fb:

General > Generating and Viewing a Document Number
----------------------------------------------------------

You can set a document number for documents created in eformsign. You can set it so that a document number is generated automatically for each template, and can select one of four document numbering formats. The document number can be generated in the document using the document field. You can also see a separate column in the document list and search documents by the document number.

**Generating a document number**
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^


.. figure:: resources/en-generate-document-number.png
   :alt: Setting a Document Number
   :width: 600px


1. In the sidebar menu, click the **Manage templates** menu.

2. Click on the settings icon (|image5|) of the desired template to go to the **Template settings** page.

3. Tick the **Generate a document number** checkbox in the **General** page.

-  **Selecting a document numbering rule**

   .. figure:: resources/en-generate-document-number-select.png
      :alt: Selecting a Document Numbering Rule



   **▪ Serial number**
      Generated in the format of the document creation order

      E.g. 1, 2, 3...

   **▪ Year_serial number**
      Generated in the format of the document creation year + document creation order

      E.g. 2020_1, 2020_2...

   **▪ Template_serial number**
      Generated in the format of the template abbreviation + document creation order

      E.g. Application 1, Application 2...

   **▪ Template_year_serial number**
      Generated in the format of the template abbreviation + document creation year + document creation order

      E.g. Application 2020_1, Application 2020_2...

- **Choosing when to number a document:**

   ▪ **Start**
      A number is generated when a document is created.

   ▪ **Complete**
      A number is generated when a document has been completed after going through all the steps in the workflow.

4. Click the **Save** button at the top right corner of the page to apply your changes.

**Viewing a document number**
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

A document number can be viewed directly on a document using the document field and can also be viewed in the document list.

-  **Viewing a document number directly on a document**

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

   You can generate a document number directly on a document by using the document field in eformsign for Microsoft Office.

   1. Open a file in Word, Excel, or PowerPoint.

   2. Add the document field in the location where the document number will be displayed.

   3. Click the **Upload** button to upload the file on eformsign.

   4. In **Template settings > General,** tick the **Generate a document number** checkbox.

   5. Select a document numbering rule.

   6. Click the **Save** button to save the settings.

-  **Viewing a document number in the document list**

++++++++++++++++++++++++++++++++++++++++++++++++++++++

   .. figure:: resources/en-completed-document-box-docno.png
      :alt: Completed - Document List
      :width: 700px


   .. figure:: resources/en-completed-document-list-docno-column.png
      :alt: Completed - Document List - Document Number
      :width: 700px


   A document number can be viewed in the Documents menus (In progress, Action required, and Completed), and the Manage documents menu (requires document management permission).

   1. In the sidebar, click the **Completed** or **Manage documents** menu.

   2. Click the column settings icon at the top right corner of the page.

   3. Check **Document number** in the column list.

      |image6|

   4. Check that **the document number** column is added.

-  **Searching for a document using a document number**

++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

   |image7|

   You can search a document by its document number via advanced search.

   1. Go to the **Completed** or **Manage documents** page.

   2. Click the **Advanced** button at the top right corner of the page.

   3. Select **Document number** among the search conditions.

   4. Type in the word or number to be searched.

   5. View the search results.

.. _auth_fb:

Set Permissions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can set the permissions for the template usage, template editing and document management.

.. figure:: resources/en_template-setting-set-permissions.png
   :alt: Template Settings > Set Permissions
   :width: 700px



**Template usage**
This permission is needed to create documents from the template, and you can select **Allow all** or **Group or member** to allow all the members or some members in the company to create documents from the template.

**Template editing**
This permission is needed to edit the template, and you can select **Members** to allow editing the template. 

**Document management**
You can select groups or members to open documents created from the template, void completed documents, or remove documents permanently. You can grant permission for all or some of the three options described below.

-  **Open all documents** (default): Default permission granted to a document manager and gives the permission to open all documents to authorized groups or members.

-  **Void documents** (optional): Permission for voiding completed documents when requested by the document creator.

-  **Remove documents** (optional): Permission to permanently remove documents from the system.

.. _workflow_fb:


Workflow Settings
~~~~~~~~~~~~~~~~~~~~~~~~

You can create or modify the workflow of the template by clicking the **Workflow** tab in the **Template settings** page.

.. figure:: resources/en-template-settings-workflow-fb.png
   :alt: Template Settings > Workflow
   :width: 700px



**Adding steps to the workflow**
-----------------------------------------

1. Go to the **Workflow** configuration page by clicking the **Workflow** tab.

2. Click the add button (|image8|) which is in between the **Start** and **Complete** steps.

3. Select the type of recipient which you want to add.

.. figure:: resources/en-template-settings-workflow-adding-steps.png
   :alt: Template Settings > Workflow
   :width: 700px



   .. tip::

      You can add as many steps as you want. You can adjust the order of steps by clicking and dragging a workflow step.
      To delete a step, click **-** on the right side of the step button.


.. tip::

  **Merge workflow steps**

   You can merge multiple workflow steps into one so that documents can be sent to all recipients at the same time, regardless of the signing order. You can also split workflow steps that are merged together.

  **Instructions:**

   1. Go to Manage templates > Template settings> Configure > Workflow.

   2. Click the workflow step you want to merge with (when merging two steps, you must click the bottom one).

   3. Click the Merge signing order icon displayed at the top left corner of the selected workflow step. The bottom and top workflow steps will be merged together.

   4. You can also split workflow steps by clicking the same icon.


   .. figure:: resources/merge_workflow_steps.png
      :alt: Merge workflow steps (before)

   .. figure:: resources/merge_workflow_steps2.png
      :alt: Merge workflow steps (after)

   ❗ Note that this feature is available only in New from template. For New from my file, the feature is planned to be available in the future.



**Configuring the details of each workflow step**
------------------------------------------------------


You can click a step to set the details such as **Properties** and **Manage items** for each workflow step.

-  In **Properties**, you can configure the details of the step including the step name and recipients.

-  In **Manage items**, you can set the fields in which the recipient has access to or is required to fill in.

   .. figure:: resources/configure-details-of-each-step.png
      :alt: Workflow > Manage items


++++++++++++++++++++++++++++++++++++++++++++++++++++++++

**Start: Step for creating a document**


   .. figure:: resources/steps-for-creating-document.png
      :alt: Workflow > Start step

   -  **Step name**: Change the name of the step. The default name is 'Start'.

   -  **Limit the number of documents**: Set the maximum number of documents that can be created from the template.

   -  **Create documents from URL**: Create a public link for external recipients (non-members) to review and sign documents directly via URL without the need to login to the eformsign service.

   -  **Document creator information**: Require users to enter their information (name, email, etc.) before they open documents created from URL.

   -  **Do not allow duplicate documents**: Prevent the creation of duplicate documents and allows to select a field for determining whether a document is duplicated or not.

   -  **Identity verification**: Require document creators to verify their identity before opening documents created from URL.

      - **Require email/SMS verification:** Send a 6-digit verification code to the recipient's email or mobile phone number. The recipient can enter the verification code into the verification window to open the document.

   .. tip::

   If both the Document creator information and Identity verification options are enabled in a template's workflow, then when document creators create a document from this template, they need to enter their information and verify their identity to create documents. Note that the document creator’s information and identify verification will be displayed in document inboxes and on the audit trail certificate.


   - **Approved domain IP**: Set to allow creating documents only form approved domains or IPs.

   -  **Block automated document generation by bots**: Require users to tick the reCAPTCHA check box before submitting documents to prevent bots from auto-generating documents.

   .. note::

      **Block automated document generation by bots**

      By selecting this option, when a person submits a document after creating a document via URL, the reCAPTCHA feature is dispalyed on the Submit document pop-up. The person can submit the document after ticking the "I'm not a robot" check box. 

      .. figure:: resources/URL-option-recaptcha.png
         :alt: reCAPTCHA
         :width: 250px

      ❗Disabling this option allows bots to mass-generate documents from the document URL, resulting in excessive charges.

.. tip::

   **How to generate QR code when using the 'Create documents from URL' option**

   When creating a signing link by using the 'Create document form URL' option, you can generate a QR code instead of a signing link.  You can upload the QR code image on a website or share it with others so the people can create and submit documents by scanning the image using the camera on a mobile device.

   Select the **Create documents from URL** option in the Start step of the workflow and click the
   **Generate QR code** button to download the image file.

   
   .. figure:: resources/en-workflow-step-start-QRcode.png
      :alt: Workflow > Generate QR code
      :width: 400px


++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

**Recipient: Step for signing or filling out a document**



.. figure:: resources/en-workflow-participants-properties.png
   :alt: Workflow > Participant step properties
   :width: 700px

-  **Step name**: Change the name of the step. The default name is 'Start'.

-  **Notification**\: Select how recipients can receive notifications and edit their content. 

   - By default, notifications are sent by email. You can also select SMS to send notifications via text messages.

   - **Edit notification message:** You can edit the notification message for each step.  

-  **Document expiration**\: Set the time period in which documents can be sent by the recipient of the step. If the time period is set to 0 day 0 hour, then there is no document expiration. No document expiration is only available for members.  
   

-  **Automatically fills in the recipient's contact info**\: When sending documents to a recipient, this option allows the name and contact of the recipient to be filled in automatically based on the information the recipient enters into the document.


-  **Identify verification**\: Require non-member recipients to verify their identity when opening the document.   

   - **Require document password**\: Set a verification password that recipients must enter before opening the document. The password can be the recipient name, a value entered directly by the sender, or the value of a field in the document.

            .. figure:: resources/en-doc-require-doc-password-setting.png
               :alt: Require document password
               :width: 400px    
      
   - **Require email/SMS verification**\: Require recipients to verify their identity using email/SMS. A 6-digit code will be sent to recipients' email address/mobile number and the recipients must enter the code in the identity verification window.
      
-  **Hide files or sheets:** Allows you to choose which files/sheets in the document are hidden from the recipient, if the form consists of two or more files. This option cannot be applied to company members.

-  **Disable the decline feature:** Does not allow recipients to decline documents.

.. note::

   **Selecting recipients in a workflow step**

   For any given step other than Start and Complete, you can choose to pre-select recipients or choose to allow the sender to select recipients before sending a document.

   .. figure:: resources/en-workflow-participant-selected.png
      :alt: Workflow > Recipients
      :width: 700px   

   -  **Sender can add/skip recipient**: Allows the sender to enter the contact information of the recipients before sending the document. If the sender does not enter the contact information, this step is skipped.

   -  **Sender needs to add recipient**: Requires the sender to enter the contact information of recipients before sending the documents. If the sender does not enter the contact information, the document is not sent.

   -  **Group or member**: Allows you to pre-select recipients. You can only select groups or members in your company.

   -  **Recipient of a previous step**: Allows you to select the person of a previous step including the Start step.



.. _hide:



**How to hide files in a document**
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. tip::

   
   **Using the 'Hide files or sheets option'**

   If you add multiple files to a document, you can hide certain files from recipients in a workflow step. If you upload multiple files to a document, then the **Hide files or sheets** option appears in the **Properties** tab of workflow steps in **Template settings** where you can choose to hide or show each file.
   

   ❗Note that the 'Hide files or sheets' option is only available when sending a document to non-member recipients.

   **Instructions**

   1. Go to **Sidebar menu  Manage templates**.
   2. Click the **Settings icon (⚙)**\ of the desired template.
   3. Go to **Configure > Workflow**.
   4. Select the desired **recipient** step. 
   5. Select the **Hide files or sheets** option in **Properties** on the right. 
   6. For each file or Excel sheet, select one of the options below.

      - **Required:** The file or sheet is shown to the recipient.

      - **Optional:** The document creator can choose whether to show or hide the file or sheet to the recipient.

      - **Hide:** The file or sheet is hidden from the recipient.

   .. figure:: resources/en-hide-setting.png
      :alt: Hide files or sheets
      :width: 500px



**Complete: Step in which a document is finally completed**
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++


   .. figure:: resources/complete-step-en.png
      :alt: Complete step
      :width: 800px

   -  **Step name**\: Change the name of the step. The default name is ‘Complete’.

   -  **Backup completed documents in external cloud storages**: Allow the document to be stored in external cloud storages connected to eformsign by the administrator or company managers.

   -  **Timestamp**: Allow the completed document to be timestamped which proves that the document remains unchanged since that time. This feature will incur an extra charge.


.. _field_fb:

Field
~~~~~~

In the **Field** menu, you can set the default values or auto-fill values for fields in the template, and adjust the order of the fields.

.. figure:: resources/en-template-settings-field-fb.png
   :alt: Template Settings > Field
   :width: 700px


You can set the default value of a field to be the value saved in company/group/member information in **Manage custom fields**. You can also choose it to be the value entered recently or a value entered manually.

.. tip::

   **How to configure auto-fill**

   You can save information that are frequently entered into a document so that they can be used for auto-filling later.

   For example, you can pre-save information about your company or group (such as department name, leader, and representative number) and information about the document creator (including name and contact details). You can add items for related fields and set the default values in **Manage company > Manage custom fields**.

   1. In the **Manage custom fields** screen, add a field.

   2. Go to the **Manage templates** menu.

   3. Click the **Template settings** icon.

   4. Go to the **Field** menu.

   5. Enter the default value for the field that you want to be auto-filled.

   6. After completing all the settings, click the **Save** button.

.. _noti_fb:


Notification Settings
~~~~~~~~~~~~~~~~~~~~~~~~~

You can select the recipients of status notification messages, and view and edit the messages for documents created from the template.


**Document status notifications**

You can select who will receive status notifications for documents created from the template. You can also preview the following notification message types: approved, reviewed and signed, rejected, voided, and corrected. As well, you can edit and preview the notification messages for completed documents.

.. figure:: resources/template-setting-notification-channel.png
   :alt: Notification settings


.. note::

   When the **Document creator** option is checked but the **Step handler** option is unchecked, a status notification is sent to the person who originally created the document.

   When the **Document creator** option is unchecked but the **Step handler** option is checked, status notifications are sent to people who have processed the document before the current step, except the document creator.

   When the **Document creator** and **Step handler** options are both checked, status notifications are sent to both the document creator and the people who have processed the document before the current step.

   When the **Document creator** and **Step handler** options are both unchecked, no notifications will be sent for that status.



   .. caution::

      ❗When the **Document creator** option for **When the document is completed** is checked and an external recipient creates and submits a document via a URL, the external recipient must enter his/her email in which a notification will be sent to when the document is completed.


**Editing document status notifications**

.. figure:: resources/template-setting-notification-edit2.png
   :alt: Editing document status notifications
   :width: 600px


- **Select notification template:** The document status notification template is set to the default template, but you can change it to another template if you create one. For information on how to create a new notification template, refer to `Notification Template Management <chapter9.html#notification-template>`_.  

- **Email title:** Sets the title of the email sent when a document is completed.

- **SMS message:** Sets the message when a document completion notification is sent via SMS. A link for viewing the document is sent together with the message.

.. note::

   The message size can be a maximum of 65 bytes (65 characters).

- **Files attached & Method:** Select the files to be send together with the document completion notification and select the filees to be attached.

   - **Download link:** A download link button is included in the email or SMS of a completed document, and opens a document viewer page when clicked. In the viewer page, you can view and download the document.

   - **Attachment:** PDF file(s) are included in the email. However, if the size of the document exceeds 10 MB or file(s) are sent via SMS, then a download link is included instead. 

   .. caution::

      If you send an email notification using the **Attachment** method, the completed document is included in the email. Therefore, even if is configured to require the recipient to go through identity verification, the recipient can still view and download the document.

- **Edit body:** Edits the body of the notification message.



---------------------------
Menus for Each Template
---------------------------

Go to the **Manage templates** page, click the menu icon (|image23|) right next to the template name to see the menus that can be set for each template.

|image24|

-  **Duplicate**: Duplicates the template. The template's file and detailed settings for the template will be duplicated. You will have
   a chance to change and save the detailed settings before the template is duplicated.

-  **Delete**: Deletes the template. Once a template is deleted, you can no longer create documents from that template.

-  **Download file**: Click **Download file** to download a form in the format is was uploaded (e.g. Word, Excel, etc.).

-  **Deactivate**: When a template is deactivated, it will not be shown in the **New from template** page for other members.

-  **Change owner**: You can change the owner of the template. By default, the person who created the template is automatically assigned as the template owner. If you want to make changes later, you can change the owner to another member by clicking this menu. The new template owner can be selected among members who have permission to manage templates.

   |image25| 



---------------------
Search Templates
---------------------

In the **Manage templates** page, you can lookup and search templates by template category.

|image27|

**① Lookup Templates**
   Click the box **(1)** to lookup templates by template status and category. Click **X** to return to view all categories.

   By default, templates are saved in the Sample category. You can create categories in **Template settings > General.**

**② Search templates**
   You can search templates by entering keywords for the template name and category name.

**③ Sort**
   You can select the template sorting order in ascending or descending by template name or category.

.. |image1| image:: resources/config-icon.PNG
   :width: 25px
.. |image2| image:: resources/en-manage-template-settings-.png
   :width: 700px
.. |image3| image:: resources/en-generate-document-no.png
.. |image4| image:: resources/config-icon.PNG
   :width: 20px
.. |image5| image:: resources/config-icon.PNG
   :width: 20px
.. |image6| image:: resources/en-document-number-list.png
.. |image7| image:: resources/en-manage-template-search-advanced.png
   :width: 600px
.. |image8| image:: resources/workflow-addstep-plus-button.png
   :width: 20px
.. |image9| image:: resources/en-template-settings-workflow-add-steps-fb.png
   :width: 700px
.. |image10| image:: resources/en-template-settings-workflow-order-fb.png
   :width: 500px
.. |image11| image:: resources/en-template-settings-workflows-item-fb.png
   :width: 700px
.. |image12| image:: resources/en-template-settings-workflow-started-fb.png
   :width: 700px
.. |image13| image:: resources/en-template-settings-workflow-approver-fb.png
   :width: 700px
.. |image14| image:: resources/en-template-settings-approver-display-name.png
   :width: 250px
.. |image15| image:: resources/en-template-settings-workflow-internal-fb.png
   :width: 700px
.. |image16| image:: resources/en-template-settings-workflow-external-fb.png
   :width: 700px
.. |image17| image:: resources/workflow-step-external-recipient-property-pw.png
   :width: 400px
.. |image18| image:: resources/template-fb-setting-workflow-outsider-1.png
   :width: 700px
.. |image19| image:: resources/en-template-settings-workflow-completed-fb.png
   :width: 700px
.. |image20| image:: resources/en-template-settings-edit-notification-messages.png
   :width: 400px
.. |image21| image:: resources/en-template-settings-edit-notification-messages-popup-fb.png
   :width: 700px
.. |image22| image:: resources/en-template-settings-notification-status.png
   :width: 500px
.. |image23| image:: resources/template-hamburgericon.png
   :width: 10px
.. |image24| image:: resources/en-manage-template-menu-icon.png
   :width: 500px
.. |image25| image:: resources/en-manage-template-menu-icon-change-owner.png
.. |image26| image:: resources/en-manage-template-menu-icon-document-manager.png
.. |image27| image:: resources/en-manage-template-search.png
   :width: 700px
