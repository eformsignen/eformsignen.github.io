.. _webform:

Introduction to Web Form Designer
=================================

Web Form Designer Overview
--------------------------

Web Form Designer You can easily create a template using Web Form
Designer by uploading a PDF file to eformsign in the **Manage
templates** page. After uploading a file, simply click and locate the
basic components available in the left tree menu of Web Form Designer
and set the properties of each component. This is all you need to do to
create a template.

.. note::

   Currently, only PDF files are supported, but other various file
   formats such as Microsoft Office, JPG, PNG, etc. are planned to be
   supported.

.. note::

   In addition to Web Form Designer, eformsign also provides a Microsoft
   Office Add-in feature named **OZ in Office (Form Builder)** which
   allows you to create electronic documents directly in Microsoft
   Office. To use Form Builder, please install the Microsoft Office
   add-in, and refer to `??? <#formbuilder>`__.

1. To create a template, go to the **Manage templates** page by clicking
the **Manage templates** menu in the sidebar.

.. figure:: resources/web-form_1.png
   :alt: Web Form Designer Screen
   :width: 730px

   Web Form Designer Screen

2. To upload a file, simply drag the file onto the **Manage templates**
page or click the **Select a file** button and then upload the file.

.. figure:: resources/web-form_2.png
   :alt: Web Form Designer Screen
   :width: 730px

   Web Form Designer Screen

3. When a file is uploaded, the **Create template** page will be
displayed as follows:

.. figure:: resources/web-form_3.png
   :alt: Web Form Designer Screen
   :width: 730px

   Web Form Designer Screen

Web Form Designer Menu Layout
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Web Form Designer consists of a screen that displays the file, the left
and right panels, and the top bar.

.. figure:: resources/web-form_4.png
   :alt: Web Form Designer Menu Layout
   :width: 730px

   Web Form Designer Menu Layout

1. **Document display screen:** Displays the uploaded file.

2. **Top bar:** Displays the **Design form** step and the **Configure**
   step, and allows you to preview the template with components added.
   It also allows you to go back to the **Manage templates** page where
   you can see the list of templates.

3. **Basic components list:** Provides 14 basic components including
   Text, Multiline, Signature, Check, and Radio components. Also, new
   components including custom and shape components are planned to be
   added.

4. **Properties:** Allows to set the properties of each component after
   adding components such as Signature, Text, and Check by clicking and
   locating them to the document display screen.

Overview of Components
----------------------

Components Components are used to create fields in electronic documents
that users can enter information. Many different components including
Signature, Check, Date, and Text are provided, and each component can be
configured in detail by using the **Properties** tab.

.. figure:: resources/component_web_1.png
   :alt: Adding a component in Web Form Designer
   :width: 730px

   Adding a component in Web Form Designer

Component Types
~~~~~~~~~~~~~~~

The components provided in eformsign are as follows:

-  `Text <#text2>`__\ **:** Components Text Enters short text (usually 1
   to 2 words).

-  `Multiline <#text2>`__\ **:** Components Multiline Enters long text
   with multiple lines.

-  `Signature <#signature2>`__\ **:** Components Signature Enters a
   signature.

-  `Check <#check2>`__\ **:** Components Check Ticks a check box.

-  `Radio <#select2>`__\ **:** Components Radio Selects an item among
   multiple items (can also be set to select multiple items).

-  `Label <#label2>`__\ **:** Components Label Sets the form ID.

-  `Combo <#combo2>`__\ **:** Components Combo Displays a drop-down menu
   that allows you to select an item.

-  `Datetime <#date2>`__\ **:** Components Datetime Enters a specific
   date.

-  `Numeric <#numeric2>`__\ **:** Components number Enters a number.

-  `Toggle <#toggle2>`__\ **:** Components Toggle Switches to another
   value if two or more values are entered.

-  `Camera <#camera2>`__\ **:** Components Camera Takes a photo using a
   camera or selects a photo from an album in devices with a built-in
   camera (e.g. smartphone, tablet, etc.). Selects an image file in
   devices without a camera (e.g. desktop PC).

-  `Voice <#record2>`__\ **:** Components Voice Records audio in devices
   with a voice recording function.

