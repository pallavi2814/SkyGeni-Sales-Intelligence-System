# SkyGeni-Sales-Intelligence-System

# Overview

This project simulates a real-world sales intelligence scenario where a CRO reports declining win rates despite strong pipeline volume.
The objective is NOT to build complex ML models but to design a decision intelligence system that helps leadership understand:

- Why win rates are declining
- What factors drive success or failure
- What actions sales leadership should take
# Business Problem Framing
## Core Problem
Revenue predictability is declining because win rate performance is inconsistent across segments.

Leadership lacks:
- Clear diagnostic insights
- Driver-level analysis
- Actionable recommendations

## Key Questions for CRO
- Which regions or products have declining performance?
- Which lead sources generate low-quality pipeline?
- Are certain reps or industries underperforming?
- Is long sales cycle hurting conversion?

## Metrics That Matter
- Win Rate
- Sales Cycle Duration
- Deal Velocity
- Rep Performance Consistency

## Assumptions
- Data is historically accurate
- Sales stages are standardized
- Outcome labels are reliable
- Closed deals reflect final truth
# Data Exploration & Insights
## Insight Examples
1. Regional performance differences
2. Product-driven win variation
3. Lead source quality gaps

## Custom Metrics
1. Sales Velocity Score
2. Rep Win Consistency Index

Business Impact:
- Optimize sales coverage
- Improve pipeline quality
- Focus enablement resources

## Decision Engine

Selected Approach: **Win Rate Driver Analysis**

Why:
- High interpretability
- Strong leadership relevance
- Actionable insights
- Suitable for executive dashboards

Outputs:
- Win rate by industry
- Win rate by product
- Win rate by region
- Automated recommendations

# Mini System Design

## Architecture
Data Source → ETL → Feature Engineering → Decision Engine → Insights Dashboard → Alerts

## Data Flow
CRM → Data Pipeline → Analytics Engine → Executive Reporting

## Example Alerts
- "Win rate dropped 15% in APAC"
- "Lead source X producing low conversions"
- "Product Y losing deals in finance industry"

## Execution Frequency
Daily automated analysis

## Failure Risks
- Missing CRM fields
- Incorrect stage updates
- Small sample bias

# Reflection

Weakest Assumptions:
- Clean CRM data
- Consistent sales behavior

Production Risks:
- Data drift
- Incomplete deal lifecycle

Next 30-Day Improvements:
- Predictive deal scoring
- Rep coaching analytics
- Real-time pipeline monitoring

Lowest Confidence Area:
- Lead source attribution accuracy
