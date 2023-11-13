(er-datahazardsintro)=
# Introduction to Data Hazards Project
<!--`data-hazards-intro.md` -->

Data Hazards is a community project to develop a shared vocabulary of data science risks (in the form of Data Hazard labels) and materials to help data practitioners use them.

These labels and materials are provided CC-BY licensed on the [Data Hazards website](https://datahazards.com).
They exist to facilitate interdisciplinary discussions and self-reflection about all kinds of data ethics risks. 
Ultimately, the project aims to help data practitioners to identify and mitigate these risks.
You can watch a short animation explaining the project below:

<div style="text-align: center">
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/26fNnar4JvY?controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

In this section, we explain the nature of the project.
Feel free to skip ahead to the next section for more practical guidance on {ref}`how to use the Data Hazards<(er-datahazardshowtouse>` in your data-intensive work. 

## Data Hazards labels


### What do they look like? Anatomy of a Data Hazards label

Each label has: 

- **Hazard image**, title, and description which represents and describes the risk.
- **Examples** to clarify what the hazard covers.
- **Safety Precautions** - things that we would want to see done before the research is deployed.

### Example label: high environmental cost
> [name=Alejandro ©] very interested to mention or crossreference this in the WIP chapter on The Environmental Impact of Digital Research, https://github.com/alan-turing-institute/the-turing-way/pull/3117
---
<center><img src="https://datahazards.com/_images/environment.png"  width="250" height=""></center>

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

## Application example into Research life-cycle
To help visualize where and when Data Hazards can be used in your workflow, below we use an example assuming four main stages of workflow: design, data collection, data analysis and reporting.


#### Design:
 - Are you using data? Then doing some reflection on [identity and positionality](https://the-turing-way.netlify.app/ethical-research/self-reflection/sr-positionality.html?highlight=bias) could help you think of what Data Hazards labels you might encounter as you design your project, for example ["ranks of classifies people hazard"](https://datahazards.com/contents/hazards/ranks-classifies.html) or ["risk to privacy"](https://datahazards.com/contents/hazards/risk-to-privacy.html) could apply at this stage.
 - In this part of the workflow, you might want to prepare to avoid certain Data Hazards if you can, and if you can't avoid them because of where your data has come from, you may want to acknowledge this. For example, if you a [sensitive data project](https://the-turing-way.netlify.app/project-design/sdp.html), what Data Hazard labels will apply, and/or what can you do to design your project in a way that avoids certain harms?
 
#### Data Collection and Analysis:
 - As you are collecting and analyzing your data, you might want to iteratively think of the potential Data Hazards that exist in the information you are collecting. To then apply the labels as you perform the next step of the process: reporting.

#### Reporting:
 - When reporting your results, you can think of applying and reporting the Data Hazard labels that are relevant for your project; examples of how others have done this can be found here [link to self reflection and case studie(s)]. Labeling your project with Data Hazards should also include considerations of mitigations to these risks. This would then be helpful for people who see your outputs in the future. They can be aware of potential risks as they proceed with the project, and continue to think of solutions to any issues related to the research topic.



## Glossary

- risk:
- hazard:
- danger:
