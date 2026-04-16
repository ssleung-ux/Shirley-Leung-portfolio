| [home page](https://ssleung-ux.github.io/Shirley-Leung-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one.md) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Outline
Auto insurance premiums vary widely across U.S. states, but higher costs don’t always align with greater driving risk.  

This project uses data visualization to examine the gap between what drivers pay and key risk factors such as fatal crash and uninsured motorist rates, highlighting states that stand out as outliers.  

It also explores how factors like state regulation and litigation patterns may drive premiums higher than road risk alone would justify.

## Project Structure 

**One sentence summary:** Millions of American drivers pay insurance premiums influenced more by state legal and regulatory systems than by actual driving risk

**Story arc:**
<img width="2200" height="1577" alt="image" src="https://github.com/user-attachments/assets/66cc9897-15cd-486a-852e-20bb46128bed" />


## Initial sketches
**Average auto insurance premium price by state**
<img width="1183" height="1075" alt="image" src="https://github.com/user-attachments/assets/138c0323-8faf-47ce-9454-67aa8dc63d94" />  

**Scatter plot - Relationship between premium vs. Fatality rate by country**
<img width="1326" height="1460" alt="image" src="https://github.com/user-attachments/assets/a2a610a1-34e5-4b15-9fcb-b4fe5f59e9b2" />




# The Data
The primary source for premium data is the NAIC 2023 Auto Insurance Database Average Premium Supplement, published June 2025. This report provides state-level average expenditure and combined average premium per insured vehicle for 2019–2023, broken down by liability, collision, and comprehensive coverage.  

For the risk side, I will use state-level fatal crash rates published by the Insurance Institute for Highway Safety (IIHS), expressed as deaths per 100 million vehicle miles traveled. This normalized metric controls for differences in population in each state and driving volume, making this the appropriate way to analyze risk across states.

| Name | URL | Description |
|------|-----|-------------|
|IIHS State-by-State Fatality Statistics 2023|[Link](https://www.iihs.org/research-areas/fatality-statistics/detail/state-by-state)|The Insurance Institute for Highway Safety publishes state-level fatal crash rates expressed as deaths per 100 million vehicle miles traveled (VMT). This normalized metric is an appropriate measure of road risk for cross-state comparisons, as it controls for differences in state size and total driving volume.  This is the primary risk variable that will be plotted against premium data in the scatter plot.|
|NAIC 2023 Auto Insurance Database Average Premium Supplement|[Link](https://content.naic.org/sites/default/files/aut-db_1.pdf)|State-level average auto insurance expenditure and combined average premium, 2019–2023|
|NHTSA FARS National CSV|[Link](https://www.nhtsa.gov/crash-data-systems/fatality-analysis-reporting-system)|Census of all U.S. fatal crashes by state, used as verification source, as IIHS's source is from here|  
|U.S census |[link](https://www.census.gov/data/datasets/time-series/demo/popest/2020s-counties-total.html)|  |

# Method and medium
This project will be built using Shorthand as the primary storytelling platform, with all data visualizations created in Tableau Public. Shorthand's scroll-driven format is well-suited to the narrative arc structure. Each section of the story maps naturally to a Shorthand scroll section, with Tableau visualizations embedded inline.

# Call to actions
This project aims to inform drivers and policymakers about structural inefficiencies in state auto insurance markets. By highlighting the gap between premiums and underlying risk, it encourages evaluation of whether current rate regulation frameworks are functioning as intended. It also underscores the need for potential reforms in states where pricing remains persistently misaligned.

## AI acknowledgements
Claude (Sonnet 4.6) is used to brainstorm the project topic, identify appropriate public data sources, and draft initial text for the outline and sections. All final content was reviewed and edited by me.
