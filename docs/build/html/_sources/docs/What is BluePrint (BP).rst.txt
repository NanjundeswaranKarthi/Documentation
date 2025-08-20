.. _blueprint:

Blueprint (BP)
==============

- A Blueprint is like the empty SWPPP book with chapter titles and some fixed text already written.

- Wherever something changes per project, there’s a blank space that links to the Data Dictionary.  

- It is the **skeletal structure** of the SWPPP document, including static text and dynamic placeholders.

**Why is it needed?**

- A Blueprint is the **document skeleton** for a specific state’s SWPPP.  
- It contains **fixed legal/environmental text** plus placeholders for dynamic data from the DD.  
- Without this skeleton, the final document will be a pile of random answers with no structure.  

**✅ Purpose**

- Organizes the content of the SWPPP (e.g., Project Info, TMDLs, BMPs).  
- Integrates **Data Dictionary variables** in required places.  

**🔗 Dependency**

- Requires the **Data Dictionary** to define variables.  

**What happens next:**

1. **Andy** writes the SWPPP skeleton for a state.  
2. **Andy** puts placeholders (`{{PROJECT_NAME}}`) wherever dynamic data goes.  
3. **Andy** exports it (as JSON) and sends it to Jackie.  
4. **Jackie** loads it into the system.  

.. seealso::

