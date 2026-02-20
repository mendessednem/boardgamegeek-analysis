# BoardGameGeek Data Analysis 🎲

This project explores board game data collected from BoardGameGeek (BGG), applying data analysis, visualization, predictive modeling, and recommendation techniques using R.

The goal is to extract insights from board game characteristics and understand what drives high ratings and popularity.

---

## 📊 Project Overview

The analysis covers:

- Exploratory Data Analysis (EDA)
- Data preprocessing and cleaning
- Rating prediction modeling
- Top game classification
- Content-based recommendation system

---

## 📁 Dataset

The dataset contains board game information including:

- Game name
- Year of publication
- Average rating
- Number of users
- Playing time
- Minimum and maximum players
- Complexity (weight)
- Categories and mechanics

Data source: BoardGameGeek (exported dataset)

---

## 🔎 Exploratory Analysis

The project investigates:

- Distribution of ratings
- Relationship between complexity and rating
- Influence of player count on popularity
- Temporal trends in board game publishing
- Correlation analysis between numerical variables

Visualizations include histograms, scatter plots, and correlation matrices.

---

## 🤖 Predictive Modeling

### 🎯 Rating Prediction

A regression model is built to predict a game’s average rating based on:

- Complexity (weight)
- Player count
- Playing time
- Publication year
- Popularity indicators

Model performance is evaluated using appropriate regression metrics.

---

### 🏆 Top Game Classification

A classification approach is used to determine whether a game belongs to the top-rated group.

This allows identifying key characteristics of highly successful games.

---

## 🎲 Recommendation System

A simple content-based recommender suggests similar games based on:

- Shared mechanics
- Shared categories
- Similar numerical attributes

This demonstrates how structured board game metadata can support personalized recommendations.

---

## 🛠 Technologies Used

- R
- dplyr
- ggplot2
- caret (or other modeling packages)
- Basic machine learning models
- Correlation and statistical analysis

---
