Introduction to eformsign
=============================

Overview
------------------------

eformsign is an electronic document solution that allows anyone to
easily create electronic documents from paper documents and utilize
various data stored in electronic documents. You can easily create
electronic documents by uploading your PDF files onto eformsign and
converting the files to electronic forms via eformsign's Web Form
Designer feature. You can also use eformsign's Microsoft Office add-in
to create electronic forms from documents created using Microsoft Office
programs including Word, Excel, and PowerPoint.

eformsign allows you to create a workflow for each template according to
your company's business process. You can flexibly set a document signing
process for internal documents requiring approvals as well as for
external documents such as contracts, agreements, and applications.
Furthermore, detailed configurations such as notifications and required
input fields can be set for each workflow step or recipient, and the
progress status of documents is logged as history. Moreover, an audit
trail certificate is provided for the prevention of document forgery and
falsification.

eformsign also provides a bulk send feature, by which users can create
and send multiple documents at once and can minimize repetitive input
with the auto-fill feature. Also, by adding and configuring custom
fields, fields in documents such as company information, group and
member information, recent input value, and date can be automatically
filled in. Furthermore, eformsign allows users to easily manage
companies' members and their permissions, configure detailed
notifications settings for documents, and manage and utilize data
entered in documents by extracting input data.

.. figure:: resources/main_feature.png
   :alt: Key Features
   :width: 700px


The eformsign solution also provides a digital signature feature which
allows you to sign e-signatures on electronic documents.

A digital signature is a signature in electronic form that replaces the
traditional wet-ink signature. Just as when signing a signature on
paper, you need to prove that the signer is you and this is done by
going through an identity verification step. Personal information such
as email, social security number, password, phone number, certificate,
etc. can be used to verify identity.

Digital signatures have become legally binding in phases in the vast
majority of countries around the world. eformsign’s e-signatures are
legally binding for individual-individual and corporation-individual
matters. As well, it provides various additional features for
non-repudiation.

.. note::

   The following describes the legal effect of digital signatures of
   some regions.

   -  South Korea: Digital signatures based on PKI standards have a
      strong legal status, and their legality is not discriminated
      against the wet-ink signatures. According to Section 3.3 of the
      Digital Signature Act, a digital signature other than a certified
      digital signature shall have such an effect of a signature,
      signature and seal, or name and seal, as is agreed between the
      parties concerned.

   -  USA: Under the "technologically neutral" principle, any preference
      to more sophisticated or more secure technologies such as PKI is
      not given. There are many cases of increasing the reliability of
      digital signatures through identity verification or authentication
      services.

   -  EU: Digital signatures are categorized into Qualified Electronic
      Signatures (QES), Advanced Electronic Signatures (AdES), and
      general Electronic signatures, and their legal status is applied
      accordingly, corresponding to the characteristics of each type of
      document.

   -  Japan: With the existence of a Specified Authentication Services,
      a stronger legal effect is given to the digital signature
      authorized by the secretary of the state.

Basic Terms
---------------

The following are some basic terms you should be familiar with before
using eformsign.

-  **Web Form Designer**

   Web form designer is a tool for quickly and easily
   creating electronic forms by uploading existing document files onto
   eformsign. You can create templates by adding components such as
   signature, text box, and check box to documents such as agreements,
   applications, and contracts in the PDF format. You can then create
   documents from templates and send them to recipients to be reviewed
   and signed.

-  **Form Builder**

   Form builder is a tool used to create electronic forms
   by converting Microsoft Office files such as applications, contracts,
   and agreements into electronic forms that contain components such as
   signature and text box. Form builder also uploads the converted
   electronic forms onto eformsign. Form builder is an Microsoft Office
   add-in, and it is shown as a ribbon menu which is called **OZ in Office**.

-  **Dashboard**

   This is the main screen shown when logging into eformsign.
   You can access the sidebar menu by clicking the menu icon(|image1|)
   on the left side of the screen. Each menu may appear differently
   depending on the permissions you have. (The Company administrator can
   access all the menus.)

   .. figure:: resources/dashboard.png
      :alt: eformsign Dashboard Screen
      :width: 700px


-  **Templates**

   Templates This is an electronic form that serves as a starting point
   for a new document. With a template, you can create many documents
   from it. You can create templates by converting existing Microsoft
   Office files using Form builder or by uploading PDF files directly
   onto eformsign.

-  **Document**

   A document can be an electronic document you create and send
   for signature by using a template or an electronic document you
   create and end by upload your file. A document can be create and sent
   for signature by using either one of the **New from my file** menu or
   the **New from template** menu. Any document created like this counts
   as a document created in eformsign.

-  This is a cloud space for storing and viewing
   documents. It consists of the following three menus according to the
   document status:

   -  **Action required:** Shows the list of documents
      that you need to sign, approve, or send.

   -  **In progress:** Shows the list of documents you have
      created or processed but are incomplete.

   -  **Completed:** Shows the list of all the completed
      documents you have created or participated in.

-  **Drafts**

   Shows the list of documents saved as draft when creating a
   document by accessing the **New from my file** menu.

-  **Workflow**

   A workflow refers to the entire document process from when a
   document is created to when it is completed. Template managers can
   create the workflow steps for each template. All workflows have two
   default steps, **Start – Complete**, and can add
   three more types of steps as shown below:

   -  **Approver:** Step in which an approver can approve the document sent by the document creator.

   -  **Internal recipient:** Step in which an internal recipient, a member of the company, can review and sign the document sent by the document creator.

   -  **External recipient:** Step in which a user who is not a member of the company can review and sign the document sent by the document creator (or the internal recipient).

   .. figure:: resources/workflow_new.png
      :alt: Workflow Steps
      :width: 400px


