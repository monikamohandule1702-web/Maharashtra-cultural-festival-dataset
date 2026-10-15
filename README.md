# MAHARASHTRA FESTIVALS DATASET

## 1. Overview

The Maharashtra Festivals Dataset documents festivals celebrated across the regions of Maharashtra, India. Each record gives the festival name and alternate name, location, regional classification, religion and category, associated deity, Hindu and Gregorian months, duration, a short description of its historical background, rituals, fair activities and cultural significance, and a source reference.

The dataset is intended for cultural documentation, regional festival studies, and research on natural language processing and AI-generated information.

## 2. Files and Structure

**Main file:** `Maharashtra_Cultural_Festival_dataset.xlsx` (Microsoft Excel)

**Additional CSV files:**
- `Multiple Regions.csv`
- `Khandesh.csv`
- `Konkan.csv`
- `West_Maharashtra-Sheet1.csv`
- `Marathwada-Sheet1.csv`
- `Vidarbha-Sheet1(1).csv`

The Excel file contains six worksheets, one for each regional classification:

| Region | Records | Festival ID Prefix |
|---|---:|---|
| Marathwada | 18 | `MH-MAR` |
| West Maharashtra | 111 | `MH-WMH` |
| Vidarbha | 82 | `MH-VID` |
| Kokan | 38 | `MH-KON` |
| Khandesh | 24 | `MH-KHA` |
| Multiple Regions | 50 | `MH-MUL` |
| **Total** | **323** | |

"Multiple Regions" holds festivals observed in more than one region of Maharashtra or beyond. A festival may therefore also appear in a regional sheet (for example Holi).

## 3. Data Fields

All worksheets use the same 17 columns:

- **Festival Id:** Unique identifier (for example `MH-VID-001`), unique across the whole dataset.
- **Festival Name:** Name of the festival.
- **Alternate Name:** Other names used for the festival.
- **Village:** Village, town or site where it is held.
- **Present District:** Current district.
- **Region:** Regional classification.
- **Religion:** Religion or tradition associated with the festival.
- **Category:** Type of festival (for example, religious, cultural, tribal).
- **Deity:** Associated deity, if any.
- **Hindu Month:** Month of the Hindu calendar in which it is held.
- **Gregorian Month:** Month(s) of the Gregorian calendar.
- **Duration:** How long it lasts.
- **Historical Background:** Short description of origin and history.
- **Rituals:** Rituals performed.
- **Fair Activities:** Activities at the associated fair or gathering.
- **Cultural Significance:** Short description of its cultural importance.
- **Source:** Source reference (a web link or a text reference).

## 4. Sources and Data Collection

Festival information was compiled from the sources recorded in the Source field of each record. The descriptive fields are short summaries written for this dataset; the original content belongs to the cited sources.

## 5. Missing Values

Missing information is recorded as the text `N/A`, and no cell is left empty. In total, 364 of 5,491 data cells (about 6.6%) are `N/A`.

`N/A` means the information was not available in the consulted sources. It does not mean that the festival, ritual or practice does not exist. Please handle `N/A` before any statistical analysis.

## 6. Conventions

- **Hindu Month:** Maharashtra follows the Amanta calendar, in which the month ends on the new moon. Under the Purnimanta calendar, used in northern India, some festivals fall in the next month's name (for example, Mahashivratri is Magha in Amanta and Phalguna in Purnimanta). The dataset may contain either convention.
- **Spelling:** Month and place names are transliterated, and spellings may vary between records.
- **Fixed-date festivals:** For festivals observed on a fixed Gregorian date, the Hindu Month may be recorded as not applicable.

## 7. Limitations

- The level of detail varies from record to record.
- Festival names, dates and practices may differ across sources and over time.
- Coverage does not include every festival celebrated in Maharashtra.
- Regional classification reflects the information available when the dataset was prepared.
- Values in a few fields (for example, Religion and Hindu Month) may use slightly different spellings for the same category.
- Missing values may affect analyses that need complete records.

## 8. Usage Guidelines

1. Use the Festival Id to refer to individual records.
2. Consult the source references before relying on factual details.
3. Document any cleaning, corrections or transformations you make.
4. Handle `N/A` values appropriately.
5. Cite the dataset when using it in research or publications.

## 9. Use of AI Tools

ChatGPT and Claude were used to paraphrase text.

## 10. Creators, License and Contact

### Creators

- **Monika Mohandule**, Pimpri Chinchwad College of Engineering, Pune, India
- **Divya Bobade**, Pimpri Chinchwad College of Engineering, Pune, India
- **Tanuja Babaleshwar**, Pimpri Chinchwad College of Engineering, Pune, India
- **Anuradha Wagh**, Pimpri Chinchwad College of Engineering, Pune, India

### Contact

- Monika Mohandule: `monikamohandule1702@gmail.com`
- Divya Bobade: `divyabobade907@gmail.com`
- Tanuja Babaleshwar: `tanujababaleshwar18@gmail.com`
- Anuradha Wagh: `waghanu05@gmail.com`

### License

This dataset is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

You may share and adapt this dataset for any purpose, including commercial use, provided appropriate credit is given, a link to the license is included, and changes are indicated.

License: [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

## 11. Citation

Mohandule, M., Bobade, D., Babaleshwar, T., & Wagh, A. (2026). *Maharashtra Festivals Dataset* (Version 1.0) [Data set]. GitHub repository: [https://github.com/monikamohandule1702-web/Maharashtra-cultural-festival-dataset](https://github.com/monikamohandule1702-web/Maharashtra-cultural-festival-dataset)

## 12. Version History

- **Version 1.0:** First public release, 323 festival records in six worksheets.
