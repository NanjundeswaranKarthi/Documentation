SWPPP Masters – Data Management Process
========================================

Overview
--------

The **Master Data Management** section in the SWPPPly platform allows team members to manage structured data sets essential for various application screens, such as:

- Concrete Washout
- Construction Materials
- Final Site Stabilization BMPs
- TMDL Pollutants
- ...and more.

Each master item reflects a specific screen or functionality in the application.

Jackie’s Role – Initial Setup
-----------------------------

Jackie is responsible for the initial creation of all master datasets, including:

- Adding required fields and entries to master datasets
- Populating master entries in screens

This master data will be moved to the production environment after setup.

Andy’s Role – Ongoing Updates in Masters Screen
-----------------------------------------------

If Andy or any team member needs to:

- Update existing data, or
- Add a new master, or
- Add new fields in any master, or
- Add new entries in any master

→ They can directly create, edit, or delete data using the **Master Data Management UI**.

Export & Handoff Process
------------------------

After completing any updates:

- If the new or updated master data is associated with a new screen or functionality in the app,
- Andy has to export the modified master data and send the exported file to Jackie.

✅ This step is essential because:

- Created or updated master data may require changes in DC screens
- Once Jackie receives a new exported file, Jackie will configure and integrate the updated data into the corresponding screen or code module to ensure it appears and functions correctly in production.

Why Export File Sent to Jackie?
-------------------------------

- Ensures consistency between the UI and backend
- Prevents mismatch or display issues (Screen and Exported PDF) in production
- Jackie will configure and integrate changes into the production codebase accordingly

.. seealso::
   