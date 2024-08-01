# -FastICABlindSeparation-on-Sleep-EDF-Database
Implementation of a blind source separation method using the FastICA algorithm from scratch, applied to polysomnographic data from the Sleep-EDF database.

This project demonstrates the implementation of a blind source separation method using the FastICA algorithm, which is built from scratch. The dataset used is from the [PhysioNet Sleep-EDF database](https://physionet.org/content/sleep-edf/1.0.0/), which contains polysomnographic recordings.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Acknowledgements](#acknowledgements)

## Introduction

The goal of this project is to separate mixed signals into their original source components using the FastICA algorithm. FastICA (Fast Independent Component Analysis) is a widely used algorithm for blind source separation. The implementation is done from scratch without using any built-in ICA libraries to understand the intricacies of the algorithm.

## Dataset

The dataset used in this project is from the Sleep-EDF Database, which includes various polysomnographic signals such as EEG, EOG, EMG, and respiratory signals. The specific file used in this project is `sc4002e0.rec`.

## Installation

To run this project, you need to have Python installed along with the following libraries:

- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy

You can install the required libraries using the following command:

```bash
pip install numpy matplotlib seaborn scikit-learn scipy