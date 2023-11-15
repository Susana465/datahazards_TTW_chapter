(er-datahazardsintro)=
# Introduction to Data Hazards Project

Data Hazards is a community project to develop a shared vocabulary of data science risks (in the form of Data Hazard labels) and materials to help data practitioners use them.

These labels and materials are provided CC-BY licensed on the [Data Hazards website](https://datahazards.com).
They exist to facilitate interdisciplinary discussions and self-reflection about all kinds of data ethics risks. 
Ultimately, the project aims to help data practitioners to identify and mitigate these risks.
You can watch a short animation explaining the project below:

[INSERT VIDEO HERE]

## Data Hazards labels
In this section, we explain the nature of the project.
Feel free to skip ahead to the next section for more practical guidance on {ref}`how to use the Data Hazards<(er-datahazardshowtouse>` in your data-intensive work. 

### What do they look like? Anatomy of a Data Hazards label

Each label has: 

- **Hazard image**, title, and description which represents and describes the risk.
- **Examples** to clarify what the hazard covers.
- **Safety Precautions** - things that we would want to see done before the research is deployed.

### Example label: high environmental cost

[IMAGE GOES HERE]

#### Description
This hazard is appropriate where methodologies are energy-hungry, data-hungry (requiring more and more computation), or require special hardware that require rare materials.

#### Examples
 - Example 1: Cryptocurrency requires vast energy usage.
 - Example 2: Language models require larger and larger datasets.

#### Safety Precautions
 - Consider in what circumstances it is worthwhile to use this type of methodology.
   - To communicate the scale of the issue to other stakeholders, you may want to [convert units of energy into more relatable units]().
   - Find out [if your cloud provider uses renewable energy]().
   - Consider profiling your code, and rewriting it to use less energy.
   
- Consider future work that would reduce the need to use increasingly more resources.

---

### Similarities and differences to chemical hazard labels
<!--The Data Hazards labels look like chemical hazard labels on purpose...-->


### Where did they come from?
There were originally six labels, which were identified through reading data ethics papers at [Data Ethics Club](http://dataethicsclub.com): a fortnightly journal club for data science and ethics.
Through collecting suggestions [on GitHub](), and at conferences and Data Hazards workshops, further labels were suggested and added until we reached the current 11 labels.

### The Hazard labels are versioned
<!--The Hazard labels are versioned!-->
The Data Hazard labels are a living project and will continue to change as we gather more suggestions - for this reason they are versioned using semantic versioning.
At the time of writing, in `v1.0`, there are 11 Data Hazard labels: you can [explore the Data Hazard labels yourself](https://datahazards.com/labels) on the Data Hazards website.



## Glossary

- risk:
- hazard:
- danger:
