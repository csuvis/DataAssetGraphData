# An Open Dataset of Data Asset Graphs for Data Governance Research (DLG-DR-23)

Data have become valuable assets for enterprises. Data governance aims to manage and reuse data assets to facilitate enterprise management and product innovations. A data lineage graph (DLG) is an abstracted collection of data assets and their data lineages in a business application scenario. Analyzing DLGs provides rich data insights for data governance. For example, DLGs provide enterprises with a bird’s-eye view of entire data assets and their processing life cycle, thereby supporting a wide range of crucial requirements of data governance. However, there is a lack of open DLG datasets for data governance because of privacy and security concerns. 

DataAssetGraphData is a data asset graph dataset, aiming to facilitate the research and development of relevant methods and techniques for data governance. This dataset is a real-world dataset sourced from Huawei Cloud Computing Technologies Company Limited. The dataset contains 18 DLGs with diverse sizes from 278 nodes to 17,085 nodes. Each DLG contains the three most common types of data assets (nodes) and two types of relations (edges). 

Each DLG is stored in a Node.json file and an Edge.json file. The Node.json file has two fields to provide the information of a data asset and the Edge.json file has four fields to provide the information of a relation. All Node.json files and Edge.json files are compressed into a Node.rar file and an Edge.rar file, respectively.
