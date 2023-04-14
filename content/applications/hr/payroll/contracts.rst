=========
Contracts
=========

To view the empoyee contracts, go to :menuselection:`Payroll --> Employees --> Contracts` from the
top menu.

.. image:: contracts/payroll-contracts.png
   :align: center
   :alt: Navigate to the contracts dashboard in Payroll.

All employee contracts, and their current contract status, are displayed in a default Kanban view.
The default view displays both running contracts and contracts that need action. Expired and
canceled contracts are hidden from the default view.

.. image:: contracts/contracts-overview.png
   :align: center
   :alt: Contracts dashboard view showing running contracts and contracts with issues.

.. note::
   The list of contracts in the *Payroll* application matches the list of contracts in the
   *Employees* application. The only difference is, the *Payroll* application contracts dashboard
   will only display running contracts and contracts needing attention. The contracts dashboard in
   the *Employees* application displays all contracts in a kanban view, organized by their stage,
   regardless of status.

Creating a new contract
=======================

In order for an employee to be paid, an active contract is required. If a new contract is needed,
click the :guilabel:`Create` button.

.. image:: contracts/new-contract-button.png
   :align: center
   :alt: Click the NEW smart button to create a new contract.

A contract form will appear and the information can be entered. Required fields are underlined in
bold, the other fields are not required to be filled in.

Required fields
---------------

.. image:: contracts/required-fields.png
   :align: center
   :alt: New contract form to be filled in when creating a new contract.

- :guilabel:`Contact Reference`: Type in the name or title for the contract, such as 'John Smith
  Contract'.
- :guilabel:`Company`: Select the company the contract applies to by clicking on the drop down
  menu. A new company can be created by typing the name in the box, then clicking either
  :guilabel:`Create` to create the new company, or :guilabel:`Create and Edit` to create the new
  company and edit the company details.
- :guilabel:`Salary Structure Type`: Select one of the salary structure types from the drop down
  menu. The default salary structure types are :guilabel:`Employee` or :guilabel:`Worker`.
- :guilabel:`Start Date`: The date the contract will start. Chose a date by clicking on the drop
  down menu, navigating to the correct month and year by using the arrow icons, then clicking on
  the date.
- :guilabel:`Working Schedule`: Select one of the working schedules from the drop down list.

.. tip::
   The *Working Schedule* drop down list displays all the *Working Times* for the selected Company.
   To modify or add to the *Working Schedule* drop down list, go to :menuselection:`Payroll -->
   Configuration --> Working Times` and either :guilabel:`Create` a new *Working Time* or click on
   an existing *Working Time* and editing it by clicking :guilabel:`Edit`.

Optional fields
---------------

.. image:: contracts/optional-fields.png
   :align: center
   :alt: Optional fields for a new contract.

- :guilabel:`Employee`: Name of the employee that the contract applies to.
- :guilabel:`Department`: The department the contract aplies to.
- :guilabel:`Job Position`: The specific job position the contract applies to.
- :guilabel:`Contract Type`: Chose from :guilabel:`CDI`, :guilabel:`CDD`, or :guilabel:`PFI` from
  the drop down menu.

   - :guilabel:`CDI` is an open-ended contract with just a start date but no end date.
   - :guilabel:`CDD` is a contract with both a start date and an end date.
   - :guilabel:`PFI` is a Belgian specific contract used when hiring employees that need training,
     and covers the training period specifically.

- :guilabel:`End Date`: If the contract has a specific end date, enter it here. Chose a date by
  clicking on the drop down menu, navigating to the correct month and year by using the arrow
  icons, then clicking on the date.
- :guilabel:`HR Responsible`: If there is a specific person in HR that is responsible for the
  contract, select the perosn from the drop down menu.
- :guilabel:`Analytic Account`: This field allows a link between the contract and a specific
  analytic account for accounting purposes.

Optional Tabs
-------------

Contract Details
~~~~~~~~~~~~~~~~

The contract details section allows for the addition and editing of a contract, and the ability to
send the contract to the employee for approval and signatures.

.. image:: contracts/contract-details.png
   :align: center
   :alt: Contract details in optional tabs for a new contract.

- :guilabel:`Contract Template`: Select a pre-existing contract template from the drop down.
  Contract templates are typically created thorugh the *Recrtuiment* application.
- :guilabel:`New Contract Document Template`: Select a contract from the drop down that will be
  modified for this new employee contract.
- :guilabel:`Contract Update Document Template`: Select a contract from the drop down if the
  employee has an existing contract that requires updating.
- :guilabel:`Notes`: The notes field is a text field where any notes for the employee contract can
  be entered for future reference.

Modifying a contract
********************

Click the :guilabel:`Exteral Link` button at the end of the line to open the contract template and
make any changes.

.. image:: contracts/external-link.png
   :align: center
   :alt: Contract details in optional tabs for a new contract.

A pop up wil appear with all the contract details. Modify the fields for the contract.

.. image:: contracts/modify-contract.png
   :align: center
   :alt: Edit the details for the contract.

