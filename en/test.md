# SimpleText@CLEF-2021 Call for papers

[Home](https://simpletext-madics.github.io/2021/clef/en) | [Call for papers](https://simpletext-madics.github.io/2021/clef/en/CFP) | [Important dates](https://simpletext-madics.github.io/2021/clef/en/dates) | [Pilot tasks](https://simpletext-madics.github.io/2021/clef/en/tasks)  
[Program](https://simpletext-madics.github.io/2021/clef/en/program) | [Publications](https://simpletext-madics.github.io/2021/clef/en/publications) | [Organisers](https://simpletext-madics.github.io/2021/clef/en/organisers) | [Contact](https://simpletext-madics.github.io/2021/clef/en/contact) | [<img src="FR.png" width="20">](https://simpletext-madics.github.io/2021/clef/fr/task1)

---

## SimpleText Pilot Task Guidelines

We invite you to submit both automatic and manual runs! Manual intervention should be reported.

---

<button>[Access](https://simpletext-madics.github.io/2021/clef/en/tasks)</button> | <button>[Pilot task 1](https://simpletext-madics.github.io/2021/clef/en/task1)</button> | <button>[Pilot task 2](https://simpletext-madics.github.io/2021/clef/en/task2)</button> | <button>[Pilot task 3](https://simpletext-madics.github.io/2021/clef/en/task3)</button>

<br>

## Access
Please register at the SimpleText@CLEF workshop in order to access the data: [http://clef2021-labs-registration.dei.unipd.it/](http://clef2021-labs-registration.dei.unipd.it/)  
After registration, you will receive an email with information on how to log in to the data server: [https://guacamole.univ-avignon.fr](https://guacamole.univ-avignon.fr)

### Result submission:
Participants should put their run results into the folder Documents created for their user.

### 2021 DataSet
For this edition we use the Citation Network Dataset: DBLP+Citation, ACM Citation network ([https://www.aminer.org/citation](https://www.aminer.org/citation)). An elastic search index is provided to participants accessible through a GUI API. This Index is adequate to:
* apply basic passage retrieval methods based on vector or language IR models
* generate Latent Dirichlet Allocation models,
* train Graph Neural Networks for citation recommendation as carried out in [https://stellargraph.readthedocs.io/](https://stellargraph.readthedocs.io/) for example,
* apply deep bi directionnal transformers for query expansion.
* and much more …

### 2021 Queries
For this edition queries are a selection of recent n press titles from The Guardian enriched with keywords manually extracted from the content of the article. It has been checked that each keyword allows to extract at least 5 relevant abstracts. The use of these keywords is optional.

*Input format for all tasks:*
* Topics are in the MD format

* Full text articles from The Guardian (link, folder query_related_content with full texts in the MD format)
* ElasticSearch index on the following data server (e.g.): [https://guacamole.univ-avignon.fr/nextcloud/index.php/apps/files/?dir=/simpleText/queries&fileid=570352](https://guacamole.univ-avignon.fr/nextcloud/index.php/apps/files/?dir=/simpleText/queries&fileid=570352)
* DBLP full dump in the JSON.GZ format
* DBLP abstracts extracted for each topic in the following MD format (doc_id, year, abstract):

<br>

[<img src="next.png" width="30" vertical-align"middle"> PILOT TASK 1b](https://simpletext-madics.github.io/2021/clef/en/task1)




---
---
---
---


Lorem ipsum dolor sit amet, consectetur adipiscing elit. In pellentesque metus vehicula leo pellentesque, at tristique odio venenatis. Fusce faucibus lectus dolor, quis egestas erat convallis ut. Nunc iaculis faucibus dolor vel luctus. Phasellus id lorem dolor. Duis sagittis ultrices risus porttitor congue. Nullam mauris turpis, dapibus eu nisi eu, dignissim finibus nunc. Nunc neque augue, aliquet eget facilisis congue, efficitur id magna. Phasellus sollicitudin nulla consequat, tristique turpis et, semper lectus. Sed urna nisi, rhoncus vitae varius laoreet, iaculis a nisl. Quisque purus magna, consequat varius dictum euismod, eleifend a erat. Quisque ornare lacus quis dignissim pellentesque. Fusce sollicitudin, purus vitae ullamcorper bibendum, elit enim ornare tellus, non tincidunt nunc erat in magna. Nulla arcu mauris, faucibus et eros et, elementum ornare eros. Mauris in laoreet odio. Vivamus nec dapibus libero, at ullamcorper nulla.[^1]

[^1]: ok
