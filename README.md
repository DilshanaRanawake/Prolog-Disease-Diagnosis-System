# Disease Diagnosis System

This project is a simple expert system built in Prolog to diagnose common diseases based on a patient's symptoms. The system uses a series of questions to narrow down potential diagnoses and provides a likely result based on symptom verification.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Usage](#usage)
- [Supported Diagnoses](#supported-diagnoses)
- [Screenshots](#screenshots)

## Overview

This Prolog expert system simulates a basic medical diagnosis tool. Given symptoms entered by a user, it attempts to match these symptoms against a set of predefined disease hypotheses. If symptoms do not match any hypothesis, the system defaults to an "unknown" diagnosis.

## Features

- Diagnoses common diseases based on symptoms
- Interactive question-and-answer format
- Easy to extend with additional diseases and symptoms

## Usage
To use the system:

-Load the Prolog file in your Prolog environment.
-Run the main predicate:
``` bash
?- go.
```
-Answer the questions prompted by the system with yes or no to receive a diagnosis.

## Supported Diagnoses
The system currently supports diagnosing the following conditions:

- Cold
- Flu
- Ebola
- Measles
- Arthritis

## Screenshots

Below are examples of the system's diagnosis outputs:

### Diagnosis for Cold
![Cold Diagnosis](https://github.com/DilshanaRanawake/Prolog-Disease-Diagnosis-System/blob/main/Screenshots/1.png)

### Unknown Diagnosis
![Unknown Diagnosis](https://github.com/DilshanaRanawake/Prolog-Disease-Diagnosis-System/blob/main/Screenshots/2.png)

### Diagnosis for Measles
![Measles Diagnosis](https://github.com/DilshanaRanawake/Prolog-Disease-Diagnosis-System/blob/main/Screenshots/3.png)

-This project is inspired by a YouTube tutorial on building an expert system in Prolog.