- :guilabel:`Tags`: Select any tags associated with the contract.
- :guilabel:`Signed Document Workspace`: This is where the signatures will be housed. Chose a
  pre-configured workspace or create a new one.
- :guilabel:`Signed Document Tags`: Select or create any tags associated only with the signed
  contract as opposed to the original unsigned ocntract.
- :guilabel:`Redirect Link`: Enter a redirect link for the employee to access the contract.
- :guilabel:`Who can Sign`: Select either *All Users* or *On Invitation*.

   - :guilabel:`All Users`: Allows any user in the organization to sign the contract.
   - :guilabel:`On Invitation`: Only users selected in this field can sign the contract.

- :guilabel:`Invited Users`: Select the person(s) that can sign the document.
- :guilabel:`Document`: The attached document can be replaced by clicking the select icon (the
  pencil icon). A pop up will appear so another document can be selected for upload. The file must
  be a PDF. To remove the document, click the clear icon (trash can icon).

Once the edits are complete, click the :guilabel:`Save` smart button. All the information for the
selected contract will populate the fields, such as :guilabel:`Salary Information`. Any additional
tabs, such as :guilabel:`Personal Documents`, will appear if applicable.

Once the ifnormation for the new contract is entered on the form, there are several toptions via
smart buttons at the top. Click on :guilabel:`Generate Simulation Link` to create a link to the
contract that can be emailed to the employee. Click on :guilabel:`Signatur Request` and a pop up wil
appear to send the contract to the employee. The email message can be entered, the contract
specified, and anyone that should be copied can be specified as well.

.. image:: contracts/signature.png
   :align: center
   :alt: Send the contract via email to the employee to sign.

When edits are done, click the :guilabel:`Send` smart button to send the email, or click
:guilabel:`Discard` to delete the email.

Whne the new contract is done, click the :guilabel:`Save` smart button to save all the changes.

Salary Information
~~~~~~~~~~~~~~~~~~

.. image:: contracts/salary-info.png
   :align: center
   :alt: Optional tabs for a new contract.

This section is where the specific salary details are defined. This section is country-specific, so
depending on where the company is located, these fields will vary.

Enter either the amount in the various fields, or check off a box to apply a benefit. Some options
that can be entered here include *Meal Vouchers*, *Fuel Card*, *Internet*, *Paid Time Off*, etc.

Some fields may be automatically filled in based off of the contracts selected in the *Contract
Details* tab.

Attachment of Salary
~~~~~~~~~~~~~~~~~~~~

.. image:: contracts/salary-attachment.png
   :align: center
   :alt: Optional tabs for a new contract.

Any automatic deductions or allocations for an employee, such as child support payments and wage
garnishments, are referred to as a *salary attachment*. This section is where all of these
deductions or allocations are set.

To add a new deduction, click on :guilabel:`Add a line`. Type in a description for the allocation
under :guilabel:`Description`.

.. image:: contracts/garnishment.png
   :align: center
   :alt: Enter a new line for each type of garnishment.

Select the :guilabel:`Garnished Type` from the drop down. Chose from:

- :guilabel:`Attachment of Salary` - Any payments taken out towards something that is *not* child
  support. Typically any garnishments such as lawsuit payments, payments toward taxes owed, etc.
- :guilabel:`Allocaiton of Salary` - Any deduction that is not required but voluntary, such as a
  pre-tax allocation to a college savings account.
- :guilabel:`Child Support` - Any payments taken out specifically for child support.

Enter the start and end dates the entry applies to by clicking on the drop down menu under
:guilabel:`From` and :guilabel:`To`, navigating to the correct month and year by using the arrow
icons, then clicking on the date.

Last, enter the *amount* that each payslip will pay towards the entry.

Delete a line by clicking on the *trash can icon* at the end of the line.

.. image:: contracts/delete-garnishment.png
   :align: center
   :alt: Remove a new line by clicking the delete icon.

Save and send the contract
--------------------------

Once contracts have been created and/or modified, save the contract by clicking the :guilabel:`Save`
smart button. Next, the contract must be sent to the employee to be signed.

Click on one of the following smart buttons:

.. image:: contracts/send-contract.png
   :align: center
   :alt: Send the contract to the employee via one of the smart buttons.

- :guilabel:`Generate Simulation Link`: Clicking this will open a pop-up that contains the basic
  information as well as a link for the contract. There is a :guilabel:`Send Offer` smart button
  that will send an email to the employee so they can sign the contract.

.. image:: contracts/simulation.png
   :align: center
   :alt: Sends a link to the employee for the contract.

- :guilabel:`Signature Request`: Clicking this will have a pop up appear where an email can be
  typed to the employee. Select the document from the drop down, and fill out the email section.
  Click :guilabel:`Send` when the email is ready to be sent.

.. image:: contracts/sign-contract.png
   :align: center
   :alt: Request a signature for the contract via email.

- :guilabel:`Credit Time`: This is a Belgian specific option, and will only appear for companies
  located in Belgium.