-  `Attachment <#attach2>`__\ **:** Components Attachment Attaches a
   file.

-  `Document <#document2>`__\ **:** Components Document Enters the
   document number or ID in the document itself.

Setting Properties for Each Component Type
------------------------------------------

All components have common and unique properties. When you click the
component added, the **Properties** tab where you can set and see
detailed properties of each component will be displayed on the right
side of the Web Form Designer screen. Common properties include ID and
Tooltip Text, and the meaning of each property is as follows:

-  **ID:** Components ID Unique key for using an entered value in
   eformsign.

-  **Tooltip Text:** Components Tooltip Text: In Windows, the text in
   the Tooltip Text box of a component is displayed in the form of a
   speech bubble when hovering the mouse over the component. In mobile,
   the text is displayed on the quick type bar when clicking on the
   component.

.. note::

   For the Document component which is for providing information,
   Tooltip Text is not provided.

The description of each component is as follows.

.. _text2:

Text and Multiline
~~~~~~~~~~~~~~~~~~

Components Text Components Multiline Both Text and Multiline components
are used to create text fields. The Text component is suitable for short
text with 1 to 2 words, and the Multiline component is suitable for long
text with more than 1 line.

**Component Properties**

.. figure:: resources/wfd-text-component-properties.png
   :alt: Setting Text and Multiline Component Properties
   :width: 250px

   Setting Text and Multiline Component Properties

**① ID**

Enters the ID of the Text/Multiline component. For example, the ID of
the component in which John Doe, Jane Doe, etc. are entered can be named
‘personName’

.. note::

   All components must have an ID. An ID is automatically generated when
   you create a component, but it is recommended to rename it to
   something you can easily recognize. For example, you can rename the
   ID of a component for entering John Doe, Jane Doe, etc. as 'name'. By
   doing so, it is easier to identify components when deciding whether
   to display a field to a specific user when you are configuring the
   Field settings of a template.

**② Max Length**

Sets the maximum length of characters (including space) that can be
entered. The default value is set to ‘0’, and in this case, there is no
limit for the number of characters.

**③ Keyboard Type**

Selects the keyboard type to be used when entering text in the
component. Keyboard Type can only be used in mobile devices such as
smartphones and tablets.

**④ Show Password Characters**

This option can be set only in the Text component. By checking this
option, the password is hidden with the password symbol (●) when
entering text. The password is also hidden with the password symbol in
PDFs, and can only be seen when downloaded in the CSV format.

**④ Tooltip Text**

Displays the description in Tooltip Text when you hover the mouse over a
component.

.. _signature2:

Signature
~~~~~~~~~

Components Signature This component is used for signing a signature on a
document.

Clicking the signature area displays the **Signature** pop-up which
allows you to sign a signature by drawing, entering text, or using a
previously registered signature.

|image1|

**Component Properties**

.. figure:: resources/Signature-component-properties_web.png
   :alt: Setting Signature Component Properties
   :width: 250px

   Setting Signature Component Properties

**① ID**

Enters the ID of the signature component. For example, the ID of the
component can be ‘signerSignature’ for contract signers.

**② Signature Type**

Selects the signature type to be used when signing.

-  **Enter Directly:** Clicking a signature area displays the
   **Signature** pop-up which allows you to sign by selecting one of the
   multiple signing methods which are **Draw**, **Text**, **Mobile**,
   **Stamp**, and **Registered signature**.

-  **Registered Signature:** If the user has already registered a
   signature on eformsign, then clicking a signature area inserts the
   registered signature into the document.

-  **Registered Initials:** If the user has already registered an
   initial on eformsign, then clicking a signature area inserts the
   registered initial into the document.

.. note::

   If you have registered a signature or initial on eformsign, then when
   you click on a signature component, the registered signature/initial
   will be automatically entered into the component. However, if there
   is no registered signature or initial, then a regular **Signature**
   pop-up will be displayed when you click on a signature component.

.. note::

   In some cases, you may need to use a seal or stamp on a document
   rather than your own signature. With eformsign, you can also use a
   stamp image to stamp the signature on a document. To use a stamp
   image when submitting a document, click the **Stamp** tab in the
   **Signature** pop-up, and then select a stamp image and click **OK**.

