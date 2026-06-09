# Student Attendance Automation System

## Overview

This project is an automated attendance monitoring system built using n8n, Google Sheets, and Gmail.

The workflow reads student attendance data from Google Sheets, categorizes students based on attendance percentage, and automatically sends personalized email notifications.

## Features

* Automated attendance monitoring
* Google Sheets integration
* Gmail integration
* Personalized email alerts
* Attendance categorization:

  * Good (>= 75%)
  * Warning (60% - 74%)
  * Critical (< 60%)

## Workflow

Schedule Trigger → Google Sheets → IF Conditions → Gmail

## Technologies Used

* n8n
* Google Sheets
* Gmail

## Project Outcome

The system automatically sends attendance notifications to students based on their attendance percentage without manual intervention.
