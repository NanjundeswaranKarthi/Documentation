
.. _data-dictionary-dd:

Data Dictionary (DD)
====================
A centralized list of all dynamic fields **(e.g., Project Name, Address, Risk Level)**. Created by Andy

Think of the Data Dictionary like a list of blank spaces you’ll need to fill in later  
**(e.g., Project Name, Address, Start Date, etc.)**.

**Why is it needed?**

- Each state’s SWPPP blueprint has different data fields **(like Project Name, Site Address, Risk Level).**  
- Without it, the blueprint has empty placeholders and can’t collect the correct data.  
- Without this list, we don’t know what questions to ask Sophia later.  

**✅ Purpose**

- It serves as a **bridge** between static and dynamic content.  
- **Dynamic data points**: variables such as project name, site address, and contact information are added here.  
- Defines variables used throughout the SWPPP.  
- Used to map data inputs to specific parts of the document.  
- **Reusable** across multiple projects.  

**🟢 Key Features**

- **No dependency** – it can be created independently before any other components.  
- Acts as a **central repository** for all dynamic data fields used in the template.  
- Supports data types like **String, Integer, Date, and Object**.  
- ✅ Think of this as the **glue** between input fields and final documents.  

**What happens next:**

1. **Andy** creates the DD.  
2. **Andy** exports and sends it to Jackie.  
3. **Jackie** imports it into the system.  
4. **Sophia** fills in the data using the Data Collector UI.

.. seealso::