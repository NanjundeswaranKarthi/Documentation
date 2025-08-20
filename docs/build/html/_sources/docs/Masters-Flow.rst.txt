Master's Flow – End-to-End Order
================================

Developer Creates Master Data
-----------------------------
- A developer (Dev) sets up new master data or modifies existing master data as required.

- This includes defining fields, entries, and any structural changes such as new rows or columns.

Script & Commit Changes
-----------------------
- The master data structure and content are scripted (e.g., migration or seed files).

- The script is committed and checked into the source code repository.

Code Merge
----------
- The committed changes are merged into the main branch (or integration branch) via a pull request and code review process.

- Local Pull & Migration Execution
--------------------------------
- Another developer (Dev2) or the same developer pulls the latest code changes.

- Runs the MongoDB migration scripts locally to apply master data changes in their development environment.

Environment Promotion via CI/CD
-------------------------------
Once verified, the CI/CD pipeline promotes the updated master data through the following environments:

- Development (Dev)
- Quality Assurance (QA)
- User Acceptance Testing (UAT)
- Production (PROD)

Verification & Screen Configuration
-----------------------------------
- At each stage, verify that master data changes reflect correctly in their respective screens.

.. image:: /_static/masters_flow_vertical.png
   :alt: Master Data Flow Diagram
   :align: center
   :width: 300px

.. seealso::
