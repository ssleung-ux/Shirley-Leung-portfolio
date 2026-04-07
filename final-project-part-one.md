| [home page](https://ssleung-ux.github.io/Shirley-Leung-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Outline
Auto insurance premiums vary widely across U.S. states, but higher costs don’t always align with greater driving risk.  

This project uses data visualization to examine the gap between what drivers pay and key risk factors such as fatal crash and uninsured motorist rates, highlighting states that stand out as outliers.  

It also explores how factors like state regulation and litigation patterns may drive premiums higher than road risk alone would justify.

## Project Structure 
> A project structure that outlines the major elements of your story.  Your Good Charts text talks about story structure in Chapter 8 - you should describe what you hope to achieve.  Make sure the outline is detailed enough that we can see how you anticipate your story unfolding.  You can incorporate your Story Arc from the in-class exercise along with your user stories and one sentence summary to make the topic even more clear. 

**One sentence summary:** Millions of American drivers pay insurance premiums influenced more by state legal and regulatory systems than by actual driving risk

**Story arc:**

## Initial sketches
> Post images of your anticipated data visualizations (sketches are fine). They should mimic aspects of your outline, and include elements of your story.  

Text here...

# The Data
The primary source for premium data is the NAIC 2023 Auto Insurance Database Average Premium Supplement, published June 2025. This report provides state-level average expenditure and combined average premium per insured vehicle for 2019–2023, broken down by liability, collision, and comprehensive coverage.  

For the risk side, I will use state-level fatal crash rates published by the Insurance Institute for Highway Safety (IIHS), expressed as deaths per 100 million vehicle miles traveled. This normalized metric controls for differences in population in each state and driving volume, making this the appropriate way to analyze risk across states.

| Name | URL | Description |
|------|-----|-------------|
|IIHS State-by-State Fatality Statistics 2023|[Link](https://www.iihs.org/research-areas/fatality-statistics/detail/state-by-state)|The Insurance Institute for Highway Safety publishes state-level fatal crash rates expressed as deaths per 100 million vehicle miles traveled (VMT). This normalized metric is an appropriate measure of road risk for cross-state comparisons, as it controls for differences in state size and total driving volume.  This is the primary risk variable that will be plotted against premium data in the scatter plot.|
|NAIC 2023 Auto Insurance Database Average Premium Supplement|[Link](https://content.naic.org/sites/default/files/aut-db_1.pdf)|State-level average auto insurance expenditure and combined average premium, 2019–2023|
|NHTSA FARS National CSV|[Link](https://www.nhtsa.gov/crash-data-systems/fatality-analysis-reporting-system)|Census of all U.S. fatal crashes by state, used as verification source, as IIHS's source is from here|

# Method and medium
This project will be built using Shorthand as the primary storytelling platform, with all data visualizations created in Tableau Public. Shorthand's scroll-driven format is well-suited to the narrative arc structure. Each section of the story maps naturally to a Shorthand scroll section, with Tableau visualizations embedded inline.

## AI acknowledgements
Claude (Sonnet 4.6) is used to brainstorm the project topic, identify appropriate public data sources, and draft initial text for the outline and sections. All final content was reviewed and edited by me.
