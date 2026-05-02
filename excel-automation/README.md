# ETL Automation for Manufacturing Data – VBA Macro

## Business Problem
In a Tier 1 aerospace manufacturing plant, 10 engineers spent 20 minutes per day manually extracting data from multiple sources and entering it into Excel. This process was:
- Time-consuming: 3.3 engineer-hours lost daily
- Error-prone: manual typing led to data inconsistencies
- Delaying reporting: production decisions based on outdated data

## Solution
I developed a VBA macro that:
1. Extracts data from source files (CSV, SAP exports)
2. Transforms data (cleaning, formatting, validation)
3. Loads data into a central Excel dashboard in 5 minutes total

## Key Results
- **Time saved:** 3.3 engineer-hours per day → ~80 hours/month
- **Error reduction:** 90% decrease in manual lookup errors
- **Productivity boost:** 2 hours/week per designer saved

## Technology Stack
- **VBA (Excel):** Automation, data transformation, error handling
- **Power Query (optional):** Data connection and refresh
- **Excel:** User interface and reporting

## Code Snippet (simplified)
```vba
Sub ETL_ProductionData()
    ' Step 1: Extract
    Workbooks.Open "source_data.csv"
    ' Step 2: Transform
    Range("A1:D1000").Copy
    ' Step 3: Load
    ThisWorkbook.Sheets("Dashboard").Range("A1").PasteSpecial
    Application.CutCopyMode = False
    MsgBox "ETL completed in " & Timer - start & " seconds"
End Sub