-  **Company Administrator**

   The representative of a company and has full permission to use eformsign.

-  **Company Management Permission**

   Members with company management permission can access company
   management menus, and can manage the company, groups, and members.

-  **Template Management Permission**

   With this permission, a member can access the **Manage templates**
   menu and can manage templates. Managing templates includes creating,
   deploying, editing, and deleting the eformsign templates.

-  **Document Management Permission**

   With this permission, a member can access the **Manage documents**
   menu to view the documents created from each template, approve
   documents requested to be voided, or permanently remove documents
   from the system. Note that the document management permission can be
   set for each separate template.

eformsign Usage Flow
------------------------

To use eformsign, you can either upload a PDF file onto eformsign and
create an electronic form online, or create a form using Microsoft Word,
Excel, or PowerPoint and then upload it to eformsign.

.. note::

   Currently, the method of uploading files and creating forms online
   only supports PDF files. Microsoft Office files, and image files such
   as JPG and PNG are planned to be supported in the near future.

New from my file
~~~~~~~~~~~~~~~~~~~~

You can upload a PDF file onto eformsign and then
create and send a document by adding components such as text, signature,
and date. You can easily and freely send a document by uploading a file,
without the need to create a template. Just simply add components to the
uploaded document, set the workflow in the **Add recipients** step, and
then press the **Start Now** button to send.

Also, before sending a document to recipients, you can temporarily save
it as a draft and then send it later.

.. figure:: resources/use_flow_web.png
   :alt: Usage Flow of eformsign using New from my file
   :width: 700px


Create from template
~~~~~~~~~~~~~~~~~~~~~~~

There are two ways to create a document from a template: uploading a
file on eformsign and creating a template using Web Form Designer, and
creating a template using Microsoft Office using Form Builder and
uploading it on eformsign.

1. **Using Web Form Designer**

   You can create a template by uploading a document
   file (in the PDF format) on eformsign and then adding the components
   you want such as text, signature, and date onto the document.

   After adding components in the uploaded document, configure the
   template settings, workflow, notification settings and deploy the
   template.

   You can then go to the **New document** menu to create a document from a
   template you deployed and send it to recipients

   .. figure:: resources/use_flow.png
      :alt: Usage Flow of eformsign Using Web Form Designer
      :width: 700px



2. **Using Form Builder**

   You can create a template by creating or opening a
   document file in Microsoft Office (Word, Excel, and PowerPoint), and
   then using the ribbon menu (named OZ in Office) to add the components
   you want such as text, signature, and date onto the document.Then,
   you can upload the template you created onto eformsign by clicking
   the Upload button in the ribbon menu.

   After uploading the template, set the template settings, workflow,
   notification settings, etc. and deploy the template.

   You can then go to the New document menu to create a document from a
   deployed template and send it to recipients

.. figure:: resources/use_flow2.png
   :alt: Usage Flow of eformsign Using Form Builder
   :width: 700px


Minimum System Requirements
~~~~~~~~~~~~~~~~~~~~~~~~~~~

The minimum system requirements for Form builder and eformsign are as
follows:

-  **Form builder (OZ in Office)**

   -  **OS:** Windows 7 and later

   -  **MS Office:** Microsoft Office 2010 and later

-  **eformsign and Web form designer**

   -  **OS:** Windows 7 and later, OS X Mavericks and later

   -  **Browser:** Internet Explorer 11 and later, Chrome 49 and later,
      Safari 9 and later

   -  **Mobile OS:** iOS: 6.1.6 and later, Android: 5.0 (Lollipop) and
      later

   .. note::

      Installing the mobile eformsign app is not a mandatory requirement
      to use eformsign.

Use Cases
---------

eformsign can be used for many different cases, including creating
contract, agreement, and application forms. All documents are encrypted
(AES-256 method) and stored in the PDF/A format, which is the
international standard for long-term storage of documents.

Contract Forms
~~~~~~~~~~~~~~

Electronic documents can be used to sign various types of contracts
including employment contracts, purchase/rental contracts, maintenance
contracts, and franchising contracts. By using eformsign, you can record
the history of contract processes, prevent the forgery of documents
through audit trail certificates, and sign hundreds of contracts without
meeting face-to-face with customers or contracting parties.

The e-contract process using eformsign is as follows:

.. figure:: resources/contract_ex1.png
   :alt: E-Contract Process
   :width: 700px


Agreement Forms
~~~~~~~~~~~~~~~

Electronic documents can be used to sign various types of agreements
including privacy policy and consent forms, medical informed consent
forms, parental consent forms, and sublease agreement forms. You can use
various types of devices including smartphones, tablets, and computers
to create and send thousands of agreement forms to recipients at once.

The e-agreement process using eformsign is as follows:

.. figure:: resources/usecase-process.PNG
   :alt: E-Agreement Process
   :width: 700px


Application Forms
~~~~~~~~~~~~~~~~~

Electronic documents can be used to sign various types of applications
including application forms for registrations, quotations, medical
treatments, and purchases. eformsign's workflow feature allows you to
easily send application forms even when an application needs to go
through multiple departments in an organization as well as forwarding
the document to the correct department. You can also send the copy of a
completed document to the parties involved immediately after the
document is completed.

.. figure:: resources/workflow_ex1.png
   :alt: Example Workflow of an Application Form
   :width: 400px


The e-application process using eformsign is as follows:

.. figure:: resources/application_ex1.png
   :alt: E-Application Process
   :width: 700px


.. |image1| image:: resources/menu_icon.png
