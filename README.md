MAHARASHTRA FESTIVALS DATASET
=============================

1. OVERVIEW
-----------
The Maharashtra Festivals Dataset documents festivals celebrated across the regions of Maharashtra, India. Each record gives the festival name and alternate name, location, regional classification, religion and category, associated deity, Hindu and Gregorian months, duration, a short description of its historical background, rituals, fair activities and cultural significance, and a source reference.

The dataset is intended for cultural documentation, regional festival studies, and research on natural language processing and AI-generated information.

2. FILES AND STRUCTURE
----------------------
File: Maharashtra_Cultural_Festival_dataset.xlsx (Microsoft Excel)
      Multiple Regions.csv
      Khandesh.csv
      Konkan.csv
      West_Maharashtra-Sheet1.csv
      Marathwada-Sheet1.csv
      Vidarbha-Sheet1(1).csv

The file contains six worksheets, one for each regional classification:

- Marathwada: 18 records (Festival Id prefix MH-MAR)
- West Maharashtra: 111 records (Festival Id prefix MH-WMH)
- Vidarbha: 82 records (Festival Id prefix MH-VID)
- Kokan: 38 records (Festival Id prefix MH-KON)
- Khandesh: 24 records (Festival Id prefix MH-KHA)
- Multiple Regions: 50 records (Festival Id prefix MH-MUL)
- Total: 323 records

"Multiple Regions" holds festivals observed in more than one region of Maharashtra or beyond. A festival may therefore also appear in a regional sheet (for example Holi).

3. DATA FIELDS
--------------
All worksheets use the same 17 columns:

- Festival Id: unique identifier (for example MH-VID-001), unique across the whole dataset
- Festival Name: name of the festival
- Alternate Name: other names used for the festival
- Village: village, town or site where it is held
- Present District: current district
- Region: regional classification
- Religion: religion or tradition associated with the festival
- Category: type of festival (for example religious, cultural, tribal)
- Deity: associated deity, if any
- Hindu Month: month of the Hindu calendar in which it is held
- Gregorian Month: month(s) of the Gregorian calendar
- Duration: how long it lasts
- Historical Background: short description of origin and history
- Rituals: rituals performed
- Fair Activities: activities at the associated fair or gathering
- Cultural Significance: short description of its cultural importance
- Source: source reference (a web link or a text reference)

4. SOURCES AND DATA COLLECTION
------------------------------
Festival information was compiled from the sources recorded in the Source field of each record. The descriptive fields are short summaries written for this dataset; the original content belongs to the cited sources.

5. MISSING VALUES
-----------------
Missing information is recorded as the text "N/A", and no cell is left empty. In total, 364 of 5,491 data cells (about 6.6%) are "N/A".

"N/A" means the information was not available in the consulted sources. It does not mean that the festival, ritual or practice does not exist. Please handle "N/A" before any statistical analysis.

6. CONVENTIONS
--------------
- Hindu Month: Maharashtra follows the Amanta calendar, in which the month ends on the new moon. Under the Purnimanta calendar, used in northern India, some festivals fall in the next month's name (for example, Mahashivratri is Magha in Amanta and Phalguna in Purnimanta). The dataset may contain either convention.
- Spelling: month and place names are transliterated, and spellings may vary between records.
- Fixed-date festivals: for festivals observed on a fixed Gregorian date, the Hindu Month may be recorded as not applicable.

7. LIMITATIONS
--------------
- The level of detail varies from record to record.
- Festival names, dates and practices may differ across sources and over time.
- Coverage does not include every festival celebrated in Maharashtra.
- Regional classification reflects the information available when the dataset was prepared.
- Values in a few fields (for example Religion and Hindu Month) may use slightly different spellings for the same category.
- Missing values may affect analyses that need complete records.

8. USAGE GUIDELINES
-------------------
1. Use the Festival Id to refer to individual records.
2. Consult the source references before relying on factual details.
3. Document any cleaning, corrections or transformations you make.
4. Handle "N/A" values appropriately.
5. Cite the dataset when using it in research or publications.

9. USE OF AI TOOLS
------------------
ChatGPT and Claude were used to paraphrase text . 

10. CREATORS, LICENSE AND CONTACT
---------------------------------
Creator: Monika Mohandule, Pimpri Chinchwad College of Engineering, Pune, India
         Divya Bobade, Pimpri Chinchwad College of Engineering, Pune, India
	 Tanuja Babaleshwar, Pimpri Chinchwad College of Engineering, Pune, India
         Anuradha Wagh, Pimpri Chinchwad College of Engineering, Pune, India
Contact:  monikamohandule1702@gmail.com
         divyabobade907@gmail.com
         tanujababaleshwar18@gmail.com
         waghanu05@gmail.com
License: CC BY 4.0

11. CITATION
------------

Mohandule, M., Bobade, D., Babaleshwar, T., & Wagh, A. (2026). *Maharashtra Festivals Dataset* (Version 1.0) [Data set].GitHub repository:https://github.com/monikamohandule1702-web/Maharashtra-cultural-festival-dataset.git 

12. VERSION HISTORY
-------------------
Version 1.0: first public release, 323 festival records in six worksheets.
