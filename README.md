# Maharashtra Festivals Dataset

**A Region-Wise Dataset of Festivals and Cultural Traditions of Maharashtra, India**

## 1. Overview

The Maharashtra Festivals Dataset documents festivals celebrated across the regions of Maharashtra, India. Each record includes the festival name and alternate name, location, regional classification, religion and category, associated deity, Hindu and Gregorian months, duration, historical background, rituals, fair activities, cultural significance, and source reference.

The dataset is intended for cultural documentation, regional festival studies, and research on natural language processing (NLP) and AI-generated information.

## 2. Files and Structure

The repository contains one combined Excel workbook and six regional CSV files.

### Files Included

| File Name | Description |
|---|---|
| `Maharashtra_Cultural_Festival_dataset.xlsx` | Combined Excel workbook containing all six worksheets |
| `Multiple Regions.csv` | Festivals associated with multiple regions |
| `Khandesh.csv` | Khandesh festival records |
| `Konkan.csv` | Konkan festival records |
| `West_Maharashtra-Sheet1.csv` | West Maharashtra festival records |
| `Marathwada-Sheet1.csv` | Marathwada festival records |
| `Vidarbha-Sheet1(1).csv` | Vidarbha festival records |

### Regional Distribution

The dataset contains 323 records across six worksheets.

| Region | Number of Records | Festival ID Prefix |
|---|---:|---|
| Marathwada | 18 | `MH-MAR` |
| West Maharashtra | 111 | `MH-WMH` |
| Vidarbha | 82 | `MH-VID` |
| Konkan | 38 | `MH-KON` |
| Khandesh | 24 | `MH-KHA` |
| Multiple Regions | 50 | `MH-MUL` |
| **Total** | **323** | — |

The *Multiple Regions* worksheet contains festivals observed in more than one region of Maharashtra or in broader geographical contexts. A festival may also appear in an individual regional worksheet. For example, Holi may be represented in multiple regional contexts.

**Note:** The total represents worksheet records and should not automatically be interpreted as 323 unique festivals.

## 3. Data Fields

All worksheets use the same 17 columns.

| Field | Description |
|---|---|
| Festival Id | Identifier assigned to a festival record, such as `MH-VID-001` |
| Festival Name | Name of the festival |
| Alternate Name | Other names used for the festival |
| Village | Village, town, or site where the festival is held |
| Present District | Current district associated with the record |
| Region | Regional classification |
| Religion | Religion or tradition associated with the festival |
| Category | Type of festival, such as religious, cultural, or tribal |
| Deity | Associated deity, if applicable |
| Hindu Month | Hindu calendar month associated with the festival |
| Gregorian Month | Gregorian month or months of celebration |
| Duration | Recorded duration of the festival |
| Historical Background | Short description of the festival's origin and history |
| Rituals | Rituals and traditional practices performed |
| Fair Activities | Activities at associated fairs or gatherings |
| Cultural Significance | Description of the festival's cultural importance |
| Source | Web link or textual source reference |

Festival IDs are intended to provide consistent references to individual records across the dataset.

## 4. Sources and Data Collection

Festival information was compiled from the sources recorded in the `Source` field of each record.

The descriptive fields contain short summaries prepared for this dataset. Original source material remains attributable to its respective sources.

Users should consult the cited references to verify historical details, festival dates, rituals, locations, and cultural practices before relying on the information for research or publication.

## 5. Missing Values

Missing information is represented by the text `N/A`. No data cells are intentionally left empty.

- **Total data cells:** 5,491
- **Cells containing `N/A`:** 364
- **Percentage of missing values:** Approximately 6.6%

`N/A` indicates that the information was not available in the consulted sources. It does not mean that the festival, ritual, or cultural practice does not exist.

Users should handle `N/A` values appropriately before conducting statistical analysis, data visualization, or machine-learning tasks.

## 6. Data Conventions

### Hindu Calendar

Maharashtra commonly follows the Amanta calendar convention, in which the lunar month ends on the new moon. Under the Purnimanta convention used in parts of northern India, some festivals may be assigned to a different month.

