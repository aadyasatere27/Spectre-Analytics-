Spectre Analytics

Financial Energy Monitor
Operational Intelligence for Energy Efficiency

Spectre Analytics is a real-time energy monitoring platform built to bridge the gap between operations and finance. Instead of stopping at raw power consumption metrics, the system detects hidden inefficiencies, explains why they occur, and translates them directly into financial loss.

This project was built during our first hackathon as a working prototype demonstrating how energy data can be turned into actionable operational and financial insight.

Problem Statement

Most energy dashboards answer how much power is being used, but fail to answer:

Is this usage expected?

What part of it is waste?

Why is the waste happening?

How much money is being lost because of it?

As a result, inefficiencies remain invisible, especially when production continues normally and no alarms are triggered.

Spectre Analytics was built to surface these silent losses and present them in a way that both engineers and decision-makers can act on.

Core Concept

Spectre treats energy as a financial signal, not just a utility metric.

It works by:

Predicting what energy usage should look like

Comparing it with real-time consumption

Identifying deviations (anomalies)

Classifying the root cause

Converting excess usage into monetary loss

Key Features
1. Real-Time Anomaly Detection

Continuously compares expected load vs actual load

Detects abnormal behavior such as idle load, phantom drain, short cycling, and electrical faults

Works even when production is running normally

2. Financial Translation Layer

Converts wasted energy directly into:

Cash burn rate (per hour)

Daily loss

Annualized potential savings

Removes ambiguity around energy units by framing inefficiency in currency

3. Root Cause Classification

Each anomaly is classified into meaningful categories such as:

Phantom Drain

Idle Load

Thermal Overload

Harmonic Distortion

Steam Trap Leak

Surge Events

Sensor Drift Errors

This allows teams to prioritize fixes based on impact, not guesswork.

Platform Overview
Overview Dashboard

Designed for facility managers and operators.

Total Waste (kW): Excess energy beyond predicted baseline

System Efficiency (%): Live operational health score

Active Anomalies: Unresolved issues requiring attention

Carbon Footprint (kg/h): Real-time Scope 2 emissions

Includes:

Hourly telemetry graph showing baseline vs actual load

Grid capacity gauge to avoid peak demand charges

Savings Dashboard

Designed for finance teams and leadership.

Cash burn rate (per hour)

Energy cost lost in the last 24 hours

Annualized potential savings

Spend ROI and efficiency rating

Visualizes:

Cost velocity over time

Waste categorized by root cause

High-impact assets ranked by financial loss

Incidents Log

Acts as a system “black box” for operational intelligence.

Logs every detected anomaly with:

Timestamp

Asset ID

Classification

Technical explanation

Energy waste (kW)

Separates incidents into:

Critical issues (safety and equipment risk)

Invisible waste (silent financial loss)

Each incident includes suggested remediation steps.

Technical Overview

Frontend:

HTML

Tailwind CSS

Chart.js

Lucide Icons

Architecture:

Real-time simulated telemetry engine

Predictive baseline modeling

Event-driven anomaly generation

Financial impact calculation layer

Design Philosophy:

Dark, high-contrast UI for control-room readability

Minimal cognitive load

Financial clarity over raw metrics