**③ Signature Pen Thick**

Sets the signature pen thickness.

**④ Signature Pen Color**

Sets the signature pen color.

**⑤ Tooltip Text**

Displays the description in Tooltip Text when you hover the mouse over a
component.

.. _check2:

Check
~~~~~

Components Check The Check component is used to check whether an item is
checked or not. This component is similar to the Radio component, but
the Check component is used for checking the status of an item (whether
it is checked or not) while the Radio component is used for checking
which item among multiple items is checked.

When data is downloaded in the CSV format, the Check component’s input
value is displayed as follows:

-  When the item is checked: true

-  When the item is not checked: false

In Word and PowerPoint, the Check component is shown as a rectangular
shape. Make sure to enter data inside the rectangular shape.

**Component Properties**

.. figure:: resources/check-component-properties-1_web.png
   :alt: Setting Check Component Properties
   :width: 250px

   Setting Check Component Properties

**① ID**

Each Check component must be given a different ID. If multiple check
components are given the same ID, then only the value of the last
component is displayed.

**② Check Style**

You can specify the style of each component in **Component Properties**.
The check box is set as the default style, and you can change it to
another style (radio button or red circle).

The below example shows how check boxes are displayed according to the
selected style.

|image2|

.. _select2:

Radio
~~~~~

Components Radio The Radio component is used for checking which item is
selected among multiple items. When data is downloaded in the CSV
format, the selected item will be displayed.

In Word and PowerPoint, the Radio component is shown as a rectangular
shape. Make sure to enter data inside the rectangular shape.

**Component Properties**

.. figure:: resources/Radio-component-properties_web.png
   :alt: Setting Radio Component Properties
   :width: 250px

   Setting Radio Component Properties

**① ID**

In **Component Properties**, make sure that all the selected radio
buttons are assigned the same ID.

For example, if there are six choices available in a multiple-choice
question, assign ‘question1’ as the ID for all of them. In the example
shown below, the IDs of all the items are set to the same "question 1".

.. figure:: resources/radio-items-should-have-same-ID_web.png
   :alt: Example of Setting a Radio Component
   :width: 730px

   Example of Setting a Radio Component

**② Check Style**

You can choose the style of the Radio component in **Component
Properties**. The default style is the Circle, and you can change it to
another style (check box and radio button).

**③ Multiselectable**

Checking the **Multi-selectable** option allows you to select multiple
items. If you select more than one item, then when data is saved, each
item is separated with a comma (,).

**④ Uncheckable**

Checking the **Uncheckable** option allows you to deselect a selected
item by clicking it again.

**⑤ Tooltip Text**

Displays the description in Tooltip Text when you hover the mouse over a
component.

.. _label2:

Label
~~~~~

Components Label This component is used for setting the form ID of a
document.

**Component Properties**

.. figure:: resources/label_property_web.png
   :alt: Setting Label Component Properties
   :width: 250px

   Setting Label Component Properties

**① ID**

The form ID of the document is automatically generated and displayed. It
can also be changed.

The form ID defined here can be applied when editing the document.

.. _combo2:

Combo
~~~~~

Components Combo The Combo component is used when you need to select one
of the multiple items.

If you click a Combo component, a list of items is displayed as follows:

|image3|

**Component Properties**

.. figure:: resources/combo-component-properties_web.png
   :alt: Setting Combo Component Properties
   :width: 250px

   Setting Combo Component Properties

**① ID**

Enter the ID of the Combo component. For example, the ID of the
component for selecting the favorite color can be ‘Favorite color’.

**② Items**

Enter the items you want. You can separate the items by pressing Enter.

.. note::

   If you want to display a message such as ‘Please select a color’ in a
   combo box in a document for recipients to view, then enter the
   message at the top of the list of items in the combo box and select
   it before sending the document.

**③ Tooltip Text**

Displays the description in Tooltip Text when you hover the mouse over a
component.

.. _date2:

Datetime
~~~~~~~~

Components Datetime This component is used for entering a date. Clicking
the component displays a date selection window where you can select the
date you want.

**Component Properties**

