# COS30045 Data Visualisation — Demonstration 1

## Appliance Energy Consumption Website

This repository contains the work developed for COS30045 Data Visualisation Demonstration 1, covering T01, T02 and T03.

The website explores television choices and energy consumption in the Australian market using data processed and analysed in KNIME.

**Live website:** https://cos-30045-t01a-five.vercel.app

## Technologies and Tools

- HTML
- CSS
- JavaScript
- KNIME
- Git and GitHub
- Vercel
- Canva

## Data Story

### Audience

The data story is designed for Australian consumers who are considering purchasing a television and want to understand the available choices and their energy consumption.

### Audience Interests

The visualisation story focuses on questions that are useful when comparing television options, including:

- which screen technologies are most commonly available;
- which screen sizes provide the most model options;
- which brands offer the greatest number of models;
- how power consumption differs between screen technologies;
- how screen size relates to power consumption; and
- whether screen size has a clear relationship with star rating.

The story is presented on `televisions.html` using a sequence of charts, supporting explanations and key takeaways so that the findings can be understood without requiring technical knowledge of KNIME or the underlying data-processing workflow.

## About the Data

### Data Source

The television dataset used in this project was provided as part of the COS30045 tutorial exercises. It contains records describing televisions available in the Australian market.

The analysis uses fields including:

- `Submit_ID`
- `Brand_Reg`
- `Model_No`
- `Screen_Tech`
- `screensize_inches`
- `avg_mode_power`
- `Star Rating Index`

### Data Processing

The dataset was processed in KNIME before the visualisations were produced. The workflow includes selecting relevant columns, sorting and filtering records, removing duplicate records, transforming values where required, and preparing different branches of the workflow for the questions explored in T02 and T03.

Different questions require different forms of processing. For example:

- counts are used to compare the availability of screen technologies, screen sizes and television models;
- median power consumption is used to compare screen technologies;
- average power consumption is used for brand-level comparison; and
- individual television records are retained for scatter plots examining relationships between numerical variables.

### Privacy

The fields used in this project describe television products and their technical or energy-related characteristics. The visualisations do not use personal information about individual consumers.

### Accuracy and Limitations

The findings represent the records contained in the provided dataset and should be interpreted as a description of that dataset rather than as a permanent description of the entire Australian television market.

The analysis also depends on how values are recorded in the source data. For example, brand labels such as `SAMSUNG` and `SAMSUNG ELECTRONICS` appear as separate categories, which can affect brand-level comparisons.

Summary measures such as counts, averages and medians simplify the data and do not capture every difference between individual television models. The scatter plots show patterns and associations, but they do not establish that one variable directly causes another.

### Ethics

The visualisations are intended to communicate the data accurately and without overstating the findings. Chart titles, axis labels and explanatory text are used to make the measures clear to the reader.

Relationships shown in scatter plots are described as associations rather than causal effects. Product comparisons are also limited to the variables contained in the dataset and are not presented as overall judgements about brand or product quality.

## AI Declaration

To be completed before submission.
