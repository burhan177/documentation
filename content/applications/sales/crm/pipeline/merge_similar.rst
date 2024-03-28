=====================================
Merge similar leads and opportunities
=====================================

Odoo automatically detects similar *leads* and *opportunities* within the *CRM* app. Identifying
these duplicated records allows them to be merged without losing any information in the process.
Not only does this help keep the *pipeline* organized, it prevents customers from being contacted
by more than one salesperson.

Identifying similar leads and opportunities
===========================================

Similar *leads* and *opportunities* are identified by comparing the email addresses of the
associated contacts. If a similar lead/opportunity is found, a :guilabel:`Similar Lead` smart button
appears at the top of the lead or opportunity record.

Comparing similar leads and opportunities
-----------------------------------------

To compare the details of the similar leads/opportunities, click the :guilabel:`Similar Leads`
button. This opens a Kanban view with only the similar leads/opportunities. Click into each card to
view the details for each lead/opportunity, and confirm if they should be merged.

Merging similar leads and opportunities
=======================================

.. important::
   When merging, Odoo gives priority to whichever lead/opportunity was created in the system first,
   merging the information into the first created lead/opportunity. However, if a lead and an
   opportunity are being merged, the resulting record is referred to as an opportunity, regardless
   of which record was created first.

After confirming that the leads/opportunities should be merged, return to the Kanban view using
breadcrumbs, or by clicking the :guilabel:`Similar Lead` smart button. Click the :guilabel:`☰
(three vertical lines)` icon to change to list view.

Check the box on the left of the page for the leads/opportunities to be merged. Then, click the
:guilabel:`Action ⚙️ (gear)` icon at the top of the page, to reveal a drop-down menu. From that
drop-down menu, select the :guilabel:`Merge` option to merge the selected opportunities or leads.

When :guilabel:`Merge` is selected from the :guilabel:`Action ⚙️ (gear)` drop-down menu, a
:guilabel:`Merge` pop-up window appears. In that pop-up window, decide to :guilabel:`Assign
opportunities to` a :guilabel:`Salesperson` and/or :guilabel:`Sales Team`.

Below those fields, the leads/opportunities to merge are listed, along with their related
information. To merge those selected leads/opportunities, click :guilabel:`Merge`.

.. note::
   When merging opportunities, no information is lost. Data from the other opportunity is logged in
   the chatter, and the information fields, for reference.

When leads and opportunities should not be merged
=================================================

There may be instances where a similar lead or opportunity is identified, but should **not** be
merged. These circumstances will vary based on the processes of the salesteam and organization,
however, some potential scenarios are listed below.

Lost leads
----------