.. figure:: resources/datetime-component-properties_02_web.png
   :alt: Setting Datetime Component Properties
   :width: 250px

   Setting Datetime Component Properties

**① ID**

Enters the ID of the Datetime component. For example, the ID of the
component for selecting the vacation start date can be named ‘Vacation
start date’.

**② Format**

Sets the format in which date will be displayed. The default setting is
date_yyyy-MM-dd.

-  **yyyy:** Displays the year.

-  **MM:** Displays the month. Must be in uppercase.

-  **dd:** Displays the day.

For example, if you want to display the date in the format of
‘15-02-2020’, then enter **dd-MM-yyyy** in the Format field.

**③ Minimum Date/Maximum Date**

Sets the range of dates that can be selected in the component by
specifying the minimum and maximum dates.

**④ Display Today for Empty Value**

Checking this option automatically enters the date (the date in which
the document is opened) when the document is opened. This option is
checked by default when you add a Datetime component. You can change the
date by clicking the component.

**⑤ Tooltip Text**

Displays the description in Tooltip Text when you hover the mouse over a
component.

.. _numeric2:

Numeric
~~~~~~~

Components Numeric This component is used for entering a number.
Clicking the component displays two arrows on the right, and you can
increase or decrease the number by clicking them. In PCs, you can
directly enter the desired number into the component by using a
keyboard. In smartphones and tablets, you can scroll through the list of
numbers and select the one you want.

**Component Properties**

.. figure:: resources/number-component-properties_web.png
   :alt: Setting Numeric Component Properties
   :width: 250px

   Setting Numeric Component Properties

**① ID**

Enters the ID of the Numeric component. For example, the ID of the
component for entering the number of people in a reservation can be
named ‘peopleCount’.

**② Unit of Change**

Enters the unit of number that will increase/decrease the number
whenever the up/down arrow icon is clicked. For example, if the **Unit
of Change** is set to 100, then when you click the up arrow icon (▲),
the number is increased by 100 such as 200, 300, 400, and so on.

**③ Minimum/Maximum Value**

Sets the range of numbers that can be entered into the component by
specifying the minimum and maximum values. For example, for the date of
birth, setting the Minimum Value to 1900, Maximum Value to the current
year, and the Unit of Change to 1. Also, if you enter a value that is
lower/higher than the Minimum/Maximum Value, then the Minimum/Maximum
Value will be automatically entered. For example, if the Maximum Value
is set to 100 and you enter 101, then the number will automatically
change to 100.

**③ Tooltip Text**

Displays the description in the Tooltip Text when you hover the mouse
over a component.

.. _toggle2:

Toggle
~~~~~~

Components Toggle This component is used for indicating a specific
status such as ON/OFF. If you use this component, then the input value
is switched according to a defined order whenever the component is
clicked.

You can change the status to Good or Bad by clicking the components as
follows:

|image4|

**Component Properties**

.. figure:: resources/toggle-component-properties_web.png
   :alt: Toggle Component Properties
   :width: 250px

   Toggle Component Properties

**① ID**

Enters the ID of the Toggle component. For example, the ID of the
component for the first inspection item can be named ‘APT inspection 1’.

**② Items**

Enters the list of items that will be toggled whenever the Toggle
component is clicked. You can separate the items by pressing Enter.

**③ Tooltip Text**

Displays the description in Tooltip Text when you hover the mouse over a
component.

.. _camera2:

Camera
~~~~~~

Components Camera This component is for uploading photos (taken with a
device with a built-in camera such as smartphones and tablets) to a
document. In PCs without a camera, clicking the component displays a
window for selecting the desired image file.

If the size of the selected image is larger than the size of the
component, then it is resized to fit the component.

.. note::

   For devices with a built-in camera, the camera feature will be
   executed. For devices without a camera, a window for selecting an
   image file will be displayed.

|image5|

**Component Properties**

.. figure:: resources/Camera-component-properties_web.png
   :alt: Setting Camera Component Properties
   :width: 250px

   Setting Camera Component Properties

**① ID**

Enters the ID of the Camera component. For example, the ID of the
component that takes the photo of a driver’s license can be
‘driverLicense’.

**② Tooltip Text**

