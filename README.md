# MAHARASHTRA FESTIVALS DATASET

**Creators:** Dr. Sujata Kolhe, Monika Mohandule, Divya Bobade, Tanuja Babaleshwar, and Anuradha Wagh

**Institution:** Pimpri Chinchwad College of Engineering, Pune, India

**License:** [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

---

## 1. OVERVIEW

The Maharashtra Festivals Dataset documents festivals celebrated across the regions of Maharashtra, India. Each record gives the festival name and alternate name, location, regional classification, religion and category, associated deity, Hindu and Gregorian months, duration, a short description of its historical background, rituals, fair activities, cultural significance, and a source reference.

The dataset is intended for cultural documentation, regional festival studies, and research on natural language processing and AI-generated information.

## 2. FILES AND STRUCTURE

**Main file:** `Maharashtra_Cultural_Festival_dataset.xlsx` (Microsoft Excel)

The dataset is organized into six regional CSV files:

- `Multiple Regions.csv`
- `Khandesh.csv`
- `Konkan.csv`
- `West_Maharashtra-Sheet1.csv`
- `Marathwada-Sheet1.csv`
- `Vidarbha-Sheet1(1).csv`

The dataset contains six worksheets, one for each regional classification:

| Region | Records | Festival ID Prefix |
|---|---:|---|
| Marathwada | 18 | MH-MAR |
| West Maharashtra | 111 | MH-WMH |
| Vidarbha | 82 | MH-VID |
| Konkan | 37 | MH-KON |
| Khandesh | 24 | MH-KHA |
| Multiple Regions | 50 | MH-MUL |
| **Total** | **322** | — |

The **Multiple Regions** category contains festivals observed in more than one region of Maharashtra or beyond. Therefore, a festival may also appear in a regional worksheet. For example, Holi may be included in both the Multiple Regions worksheet and a regional worksheet.

## 3. DATA FIELDS

All worksheets use the same 17 columns:

| Field | Description |
|---|---|
| Festival Id | Unique identifier for each record, such as MH-VID-001. |
| Festival Name | Name of the festival. |
| Alternate Name | Other names used for the festival. |
| Village | Village, town, or site where the festival is held. |
| Present District | Current district in which the festival is observed. |
| Region | Regional classification within Maharashtra. |
| Religion | Religion or tradition associated with the festival. |
| Category | Type of festival, such as religious, cultural, or tribal. |
| Deity | Associated deity, if any. |
| Hindu Month | Month of the Hindu calendar in which the festival is held. |
| Gregorian Month | Month or months of the Gregorian calendar. |
| Duration | Duration of the festival. |
| Historical Background | Short description of the festival's origin and history. |
| Rituals | Rituals and customary practices performed during the festival. |
| Fair Activities | Activities at the associated fair or gathering. |
| Cultural Significance | Short description of the festival's cultural importance. |
| Source | Source reference, provided as a web link or text reference. |

Festival IDs are intended to uniquely identify records across the entire dataset.

## 4. SOURCES AND DATA COLLECTION

Festival information was compiled from the sources recorded in the **Source** field of each record.

The descriptive fields contain short summaries prepared for this dataset. The original source content remains the property of its respective owners.

Users are encouraged to consult the cited sources to verify festival names, locations, historical details, rituals, dates, and other cultural information before using individual records in research or other applications.

## 5. MISSING VALUES

Missing information is represented by the text `N/A`, and no cell is intentionally left empty.

- **Total data cells:** 5,474
- **Cells containing `N/A`:** 377
- **Percentage of missing values:** Approximately 6.89%

`N/A` indicates that the information was not available in the sources consulted during dataset preparation. It does not mean that the festival, ritual, or cultural practice does not exist.

Users should handle `N/A` values appropriately before performing statistical analysis, visualization, or machine learning.

## 6. CONVENTIONS

### Hindu Calendar

Maharashtra generally follows the Amanta lunar calendar, in which the lunar month ends on the new moon. Under the Purnimanta calendar, used in parts of northern India, some festivals may be associated with the following month's name.

For example, Mahashivratri may be associated with Magha under the Amanta convention and Phalguna under the Purnimanta convention.

The dataset may contain either convention, depending on the consulted source.

### Spelling and Transliteration

Festival names, month names, and place names are transliterated into English. Spellings may vary between records because of regional pronunciation, transliteration practices, or differences between sources.

### Fixed-Date Festivals

For festivals observed on a fixed Gregorian date, the Hindu Month may be recorded as not applicable when appropriate.

### Regional Classification

Festivals are assigned to regional categories based on the information available during dataset preparation. Some festivals are celebrated across multiple regions and may appear in the Multiple Regions worksheet as well as in individual regional worksheets.

## 7. LIMITATIONS

The dataset has the following limitations:

- The level of detail varies between records.
- Festival names, dates, rituals, and practices may differ across sources and over time.
- The dataset does not cover every festival celebrated in Maharashtra.
- Regional classification reflects the information available when the dataset was prepared.
- Some fields, such as Religion and Hindu Month, may contain variations in spelling or terminology for similar categories.
- Some records contain missing information represented by `N/A`.
- Source availability and the level of documentation may differ between festivals and regions.
- The dataset is a cultural documentation resource and should not be treated as an exhaustive or definitive account of every regional tradition.

These limitations should be considered when using the dataset for research, statistical analysis, or AI applications.

## 8. USAGE GUIDELINES

Users are encouraged to follow these guidelines when working with the dataset:

1. Use the **Festival Id** to refer to individual records.
2. Consult the source references before relying on factual details.
3. Document any data cleaning, corrections, or transformations.
4. Handle `N/A` values appropriately before analysis.
5. Be aware of regional differences in festival names, dates, and traditions.
6. Cite the dataset when using it in research, academic work, or publications.
7. Provide appropriate attribution in accordance with the CC BY 4.0 license.
8. Verify important cultural details against reliable sources before publishing derivative work.

## 9. USE OF AI TOOLS

ChatGPT and Claude were used to paraphrase descriptive text for the dataset.

The dataset is intended to support cultural documentation, regional festival studies, and research involving natural language processing and AI-generated information.

Users should independently verify the source information before relying on individual records for factual or research purposes.

## 10. CREATORS, LICENSE AND CONTACT

### Creators

- Dr. Sujata Kolhe, Pimpri Chinchwad College of Engineering, Pune, India
- Monika Mohandule, Pimpri Chinchwad College of Engineering, Pune, India
- Divya Bobade, Pimpri Chinchwad College of Engineering, Pune, India
- Tanuja Babaleshwar, Pimpri Chinchwad College of Engineering, Pune, India
- Anuradha Wagh, Pimpri Chinchwad College of Engineering, Pune, India

### Contact

- Dr. Sujata Kolhe: [sujata.kolhe@pccoepune.org](mailto:sujata.kolhe@pccoepune.org)
- Monika Mohandule: [monikamohandule1702@gmail.com](mailto:monikamohandule1702@gmail.com)
- Divya Bobade: [divyabobade907@gmail.com](mailto:divyabobade907@gmail.com)
- Tanuja Babaleshwar: [tanujababaleshwar18@gmail.com](mailto:tanujababaleshwar18@gmail.com)
- Anuradha Wagh: [waghanu05@gmail.com](mailto:waghanu05@gmail.com)

### License

This dataset is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

Under this license, users may share and adapt the material for any purpose, including commercial purposes, provided that appropriate credit is given, a link to the license is supplied, and changes are indicated.

Please consult the license for the complete terms and conditions.

## 11. CITATION

Kolhe, S., Mohandule, M., Bobade, D., Babaleshwar, T., & Wagh, A. (2026). *Maharashtra Festivals Dataset* (Version 1.0) [Data set]. GitHub. [https://github.com/monikamohandule1702-web/Maharashtra-cultural-festival-dataset](https://github.com/monikamohandule1702-web/Maharashtra-cultural-festival-dataset)

When using this dataset in academic work, please cite the dataset and acknowledge the creators and mentor as appropriate.

## 12. VERSION HISTORY

**Version 1.0 — First Public Release (2026)**

- Initial public release of the Maharashtra Festivals Dataset.
- Contains 322 festival records across six regional classifications.
- Includes 17 data fields for documenting festival names, locations, traditions, historical backgrounds, rituals, cultural significance, and source references.
- Includes a dedicated Multiple Regions classification for festivals celebrated across multiple regions.
- Missing values are represented by `N/A`.
- Released under the Creative Commons Attribution 4.0 International License (CC BY 4.0).
