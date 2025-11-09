🩺 Medical Knowledge Graph using Neo4j
A graph-based healthcare data model built using Neo4j to connect Doctors, Diseases, and Medicines through real-world relationships. 
This project demonstrates how graph databases can efficiently represent and query complex medical relationships compared to traditional relational systems.

🧠 Problem Statement
Healthcare data is often scattered across different tables and sources — making it difficult to answer questions like:
“Which medicine is prescribed for a particular disease?”
“Which doctor recommends treatment for a disease?”
“What medicines are commonly used for diseases suggested by a particular doctor?”
Traditional relational databases require multiple joins for these queries, making them slow and hard to scale.
Neo4j solves this by modeling entities as nodes and their relationships directly in the database.

💡 Project Objective
To build a medical recommendation graph that visually and logically represents:
Doctors → Diseases they suggest treatments for
Diseases → Medicines prescribed for them
This helps quickly explore and analyze healthcare relationships.

🧰 Tech Stack
Component : Technology
Database : Neo4j
Query Language : Cypher
Visualization : Neo4j Browser / Bloom

🚀 Impact / Outcome
Simplified medical recommendation discovery using relationship-driven querying.
Demonstrated how graph databases outperform relational systems for interconnected data.
