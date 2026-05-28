# 📅 Working with Date and Time in Pandas

A comprehensive guide to handling date and time data using Python's Pandas library. This repository contains practical examples and real-world datasets to master datetime operations.  

## 📋 Table of Contents

- [Overview](#overview)
- [Files in this Repository](#files-in-this-repository)
- [Key Concepts Covered](#key-concepts-covered)
- [Getting Started](#getting-started)
- [Code Examples](#code-examples)
- [Common DateTime Functions](#common-datetime-functions)
- [Format Codes](#format-codes)
- [Sample Output](#sample-output)
- [Requirements](#requirements)
- [Author](#author)

---

## 📖 Overview

Working with dates and times is a common task in data analysis. This repository demonstrates how to:

- Convert Unix timestamps to readable datetime
- Calculate differences between dates
- Extract day names, months, quarters, and more
- Handle various date formats
- Perform datetime arithmetic

---

## 📁 Files in this Repository

| File | Description |
|------|-------------|
| `DateTime Execution.ipynb` | Main Jupyter notebook with all datetime operations |
| `order_delivery.csv` | Order and delivery dates for difference calculation |
| `expense.csv` | Raw expense tracking data |
| `expense_datetime.csv` | Processed expense data with datetime columns |
| `fast_delivery.csv` | Filtered data for fast deliveries |
| `timestamp.csv` | Unix timestamp conversion examples |
| `README.md` | This documentation |

---

## 🎯 Key Concepts Covered

| Concept | Description |
|---------|-------------|
| `pd.to_datetime()` | Convert strings/numbers to datetime |
| `.dt.day_name()` | Extract day of week (Monday, Tuesday, etc.) |
| `.dt.quarter` | Extract quarter (1, 2, 3, 4) |
| `.dt.year / .dt.month / .dt.day` | Extract date components |
| Date Subtraction | Calculate time differences between columns |
| Unix Timestamp | Convert seconds since epoch to datetime |
| Custom Date Formats | Parse dates with specific formats |

---
