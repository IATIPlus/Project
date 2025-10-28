![IATI Plus Logo](https://github.com/IATIPlus/Project/blob/main/Media/IATIPlus-Header.png)
# An Extensible IATI Database Clone for AI Research

**IATI Plus** is a comprehensive, graph-based representation of the entire [IATI](https://iatistandard.org/en/) corpus. IATI is an XML standard and open data sharing framework that is widely used across the humanitarian and development communities by organizations to share granular information on aid activities, transactions and results. IATI Plus is high-performance graph database developed by volunteers supported by [Neo4j](https://neo4j.com/) to advance and accelerate humanitarian AI research and advanced analytics. 

Given IATI's complex XML structure, which includes hundreds of unique elements and attributes, traditional data testing methods fall short. IATI Plus is specifically designed to support highly complex query testing, enabling researchers and developers to query all of IATI's interconnected elements in ways not feasible with standard tools. The graph database provides a stable sandbox for building and rigorously testing commercial-grade AI applications operating at scale. Its extensibility also allows teams to experiment with new IATI information fields or data models without impacting or requiring any changes to the official IATI standard.

## Core Work Areas

IATI Plus is a collaborative, all-volunteer initiative, bringing together a diverse community of students, researchers, AI experts, private sector companies, and humanitarian organizations. The project's efforts are focused on three core work areas: aggregating, preparing, and storing data in a dedicated repository; developing and refining the central high-performance graph database; and building a library of complex sample queries for researchers to test.

| Work Areas  | Description |
| ------------- | ------------- |
| IATI Data Snapshot [Repository](https://github.com/IATIPlus/Project/tree/main/Repository)  | IATI makes daily snapshots of its entire XML corpus available for researchers to download directly, each segmented into hundreds of subfolders by publishing organization. Volunteers are developing an automated data pipeline to fetch and unzip these daily snapshots, and consolidate the thousands of individual XML files they contain into a single, day-stamped master XML file. These master files are archived in a cloud data repository. This process builds a complete longitudinal record, allowing researchers to track data changes over time and compare different historical snapshots in novel ways. |
| IATI Plus Graph [Database](https://github.com/IATIPlus/Project/tree/main/Database)  | This core work area focuses on the database itself. Volunteers will use the day-stamped master XML files to build and continuously update the IATI Plus graph database, keeping it synchronized with the official IATI corpus. The team will also focus on optimizing the graph’s structure for efficient traversal by AI applications and developing guidance on effective query design and best practices. |
| Research [Questions](https://github.com/IATIPlus/Project/tree/main/Questions)  | This final work area is dedicated to building a comprehensive library of sample questions to validate the database and test AI applications. Volunteers will focus on the end-to-end query process: from translating complex, natural-language questions into executable Cypher query statements, to synthesizing the raw data outputs back into meaningful answers. The team will also develop a scalable framework for generating and evaluating these test questions, ensuring they cover a wide vertical and horizontal range of humanitarian and development use cases. |

## Get Involved

We are an open-source, volunteer-driven project actively seeking contributors of all skill levels. You can help by checking our open issues, improving documentation, or submitting a pull request. To learn more and join the community, please email us at: team(at)humanitarianai.org
