# AuditBench: A Benchmark for Large Language Models in Financial Statement Auditing

## Overview

Welcome to the repository for *AuditBench: A Benchmark for Large Language Models in Financial Statement Auditing*. This repository contains datasets and resources supporting our research on automated financial statement auditing using large language models (LLMs). The included files offer structured financial data, transaction records, and error-injected financial tables to facilitate research on LLM-based auditing capabilities.

The paper, *AuditBench: A Benchmark for Large Language Models in Financial Statement Auditing*, has been uploaded to this repository. You may refer to the paper to understand the research objectives, methodologies, and key findings.

## Repository Contents

This repository contains the following files and datasets:

### 1. `Raw_table_data`

This file contains textual representations of financial tables extracted from 10,000 financial statements of various companies. The financial tables were originally stored as images and have been translated into structured text format. These tables provide the foundational financial data used in our analysis and experiments.

### 2. `transaction_data`

This file includes transaction data corresponding to the financial tables in `Raw_table_data`. Each financial table has been assigned synthetic transaction data that aligns with its reported financial figures, allowing for validation of financial statement accuracy.

### 3. `Error_insertion`

This directory contains datasets with manually injected errors in financial tables to simulate real-world auditing challenges. The directory consists of two files:

- **`wrong_table_data.json`**: This file contains financial tables where a single error has been manually introduced per table. The dataset also includes corresponding transaction data and metadata indicating the type of error injected.
- **`wrong_table_data_multiple_errors.json`**: This file extends the `wrong_table_data.json` dataset by injecting multiple errors into each financial table. It serves as a more challenging benchmark for evaluating the error detection capabilities of LLMs.

## Citation

If you use this dataset or refer to our research in your work, please cite our paper:

```
@inproceedings{wangauditbench,
  title={AuditBench: A Benchmark for Large Language Models in Financial Statement Auditing},
  author={Wang, Rushi and Liu, Jiateng and Zhao, Weijie and Li, Shenglan and Zhang, Denghui},
  booktitle={2nd AI4Research Workshop: Towards a Knowledge-grounded Scientific Research Lifecycle}
}
```

Feel free to open an issue or contact us for any questions or clarifications.

---

**Contributors:** Rushi Wang, Jiateng Liu, Weijie Zhao, Shenglan Li, Denghui Zhang\
University of Illinois Urbana-Champaign | Stevens Institute of Technology