

# Wikidata Editor Network Analysis

## Introduction

The analysis provided herein focuses on the social network of editors that contribute to Wikidata, a collaborative, global, and cross-domain knowledge graph. The aim is to understand the interactions and connections between the editors using Talk pages as a primary data source.

## Data Source

The primary data consists of CSV files with three columns: page name, thread subject, and user name. Each row signifies that a user with the stated username commented on a specific thread in a designated page. This information helps establish a social network of communication, drawing connections between Wikidata users based on their discussions in Talk pages.

## Task A: Network Construction

### Objective:
Construct a Wikidata editor network using the provided data, where:

Nodes represent Wikidata user editors.
Edges signify social connections between editors who've commented on the same thread within the same page.

### Key Points:
- Determine suitable data structures to represent the network.
- Decide on how to retain additional information that cannot be directly encoded as nodes and edges.
- Outline the algorithmic approach to build the network.
- Calculate the cost (in terms of time and input size) of constructing the network.
- Documentation for this task will include snippets of code, outputs, visualizations, and explanatory text.

## Task B: Network Metrics

### Objective:
Analyze the constructed network using various analytical tools, metrics, and algorithms.

### Key Points:
- Identify characteristic properties, relevant metrics, and distributions of the Wikidata editor network.
- Compare this network with a random network.
- Interpret the network's representation of editor networks in collaborative knowledge projects like Wikipedia and Wikidata.
- Evaluate how the analysis changes if two editors are considered connected when they've contributed to any thread on the same page, not necessarily the same thread.
- Documentation for this task will comprise snippets of code, outputs, visualizations, and explanatory text.

## Task C: Epidemic Models

### Objective:
Consider a situation where the Wikimedia Foundation wishes to understand how opinions and knowledge expand among editors.

### Key Points:
- Evaluate the likelihood of a behavior (e.g., trolling) not yet propagating to neighboring editors based on network data.
- Determine a priority list for checking editors based on the chance of them exhibiting a specific behavior.
- Documentation for this task will be twofold: a textual explanation for addressing the questions, followed by snippets of code, outputs, and explanatory text illustrating specific examples.

## Task D: Network Metric-Based Quality

### Objective:
- Reflect on the subjective and social aspects of deciding when and how to establish an edge between two editor nodes and assess the quality of network links using network metrics.

### Key Points:
- Identify potential problems (bias, identity, etc.) that can impact the network's quality.
- Suggest network metrics (and their combinations) for evaluating link quality and resolving identity issues.
- This task will focus on a textual description, emphasizing how ideas from reading club sessions could be applied to the problem described.

#### Request for the written report.
