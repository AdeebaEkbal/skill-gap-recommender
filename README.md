# Skill-Gap and Career Recommender for AMU Students

A system that recommends career roles based on a student's current skills and shows which skills are missing for each role.

## Problem
Many students do not know which skills lead to which careers, or which skills they lack for a target role.

## Features
- Recommends top matching career roles
- Shows matched and missing skills for each role
- Suggests the order in which to learn missing skills

## Approach
1. Clean and standardise skill data (Pandas, NumPy)
2. Convert skills to TF-IDF vectors (Scikit-learn)
3. Rank roles by cosine similarity
4. Compute skill gap: required skills minus student skills
5. Show results in a Streamlit app

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Streamlit, Google Colab

## Status
In progress

## Author
Adeeba Ekbal, B.Sc. (Hons) Computer Application, AMU
