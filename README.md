# Tunnel Trials Report

**Author:** Malachy McGovern  
**Date:** 13/06/2022

## Overview

This trial evaluates the efficiency of both traditional handling and tunnel handling methods in completing husbandry tasks. Efficiency is measured by the rate of completion of typical tasks such as checking animals and cleaning cages, including mating-specific actions like sexing and weaning. Conducted over four weeks, the trial randomly selected 20 cages from 4 racks across two rooms, resulting in 264 observations of cage checks.

### Timing

Timing procedures involved starting the timer when the cage was ready for inspection and stopping it once all relevant tasks were completed. Additional tasks, such as refilling diet containers or recording data, were encouraged to be performed outside the timing period unless absolutely necessary.

## Variables

- **Total time**: Dependent variable representing the time taken to check the cage (in seconds).
- **Cage Function**: Categorical variable indicating whether the cage is used for mating or stock.
- **Number of animals**: Numerical variable indicating the total number of animals in the cage for the weekly check.
- **Binary variables**: 
  - *Cleaned*: Indicates whether the cage base was changed.
  - *Sexed*: Indicates the process of sexing the litter.
  - *Weaned*: Indicates the process of weaning the litter.

## Aims of Analysis

The primary aim is to compare the time taken for checking and cleaning between tunnel and traditional cages using a T-test. Additionally, a regression model will be constructed to predict the time required to check a cage based on variables such as the number of animals and the necessity for cleaning, sexing, or weaning. 

### Binomial Distributions: Cleaning Probabilities

**Stock Cages** - The probability of stock cages being cleaned increases linearly with the number of animals. Interestingly, little difference exists in the cleaning probability between cages with two, three, or four animals.

**Mating Cages** - Mating cages with more than seven animals are cleaned every week. Moreover, smaller litters have similar cleaning rates to adult stock cages.

## Tunnel vs. Traditional Comparison

When comparing tunnel and traditional handling, significant differences are observed in both matings and stock categories. Matings collectively take more time than stock cages for both handling methods. Statistical tests confirm these differences.

### Physical Animal Checks

**Stock Cages** - No significant difference is found in checking between tunnel and traditional cages for stock cages.

**Mating Cages** - Similarly, no significant difference is observed in checking between tunnel and traditional cages for mating cages.

### Cleaning Times

**Stock Cages** - Tunnel cages take significantly more time to clean than traditional cages, indicating a difference in maintenance efficiency.

**Mating Cages** - After excluding outliers, a significant difference is found between the cleaning times of tunnel and traditional cages for mating cages, with tunnel cages taking substantially longer to clean.

## Modelling Checking & Cleaning Times

Regression models are constructed to predict cage checking and cleaning times based on various variables such as the number of animals and cleaning necessity.

Thank you for reading this report. For further details or inquiries, please contact the author.