Displays the description in the Tooltip Text when you hover the mouse
over a component.

.. _record2:

Voice
~~~~~

Components Voice This component is used for storing recorded voice. You
can set the maximum recording time and you can also configure the
settings to allow users to only listen to the voice recording.

When you add a Voice component, you can record voice or play a voice
recording as follows:

|image6|

.. note::

   If the recording time limit is set to 1 or more, the recording is
   completed automatically at the time set (unit: seconds).

   In the case of ActiveX viewer, the recording playback UI is supported
   from Windows 8 and later.

   In PCs, the Voice component works only when a voice recording device
   is connected to a PC.

**Component Properties**

.. figure:: resources/record_component_web.png
   :alt: Setting Voice Component Properties
   :width: 250px

   Setting Voice Component Properties

**① ID**

Enter the ID of the voice component. For example, the ID of the
component that plays voice recordings can be named 'Record1'.

**② Tooltip Text**

Displays the description in Tooltip Text when you hover the mouse over a
component.

.. _attach2:

Attachment
~~~~~~~~~~

Components Attachment This component is used for attaching a file to a
document. When attaching a file to a document by using the Attachment
component, the file will be attached at the very end of the document as
a new page.

The types and sizes of files that can be attached are as follows:

-  File type: PDF, JPG, PNG, and GIF

-  File size: Up to 5MB

**Component Properties**

.. figure:: resources/Attachment-component-properties_web.png
   :alt: Setting Attachment Component Properties
   :width: 250px

   Setting Attachment Component Properties

**① ID**

Enters the ID of the Attachment component. For example, the ID of the
component for attaching a resume can be named ‘myResume’.

**② Tooltip Text**

Displays the description in Tooltip Text when you hover the mouse over a
component.

.. _document2:

Document
~~~~~~~~

Components Document This component is used for entering document-related
information in the document itself. You can select either one of the
document ID or document number.

The document ID is a unique document ID assigned in the system, so it
does not require separate settings. For settings related to document
number, upload a template and then go to **Template settings >
General**.

**Component Properties**

.. figure:: resources/document-domponent-properties_web.png
   :alt: Setting Document Component Properties
   :width: 250px

   Setting Document Component Properties

**① ID**

Enter the ID of the Document component. For example, the component ID
can be ‘docNum’ for document number.

**② Document info type**

Select the type of information that will be used.

-  **Document ID:** A unique ID containing 32 digits of alphanumeric
   characters assigned to all documents in the system. E.g.
   0077af27a98846c8872f5333920679b7

-  **Document no.:** The document number set in **Template Settings >
   General.** For information on how to set a document number, please
   refer to `??? <#docnumber_wd>`__.

Configuring Template Settings
-----------------------------

After uploading a file and adding components with Web Form Designer, you
can configure additional settings for documents that will be created
from the template such as the document name, document number, and
workflow.

In the **Design form** screen, click the **Next** button to go to the
**Configure** screen. In the **Configure** screen, you can configure the
five settings shown below.

-  **General:** Sets the template name, abbreviation, document name,
   document number, etc.

-  **Set permissions:** Sets the permissions for who can create
   documents created from the template and who can open, void, or
   permanently remove documents created from the template.

-  **Workflow:** Sets the steps of the document workflow from **Start**
   to **Complete**.

-  **Field:** Sets the field default values, auto-filled values, etc.

-  **Set notifications:** Sets the notification settings for documents
   created from the template.

.. figure:: resources/component_web_2.png
   :alt: The 5 Configuration Tabs in Template Settings
   :width: 730px

   The 5 Configuration Tabs in Template Settings

After configuring all settings, click the **Save** button to save the
settings.

.. note::

   For a detailed explanation of templates, please refer to Chapter 5.
   `??? <#template_wd>`__

.. |image1| image:: resources/signature.png
   :width: 450px
.. |image2| image:: resources/check-component-style-settings.png
   :width: 550px
.. |image3| image:: resources/combo-1.png
   :width: 450px
.. |image4| image:: resources/toggle.png
   :width: 450px
.. |image5| image:: resources/camera1.png
   :width: 400px
.. |image6| image:: resources/record1.png
   :width: 350px
