# Running Performance Statistical Modelling

## Overview

This project is an undergraduate statistical modelling and experimental design report analysing how running performance changes across different times of day and running surfaces.

The study uses a randomized complete block design to investigate whether running time is affected by experimental conditions such as time period, environment, and individual runner differences. The project applies ANOVA, Tukey pairwise comparisons, and model adequacy checking to evaluate the significance of these factors.

Although the original idea considered running shoe performance, the final experimental design focuses on running time across different surfaces and time periods while controlling for runner-to-runner variation through blocking.

## Project Objective

The objective of this project is to determine whether running performance differs depending on:

* Time of day
* Running surface
* Individual runner differences

The response variable is the time, measured in seconds, required to complete a 100-meter run.

## Experimental Design

The experiment was designed as a factorial experiment with blocking.

### Factors

The main experimental factors are:

| Factor          | Levels                       |
| --------------- | ---------------------------- |
| Time of day     | Morning, Afternoon, Evening  |
| Running surface | Track, Stone/Asphalt, Grass  |
| Runner          | Three runners used as blocks |

### Response Variable

The response variable is:

```text
100-meter running time, measured in seconds
```

### Blocking

Runners were used as blocks to control for individual differences such as:

* Running ability
* Speed
* Consistency
* Physical capability
* Shoe size and personal athletic background

Blocking helps reduce unwanted variability and makes the comparison between time periods and environments more reliable.

### Design Structure

The project uses a:

```text
3 × 3 factorial experiment in a randomized complete block design
```

This gives:

```text
3 time periods × 3 environments × 3 runners = 27 experimental runs
```

## Statistical Model

The statistical model used in the project is:

[
y_{ijk} = \mu + \tau_i + \beta_j + (\tau\beta)*{ij} + \delta_k + \epsilon*{ijk}
]

where:

* (y_{ijk}) is the observed running time
* (\mu) is the overall mean
* (\tau_i) is the effect of time of day
* (\beta_j) is the effect of running environment
* ((\tau\beta)_{ij}) is the interaction between time and environment
* (\delta_k) is the block effect for runner
* (\epsilon_{ijk}) is the random error term

## Data Collection

The experiment was conducted using three runners and three running surfaces.

The running surfaces included:

* Stadium track
* Grass field
* Stone/asphalt surface

The test was performed across three time periods:

* Morning
* Afternoon
* Evening

Each runner completed 100-meter runs under each treatment combination. The runners warmed up before running and rested between trials to improve consistency and reduce injury risk.

## Analysis Methods

The project applies several statistical methods:

### 1. Exploratory Analysis

Boxplots were used to compare running time distributions across time periods and running environments.

The exploratory analysis suggested that evening running times differed noticeably from morning and afternoon running times.

### 2. ANOVA

ANOVA was used to test whether the experimental factors had statistically significant effects on running time.

The analysis examined:

* Time of day
* Running environment
* Runner block effect
* Time-environment interaction

### 3. Model Reduction

After identifying non-significant factors, the model was simplified by removing unnecessary terms.

This improved interpretability while keeping the important explanatory variables.

### 4. Tukey Pairwise Comparisons

Tukey pairwise comparisons were used to identify which factor levels differed significantly from one another.

The project found significant differences between:

* Evening and Afternoon
* Morning and Evening
* Track and Grass

### 5. Model Adequacy Checking

Model assumptions were checked using:

* Normal probability plot
* Shapiro-Wilk normality test
* Residuals versus fitted values plot

The normality assumption was considered reasonable because the Shapiro-Wilk p-value was greater than 0.05. The residuals versus fitted values plot showed random scatter, supporting the constant variance assumption.

## Key Findings

* Time of day had a significant effect on running performance.
* Running surface also had a significant effect on running time.
* Runner differences were significant, supporting the use of blocking.
* The interaction between time of day and environment was not significant.
* Evening running times were significantly different from morning and afternoon times.
* Track and grass surfaces showed a significant difference.
* The best running performance was generally observed in the morning or afternoon rather than evening.

## Project Files

| File                                                    | Description                                                     |
| ------------------------------------------------------- | --------------------------------------------------------------- |
| `Running_Performance_Statistical_Modelling_Report.pdf` | Original undergraduate statistical modelling report             |


## Tools and Techniques

* Experimental design
* Randomized complete block design
* Factorial experiment
* ANOVA
* Tukey pairwise comparison
* Boxplot analysis
* Shapiro-Wilk normality test
* Residual diagnostics
* Model adequacy checking
* Statistical interpretation

## Skills Demonstrated

* Statistical modelling
* Experimental design
* Hypothesis testing
* ANOVA interpretation
* Blocking and nuisance factor control
* Pairwise comparison analysis
* Model assumption checking
* Data collection planning
* Research design
* Statistical reporting
* Quantitative reasoning

## Limitations

This project has several limitations:

* Only three runners were included in the experiment.
* The sample size was limited to 27 runs.
* Runners were not professional athletes.
* Human reaction time may have affected timing accuracy.
* Weather, wind resistance, body temperature, and fatigue were not fully controlled.
* The original shoe-brand comparison was not fully implemented because switching shoes repeatedly was impractical.
* Runners used their own shoes and athletic clothing, which may have introduced variability.
* The experiment was conducted within practical time and resource constraints.

## Future Improvements

This project could be improved by:

* Increasing the number of runners
* Using electronic timing equipment
* Testing across multiple days
* Controlling shoe type and athletic clothing
* Measuring outdoor temperature and weather conditions
* Adding more surface types
* Randomizing run order more strictly
* Including repeated trials for each treatment combination
* Separating shoe-brand effects from time-of-day and surface effects
* Using a larger and more diverse participant group

## Conclusion

This project demonstrates how experimental design and statistical modelling can be used to analyse running performance.

Using a randomized complete block design, the study controlled for runner differences while testing the effects of time of day and running surface. The analysis found that time of day, running surface, and runner block effects were significant, while the interaction between time and environment was not significant.

The project shows practical experience with ANOVA, Tukey comparisons, residual diagnostics, and statistical interpretation, making it a strong undergraduate statistics portfolio piece.
