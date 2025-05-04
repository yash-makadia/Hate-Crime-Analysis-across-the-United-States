# Hate Crime Analysis Across the United States

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

## Overview

This data visualization project analyzes hate crimes and human trafficking across the United States using Tableau, providing insights into crime patterns, offender profiles, and trends to inform policy and awareness. Through four interactive dashboards hosted on Tableau Public, the project explores hate crime incidents, victim impacts, offender demographics, and human trafficking cases, leveraging data from the Federal Bureau of Investigation (FBI).

**Tableau Public Story**: [US Crime Analysis Data Vis](https://public.tableau.com/app/profile/yash.makadia/viz/USCrimeAnalysisDataVis/Story1)

## Features

- **Interactive Dashboards**: Four Tableau dashboards explore hate crime trends, offender demographics, human trafficking cases, and project context.
- **Deep Insights**: Highlights rising hate crimes (e.g., 2020 surge), state-specific patterns (e.g., California, Texas), and bias motivations (e.g., race, religion).
- **Actionable Recommendations**: Guides law enforcement and policymakers to address crime through targeted interventions.
- **Public Access**: Hosted on Tableau Public for broad accessibility.

## Dataset

The project leverages two FBI Uniform Crime Reporting (UCR) datasets:

- **Hate Crime Dataset**:
  - **Size**: 226,000 rows, 28 columns, 4.57 MB.
  - **Content**: Annual statistics on bias-motivated crimes (e.g., race, gender, religion, disability, sexual orientation, ethnicity), including incidents, offenses, victims, and offenders.
  - **Source**: FBI Hate Crime Statistics ([Placeholder: https://www.fbi.gov/services/cjis/ucr/hate-crime]).
- **Human Trafficking Dataset**:
  - **Size**: 3,099 rows, 19 columns, 83.3 KB.
  - **Content**: Offenses and arrests for commercial sex acts and involuntary servitude, reported since 2013.
  - **Source**: FBI UCR Human Trafficking Data ([Placeholder: https://www.fbi.gov/services/cjis/ucr/human-trafficking]).

**Access**: Download datasets from the FBI UCR Program. Update links: [Hate Crime Dataset](https://www.fbi.gov/services/cjis/ucr/hate-crime) | [Human Trafficking Dataset](https://www.fbi.gov/services/cjis/ucr/human-trafficking).

## Visualizations

The Tableau Story, accessible at [https://public.tableau.com/app/profile/yash.makadia/viz/USCrimeAnalysisDataVis/Story1](https://public.tableau.com/app/profile/yash.makadia/viz/USCrimeAnalysisDataVis/Story1), includes four dashboards:

- **Dashboard 1: Crime Overview**  
  Visualizes hate crime trends (1991–2021), showing a sharp increase in victims in 2020 (linked to COVID-19 and social unrest, e.g., anti-Asian and anti-Black crimes). Displays 226,000 total incidents, with California as a hotspot. Breaks down crimes by category (e.g., against people, property), highlighting intimidation as the top offense.  
  ![Crime Overview](screenshots/dashboard1.png)

- **Dashboard 2: Offender Profiles and Hate Crime Patterns**  
  Profiles offenders, with California leading (39,329 incidents). Highlights bias types: racial (California), religious (New York), gender (Michigan), disability (Ohio). Cites incidents like the Charlottesville rally and Charleston church shooting, emphasizing divisive ideologies. Maps crime hotspots (e.g., service/gas stations).  
  ![Offender Profiles](screenshots/dashboard2.png)

- **Dashboard 3: Human Trafficking**  
  Focuses on human trafficking, with Texas reporting the highest cases (42.83% Trafficking Elimination Index). Compares actual vs. cleared cases, showing trends and offense subcategories (Commercial Sex Acts, Involuntary Servitude). Lists top 15 states and provides the National Human Trafficking Hotline.  
  ![Human Trafficking](screenshots/dashboard3.png)

- **Dashboard 4: Data Overview and Project Summary**  
  Summarizes FBI dataset characteristics and project objectives. Highlights key findings (e.g., 2020 crime surge, state-specific biases) and recommends interventions for law enforcement and policymakers.  
  ![Data Overview](screenshots/dashboard4.png)

## Setup Instructions

### Prerequisites
- **Tableau Public**: Free account to view the story.
- **Web Browser**: For Tableau Public and dataset access.
- **Optional**: Tableau Desktop (free trial or licensed) for local workbook exploration.

### Installation
1. **View the Tableau Story**:
   - Visit [https://public.tableau.com/app/profile/yash.makadia/viz/USCrimeAnalysisDataVis/Story1](https://public.tableau.com/app/profile/yash.makadia/viz/USCrimeAnalysisDataVis/Story1).
   - Use filters and tooltips to explore dashboards.
2. **Download Datasets**:
   - Access FBI UCR datasets: [Hate Crime](https://www.fbi.gov/services/cjis/ucr/hate-crime) | [Human Trafficking](https://www.fbi.gov/services/cjis/ucr/human-trafficking) [Update with actual links].
   - Save locally for reference.
3. **Clone the Repository** (optional):
   ```bash
   git clone https://github.com/yash-makadia/Hate-Crime-Analysis-across-the-United-States.git
   cd Hate-Crime-Analysis-across-the-United-States
   ```
4. **Add Screenshots**:
   - Capture dashboard images from Tableau Public.
   - Save as `dashboard1.png`, `dashboard2.png`, etc., in `screenshots/`.
   - Commit to repository.

## Key Findings

- **Hate Crime Surge**: Victims increased significantly in 2020, driven by anti-Asian and anti-Black incidents during COVID-19 and Black Lives Matter protests.
- **Regional Hotspots**: California leads in hate crimes (39,329 incidents), followed by New York and Michigan, with biases varying by state (e.g., racial in California, religious in New York).
- **Crime Types**: Intimidation is the most common hate crime, with service/gas stations as frequent hotspots.
- **Human Trafficking**: Texas has the highest cases, with a 42.83% case resolution rate. Commercial Sex Acts and Involuntary Servitude dominate offenses.
- **Social Impact**: Events like the Charlottesville rally and Charleston shooting highlight divisive ideologies fueling hate crimes.

## Impact and Recommendations

- **Law Enforcement**:
  - Allocate resources to hotspots like California and Texas.
  - Collaborate with organizations like the Anti-Defamation League to address bias-driven crimes.
  - Promote the National Human Trafficking Hotline (1-888-373-7888) for reporting.
- **Policymakers**:
  - Develop targeted policies for prevalent biases (e.g., racial, religious).
  - Address socioeconomic triggers like unemployment to reduce crime.
- **Community Impact**:
  - Enhance public safety through data-driven resource allocation.
  - Increase awareness of hate crimes and human trafficking via visualizations.
  - Support victims through outreach and hotlines.

## Project Files

- `README.md`: Project overview and instructions.
- `screenshots/`:
  - `dashboard1.png`: Crime Overview
  - `dashboard2.png`: Offender Profiles
  - `dashboard3.png`: Human Trafficking
  - `dashboard4.png`: Data Overview
- `LICENSE`: GNU General Public License v3.0.

## Challenges and Lessons Learned

- **Data Scale**: Processing 226,000 rows of hate crime data required optimized Tableau workflows.
- **Data Integration**: Combining hate crime and human trafficking datasets with different structures was complex.
- **Lessons**:
  - Tableau’s interactive features enhance stakeholder engagement.
  - Clear visualizations simplify complex crime data for decision-makers.

## Future Scope

- Add datasets (e.g., FBI violent crime statistics) for broader analysis.
- Implement time-series forecasting for crime trends.
- Develop an API for real-time crime data access.
- Create mobile-optimized Tableau dashboards.

## References

- FBI Hate Crime Statistics: [https://www.fbi.gov/services/cjis/ucr/hate-crime](https://www.fbi.gov/services/cjis/ucr/hate-crime) [Update with actual link].
- FBI Human Trafficking Data: [https://www.fbi.gov/services/cjis/ucr/human-trafficking](https://www.fbi.gov/services/cjis/ucr/human-trafficking) [Update with actual link].
- Tableau Public: [https://public.tableau.com/](https://public.tableau.com/)
- Anti-Defamation League: [https://www.adl.org/](https://www.adl.org/)
- National Human Trafficking Hotline: [https://humantraffickinghotline.org/](https://humantraffickinghotline.org/)

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file.

## Contributing

Fork the repository, create a branch, and submit a pull request with GPL-3.0-compliant changes.

## Contact

For questions, open a GitHub issue or contact Yash Makadia at [yashmakadia1908@gmail.com](mailto:yashmakadia1908@gmail.com).

## Acknowledgments

Thanks to the FBI for UCR datasets.