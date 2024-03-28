:show-content:
:show-toc:

=====
Lunch
=====

The *Lunch* applicaiton in Odoo allows users a convenient way to order food and pay for their meal
directly from the database. This is a convenience for employees as well as the vendors they work
with. Offering this is a great perk for employees.

Before employees can use the *Lunch* application, several things need to be configured: settings,
vendors, locations, products, product categories, and alerts. Once these are created, employees can
view offerings and order food.

Settings
========

Only 2 settings are needed to configure in the *Lunch* app: overdraft settings and notifications.
To access the settings, navigate to :menuselection:`Lunch app --> Configuration: Settings`.

Configure the following:

- :guilabel:`Lunch Overdraft`: enter the maximum overdraft amount for employees. The currency
  format is determined by the localization setting of the company.
- :guilabel:`Reception notification`: set the message users receive via the *Discuss* app when their
  food has been delivered. The default message `Your lunch has been delivered. Enjoy your meal!`
  populates this field, but can be modified, if desired.

  If in an environment with multiple languages installed in the database, a language code appears
  in the top-right of the text box. Click the 2 letter language code (for example, :guilabel:`EN`
  for English) and a :guilabel:`Tranlate: company_lunch_notify_message` pop-up window loads with the
  option to enter a translation for the other languages used by the database.

  The first column lists the different languages in alphabetical order, with the currently selected
  language in bold. The second column has the currently configured message in each column. The
  last column in the far-right provides a text box to type in a translation for each language.

  Enter the text that should appear for each language, then click :guilabel:`Save`.

  .. image:: lunch/translation.png
     :align: center
     :alt: The translation text box, with the current language highlighted, and the Arabic
           translation field highlighted.

Vendors
=======

Before food can be ordered, the restaurants that make the food, referred to as *vendors* in Odoo,
**must** be configured.

First navigate to :menuselection:`Lunch app --> Configuration: Vendors`, and all currently
configured vendors for the *Lunch* app appear in a default Kanban view. To change to a list view,
click the :guilabel:`(list icon)` in the top-left corner.

To add a new vendor, click the :guilabel:`New` button in the top-left corner, and a new lunch
supplier form loads.

Fill out the following fields on the form:

Vendor information section
--------------------------

- :guilabel:`Vendor`: enter a name for the vendor.
- :guilabel:`Vendor`:
- :guilabel:`Address`: enter the vendor's address in the various fields in this section.
- :guilabel:`Email`: enter the vendor's email in this field.
- :guilabel:`Phone`: enter the vendor's phone number in this field.
- :guilabel:`Company`: if this vendor is only available to a specific company, select the company
  from the drop-down menu. If this field is left blank, the vendor's items are available to **all**
  companies.

Availability section
--------------------

Orders section
--------------

- :guilabel:`Delivery`: using the drop-down menu, select either :guilabel:`Delivery` if the vendor
  delivers food to the office, or :guilabel:`No Delivery` if ordered food must be picked up by the
  employee.
- :guilabel:`Location`: select which locations are able to order from this vendor. Multiple
  locations can be selected. If this field is left blank, **all** locations can order from the
  vendor.
- :guilabel:`Send Order By`:
- :guilabel:`Order Time`:

Labels section
--------------

- :guilabel:`Extra (#) Label`:
- :guilabel:`Extra (#) Quantity`:




Locations
=========

Products
========

Product Categories
==================

Alerts
======


.. toctree::
   :titlesonly:

   lunch/new_job
