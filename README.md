<hr style="border:3px solid grey"> </hr>

# oi.hub.io

---

| :pushpin: <sub>**Title**</sub> | :scroll: <sub>**Project**</sub> |  :date: <sub>**Date**</sub>  | :office: <sub>**Organization**</sub> | :computer: <sub>**Author**</sub> |
|---|---|---|---|---|
|  [:link: uiHUB](https://github.com/michaelstepner/homebase-covid) | [:us: UI Claims](https://oui.doleta.gov/unemploy/uifactsheet.asp) | [:mantelpiece_clock:	 Feb, 8<sup>th</sup> 2021](https://www.daysoftheyear.com/days/2021/02/08/) | :high_brightness:	[Opportunity Insights](https://opportunityinsights.org/) | :email: [Jacob Leonard](mailto:jleonard@opportunityinsights.org) |


<hr style="border:2px solid grey"> </hr>


#### *Unemployment Insurance Data Hub*

<hr style="border:1px solid grey"> </hr>



***Purpose:*** This repo was created to help aleviate the dev pains of multiple execution environments in an academic setting. In the spirit of reproducibility and smoothing the transition between exploration, development, deployment and production , this JupyterLab implementation is used to provide quick local tools to bulild complex pipelines in jupyter.

***Concept:*** Development of new data sources and pipeline features happen in notebooks. When notebooks are completed or unitzed for pipeline processes, other notebooks are used to orchestrate the running of other notebooks in the pipeline. By parameterizing the notebooks using papermill, the notebooks can be reused, and the data architecture simplified.


_**Requirements:** [Docker Engine](https://docs.docker.com/engine/install/), [repo2Docker](https://repo2docker.readthedocs.io/en/latest/install.html#install)_

<hr style="border:2px solid grey"> </hr>

### Usage


#####


> 1. Open a terminal window navigate to the directory `uiHUB/uiClaims/`
> 2. Run the command repo2Docker



#### Tools


##### *Development*
[docker]
[repo2Docker](https://repo2docker.readthedocs.io/en/latest/usage.html)

##### *Project Structure*
CookieCutterDataScience


*Notebook Editing:*
JupyText


##### *Version Control*
[ReviewNB](https://www.reviewnb.com/)


##### *Pipelining*
[Papermill]()
[Dagster](https://github.com/dagster-io/dagster)


##### *Dashoards*
Nteract
Chartify
Panel
Pangeo
StreamLit

##### *Visualization*
[K3D](https://github.com/K3D-tools/K3D-jupyter)


##### *Reproduction*
[NBPipeline](https://pypi.org/project/nbpipeline/)
[Scrapbook]


#### Examples
[DVC & Jupyter Notebook](https://dagshub.com/DAGsHub-Official/Jupyter-Notebook-DVC/src/master/Example.ipynb)



#### Resources
[YODA](http://handbook.datalad.org/en/latest/basics/101-127-yoda.html#yoda)


#### Extensions
[Jupyter](https://github.com/jupyterlab)
[Dash]
