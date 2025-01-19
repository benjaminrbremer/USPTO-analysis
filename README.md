# USPTO-analysis
Code for effectively querying the USPTO database (all patents ever applied for, and all relevant documents related to each patent. Contains code for analyzing patent statistics, and some machine learning algorithms to help gain insight into these patents.

## Project Motivation
The motivation behind this project came from a work-in-progress research paper I am writing as a part of my undergraduate ecnomics capstone project. In the paper, we reference the US Patent and Trademark Office's (USPTO) subsidized climate mitigation program that provides subsidized (free) accelerated review of patents that "contain one or more claims to a product or process that mitigates climate change" (1). It has been, thus far, extremely difficult for us to analyze the effectiveness of this program, because neither I or my co-author can quickly find patents that applied to this pilot program. My second major is computer science, with an emphasis in data and AI, so I decided to take a pass at trying to build our own solution. 

## Project Goals
The goal for this project is to have an effective way to query and analyze patents from the USPTO database. The code should be able to query beyond the abilities of the online search engine offered by the USPTO, possibly being able to word search for text within a patent, or any of the surrounding documents (ex. for our use case, looking for the pilot program application and resulting acceptance/denial). It would also be ideal to perform both basic statistical analysis of patents, as well as more in-depth analysis that could extend as far as a patent's likelyhood to get accepted into the pilot program, or its probability of subsequently getting approved. 

# External Data Requirements and Dependencies
The USPTO database is extremely large (nearly 400 GB in JSON format), so it is not included in this repository. Download it [here](https://ped.uspto.gov/peds/#/). 


## References:
(1) https://www.uspto.gov/patents/laws/patent-related-notices/climate-change-mitigation-pilot-program
