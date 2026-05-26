# asrcc-brown-act
Research for 2025-2026 ASRCC Brown Act, Constitution and By-laws violations

## Agendas and Minutes tracking
### 01. Spreadsheet
- Meeting Dates
  - Downloaded the .pdf for the 2025-2026 RCC Academic Calendar
  - Created Google Sheet named [Meeting Tracking - ASRCC 2025-2026](https://docs.google.com/spreadsheets/d/1mxfPxMiVDVNrb7syJd-Gruj0gEm93AisqaW0rDH2USk/edit?usp=sharing)
  - Created top row headings
    - Week, Branch, <Term> Agenda, <Term> Minutes
  - Renamed Sheet1 to Summer
  - Copied Summer three times
  - Renamed Sheet2 to Fall, Sheet3 to Winter, Sheet4 to Spring
  - Filled Week column in Summer, Fall, Winter, Spring with dates from 2025-2026 RCC Academic Calendar
    - Note CON/BYLAWS state ASRCC only needs to meet twice during the off terms of Summer and Winter
  - Filled Branch column in Summer, Fall, Winter, Spring with Branch names
    - Executive, Senate, Court
- Filled Agenda, Minutes in Summer, Fall, Winter, Spring with Y/N based on presence of documents in ASRCC (Public)
  - A copy of ASRCC (Public) made on May 15, 2026 may be found here.
- Added Totals columns to count Ys in Agenda, Physical and Minutes columns of Summer, Fall, Winter, Spring Sheets
  - Changed row color to light blue
- Added new Sheet named Calculations
  - Added columns for Meetings (B), Agendas (C), Minutes (D),	Share of Meetings with an Agenda (E),	Share of Meetings with Minutes (F)
  - Added rows for Executive (2), Senate (3)
  - Added row counts for number of total meeting dates in Meetings column
  - Added row counts for number of total agendas in Agenda column
  - Added row counts for number of total minutes in Minutes column
  - Added formula "=C2/B2" in E2 to show share of meetings with an agenda for Executive
  - Added formula "=C3/B3" in E3 to show share of meetings with an agenda for Senate
  - Added formula "=D2/B2" in F2 to show share of meetings with an agenda for Executive
  - Added formula "=D3/B3" in F3 to show share of meetings with an agenda for Senate
- Recorded dates from [ASRCC email](https://github.com/rccvpaaron/asrcc-brown-act/blob/main/Meeting%20Email/Upcoming%20public%20meeting%20schedule.pdf) to Viewpoints about missed meeting dates
- Added chart to Calculations
  - Added column Total Agendas starting at B6
  - Added column Agendas Missed starting at C6
  - Added row Executive starting at A7
  - Added row Senate starting at A87
  - Added formula "=C2" to B7
  - Added formula "=C3" to B8
  - Added formula "=SUM(B2-C2)" to C7
  - Added formula "=SUM(B3-C3)" to C8

## 02. Creating the Datawrapper Charts
### Number of online agendas vs. regularly-scheduled meetings for ASRCC, 2025-2026
1. Upload Data
- Copied A1:D2 from the data table in Calculations sheet of Meeting Tracking - ASRCC 2025-2026
- Pasted A1:D2 from the data table in Calculations sheet of Meeting Tracking - ASRCC 2025-2026 into Copy & Paste Data Table field in Upload Data section of a New Chart
2. Check & Describe
- No changes
- "First row as label" box selected
3. Visualize
- Chart Type: Bullet Bars
- Refine:
  * Bars
    + Outer bar: Meetings
    + Inner bar: Agendas
  * Labels
    + Alignment: Left
    + Replace country codes with flags: No
    + Show color legend: Yes
    + Stack labels: Unselected
  * Horizontal axis
    + Custom range: min - 33
    + Number format: 1,000.00
    + Custom grid lines: Empty
    + Tick postiion: below
    + Select column: Academic Year
    + Grid: off
  * Appearance
    + Outer color: #18a1cd
    + Inner color: #00dca6
    + Thicker bars: Unselected
    + Separating lines: Unselected
  * Sorting & Grouping
    + Sort bars: Unselected
    + Reverse order: Unselected
- Annotate:
  * Title: Number of online agendas vs. regularly-scheduled meetings for ASRCC, 2025-2026
  * Description: Empty
  * Notes: Some regular meetings were cancelled, but those dates were never released to the public so the total number of meetings may be inaccurate. 
  * Data Source: ASRCC website
  * Link to data source: https://drive.google.com/drive/u/0/folders/1KTJiUQIWujfgkhZuU2dNz9TpmfrY_2DJ
  * Byline: Aaron Friesen
  * Alternative description for screen readers: A bullet bar chart comparing the number of agendas posted online by ASRCC versus the number of meetings scheduled. Agendas are low in comparison with number of meetings form both Executive and Senate.
  * Highlight elements: Unselected
  * Text annotations: None
  * Highlight range: None
- Layout:
  *  Output locale: English (en-US)
  *  Layout
    + Theme: Datawrapper
    + Automatic dark mode: Unselected
    + Use the same colors in dark mode: Unselected
  * Footer
    + Data download: on
    + Image download options: PNG
    + Embed link: off
    + Datawrapper attribution: on
  * Share buttons
    + Social media share buttons: off
### Number of online minutes vs. regularly-scheduled meetings for ASRCC, 2025-2026
1. Upload Data
- Copied A1:D3 from the data table in Calculations sheet of Meeting Tracking - ASRCC 2025-2026
- Pasted A1:D3 from the data table in Calculations sheet of Meeting Tracking - ASRCC 2025-2026 into Copy & Paste Data Table field in Upload Data section of a New Chart
2. Check & Describe
- No changes
- "First row as label" box selected
3. Visualize
- Chart Type: Bullet Bars
- Refine:
  * Bars
    + Outer bar: Meetings
    + Inner bar: Minutes
  * Labels
    + Alignment: Left
    + Replace country codes with flags: No
    + Show color legend: Yes
    + Stack labels: Unselected
  * Horizontal axis
    + Custom range: min - 33
    + Number format: 1,000.00
    + Custom grid lines: Empty
    + Tick postiion: below
    + Select column: Academic Year
    + Grid: off
  * Appearance
    + Outer color: #18a1cd
    + Inner color: #00dca6
    + Thicker bars: Unselected
    + Separating lines: Unselected
  * Sorting & Grouping
    + Sort bars: Unselected
    + Reverse order: Unselected
- Annotate:
  * Title: Number of online minutes vs. regularly-scheduled meetings for ASRCC, 2025-2026
  * Description: Empty
  * Notes: Some regular meetings were cancelled, but those dates were never released to the public so the total number of meetings may be inaccurate. 
  * Data Source: ASRCC website
  * Link to data source: https://drive.google.com/drive/u/0/folders/1KTJiUQIWujfgkhZuU2dNz9TpmfrY_2DJ
  * Byline: Aaron Friesen
  * Alternative description for screen readers: A bullet bar chart comparing the number of minutes posted online by ASRCC versus the number of meetings scheduled. Agendas are low in comparison with number of meetings form both Executive and Senate.
  * Highlight elements: Unselected
  * Text annotations: None
  * Highlight range: None
- Layout:
  *  Output locale: English (en-US)
  *  Layout
    + Theme: Datawrapper
    + Automatic dark mode: Unselected
    + Use the same colors in dark mode: Unselected
  * Footer
    + Data download: on
    + Image download options: PNG
    + Embed link: off
    + Datawrapper attribution: on
  * Share buttons
    + Social media share buttons: off