For example, Mahashivratri may be associated with Magha under the Amanta convention and Phalguna under the Purnimanta convention.

The dataset may contain month names based on either convention. Users should verify calendar assignments when precise calendrical analysis is required.

### Spelling and Transliteration

Place names, festival names, and month names are transliterated into English. Spellings may vary between records because of regional language differences and alternative transliterations.

### Fixed-Date Festivals

For festivals observed on a fixed Gregorian date, the Hindu Month field may be recorded as not applicable where appropriate.

## 7. Limitations

The following limitations should be considered when using this dataset:

- The level of detail varies between records.
- Festival names, dates, rituals, and practices may differ across sources and over time.
- The dataset does not cover every festival celebrated in Maharashtra.
- Regional classifications reflect the information available during dataset preparation.
- Some fields, including Religion and Hindu Month, may contain different spellings or representations for equivalent categories.
- Missing information may affect analyses that require complete records.
- Entries in Multiple Regions may overlap with individual regional worksheets or refer to broader geographical contexts.
- Source references and individual factual claims should be independently checked before the dataset is treated as verified ground truth.

The dataset is a structured cultural documentation resource and should not be considered an exhaustive or fully validated inventory of Maharashtra's festivals.

## 8. Usage Guidelines

Users are encouraged to follow these guidelines when working with the dataset:

1. Use `Festival Id` to reference individual records.
2. Consult source references before relying on factual details.
3. Document any data cleaning, corrections, or transformations.
4. Handle `N/A` values appropriately for the intended analysis.
5. Check for overlapping records before calculating the number of unique festivals.
6. Verify regional classifications and calendar information where accuracy is important.
7. Cite the dataset when using it in academic research, reports, or publications.

## 9. Use of AI Tools

ChatGPT and Claude were used to paraphrase descriptive text included in the dataset.

The dataset's source references should be consulted when verifying factual information. The use of AI tools for paraphrasing does not, by itself, establish the accuracy of the descriptions.

## 10. Creators, License, and Contact

### Creators

- **Monika Mohandule** — Pimpri Chinchwad College of Engineering, Pune, India
- **Divya Bobade** — Pimpri Chinchwad College of Engineering, Pune, India
- **Tanuja Babaleshwar** — Pimpri Chinchwad College of Engineering, Pune, India
- **Anuradha Wagh** — Pimpri Chinchwad College of Engineering, Pune, India

### Contact

- Monika Mohandule: monikamohandule1702@gmail.com
- Divya Bobade: divyabobade907@gmail.com
- Tanuja Babaleshwar: tanujababaleshwar18@gmail.com
- Anuradha Wagh: waghuano05@gmail.com

### License

This dataset is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license, to the extent that the creators hold the necessary rights to license the material.

Under this license, users may share and adapt the dataset for any purpose, including commercial use, provided they give appropriate attribution, link to the license, and indicate whether changes were made.

**License:** [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/)

**Suggested attribution:**

Mohandule, M., Bobade, D., Babaleshwar, T., & Wagh, A. (2026). *Maharashtra Festivals Dataset* (Version 1.0).

Third-party source material may remain subject to its original copyright and licensing terms.

## 11. Citation

Suggested citation:

Mohandule, M., Bobade, D., Babaleshwar, T., & Wagh, A. (2026). *Maharashtra Festivals Dataset* (Version 1.0) [Data set]. GitHub repository[https://github.com/monikamohandule1702-web/Maharashtra-cultural-festivals-dataset.git
]

For formal citation, add the repository URL and, if available, the DOI assigned to the published dataset on Zenodo.

## 12. Version History

### Version 1.0

- Initial public release.
- 323 worksheet records across six regional classifications.
- One combined Excel workbook and six regional CSV files.
- Structured festival information covering geographical, religious, historical, and cultural attributes.

---

## Acknowledgement

This dataset aims to support the documentation and study of Maharashtra's diverse regional festivals and cultural traditions. Further source verification, corrections, and contributions can help improve its completeness and usefulness for research.
