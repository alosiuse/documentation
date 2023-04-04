======================
User default warehouse
======================

Setting up a **default warehouse** can be useful for field technicians who keep a supply in their
van or those who always resupply from the same warehouse. It also allows field workers to switch
between warehouses from their profile.

Products in sales orders created during field interventions are always pulled from the default
warehouse, keeping the inventory accurate.

.. seealso::
   :doc:`../../inventory_and_mrp/inventory`

Configuration
=============

To set up a user default warehouse, the :doc:`storage locations
<../../inventory_and_mrp/inventory/management/warehouses/warehouses_locations>` feature needs to be
activated in the **Inventory** app. It is also necessary to have more than one warehouse in your
database.

.. seealso::
   - :doc:`../../inventory_and_mrp/inventory/management/warehouses/warehouses_locations`
   - :doc:`../../inventory_and_mrp/inventory/routes/concepts/use_routes`

User account
------------

To set up a default warehouse for a specific user, open the **Settings** application, then go to
:menuselection:`Users --> Manage users`, select a user, then go to the :guilabel:`Preferences` tab.
Scroll down to :guilabel:`Inventory`, and select the default warehouse from the drop-down menu.

.. image:: default_warehouse/user-default.png
   :alt: Selection of a default warehouse on a user profile.

.. tip::
   You can follow the same steps to easily change your default warehouse as needed.

Default warehouse in field service tasks
========================================

Once a default warehouse has been configured for a user, the materials used for a sales order
related to a Field Service task are pulled from that specific warehouse. Open the related sales
order, go to the :guilabel:`Other Info` tab, then scroll down to :guilabel:`Delivery`. The default
warehouse is applied correctly.

Once the Field Service task is marked as done, the stock of the default warehouse is automatically
updated.
