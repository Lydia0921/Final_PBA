# Summary of EDA

### Categorical Variables Summary

| Column | Missing (NA) | Unique Count | Example Values |
|--------|--------------|---------------|----------------|
| INDICATOR | 0 | 1 | Drug overdose death rates |
| PANEL | 0 | 6 | All drug overdose deaths; deaths involving any opioid; deaths involving natural & semisynthetic opioids; deaths involving methadone; deaths involving synthetic opioids (non-methadone); deaths involving heroin |
| UNIT | 0 | 2 | Deaths per 100,000 population (age-adjusted); Deaths per 100,000 population (crude) |
| STUB_NAME | 0 | 8 | Total; Sex; Sex and race; Sex and age; Age; Sex and race (single race); Sex and race & Hispanic origin; Sex and age (single race) |
| STUB_LABEL | 0 | Many | Sex, race, Hispanic origin, and age subgroups (e.g., Male: White; Female: Black; Male: 25–34 years; Female: 85+ years; etc.) |
| AGE | 0 | 10 | All ages; Under 15; 15–24; 25–34; 35–44; 45–54; 55–64; 65–74; 75–84; 85+ |
| FLAG | 5117 | 2 | NA; * (flagged or suppressed values) |

---

### Numerical Variables Summary

| Column | Missing (NA) | Notes |
|--------|--------------|-------|
| PANEL_NUM | 0 | Encoded PANEL categories |
| UNIT_NUM | 0 | Encoded UNIT categories |
| STUB_NAME_NUM | 0 | Encoded STUB_NAME categories |
| STUB_LABEL_NUM | 0 | Encoded STUB_LABEL categories |
| YEAR | 0 | Year as text/factor |
| YEAR_NUM | 0 | Numeric year |
| AGE_NUM | 0 | Encoded age groups |
| ESTIMATE | 1111 | Contains missing values, may require imputation or removal |
