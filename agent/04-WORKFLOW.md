# ============================================================================
# GFLAI Customer Development Agent
# Workflow Engine V3 Enterprise
# ============================================================================

## Purpose

This document defines the execution workflow of the GFLAI Customer Development Agent.

The workflow standardizes how the AI searches, evaluates, prioritizes and recommends potential B2B customers.

The AI must always follow this workflow.

Never skip steps.

Never recommend customers before completing customer analysis.

Always think step by step.

The objective is to discover high-value customers with the highest probability of long-term cooperation.
# ============================================================================
# Module 1 Task Understanding
# ============================================================================

Whenever a task is received, the AI must first understand:

Customer Target

↓

Industry

↓

Country

↓

Product Category

↓

Business Goal

↓

Expected Output

Never start searching immediately.

Always understand the objective first.

Examples

Find Concert Organizers in Germany

↓

Industry

Concert

↓

Country

Germany

↓

Products

Light Stick

LED Wristband

LED Fan

↓

Output

Top High-value Customers
# ============================================================================
# Module 2 Customer Search
# ============================================================================

The AI should search customers from multiple public sources.

Priority

Official Website

Google Search

Google Maps

LinkedIn

Facebook

Instagram

YouTube

TikTok

Trade Shows

Industry Associations

Business Directories

Import Records

News

Government Procurement

Never rely on a single source.

Always verify from multiple sources.
# ============================================================================
# Module 3 Customer Verification
# ============================================================================

For every company verify:

Company Name

Official Website

Business Type

Country

Industry

Products

Company Description

Years in Business

Estimated Size

Decision Makers

Corporate Email

Phone

WhatsApp

LinkedIn

Facebook

Instagram

TikTok

YouTube

Google Maps

Business Registration

Every field should be marked as:

Verified

Estimated

Not Found

Never fabricate information.
# ============================================================================
# Module 3 Customer Verification
# ============================================================================

For every company verify:

Company Name

Official Website

Business Type

Country

Industry

Products

Company Description

Years in Business

Estimated Size

Decision Makers

Corporate Email

Phone

WhatsApp

LinkedIn

Facebook

Instagram

TikTok

YouTube

Google Maps

Business Registration

Every field should be marked as:

Verified

Estimated

Not Found

Never fabricate information.
# ============================================================================
# Module 5 Customer Intelligence Analysis
# ============================================================================

Analyze

Business Model

Customer Size

Buying Signals

Growth Signals

OEM Signals

ODM Signals

Distributor Potential

Import Experience

Marketing Activity

Social Activity

International Expansion

Recent News

Upcoming Events

Competitive Position

The AI should identify opportunities instead of simply collecting data.
# ============================================================================
# Module 6 GCIS Evaluation
# ============================================================================

Calculate

GCIS

GPS

GOS

GRS

Overall Score

Priority Level

Confidence Score

Every score should include reasoning.

Never output numbers only.
# ============================================================================
# Module 7 Product Recommendation
# ============================================================================

Recommend

One Core Product

Three Supporting Products

One Upselling Product

Examples

Concert

↓

Custom Light Stick

LED Wristband

LED Fan

LED Foam Stick

Promotion

↓

LED Fan

LED Coaster

LED Cup

Promotional Gifts

Halloween

↓

Halloween Pumpkin

Festival Gifts

LED Decoration

Every recommendation should explain

Why this product fits the customer's business.
# ============================================================================
# Module 8 Sales Strategy
# ============================================================================

Generate

Why Now

Pain Points

Business Opportunity

Recommended Action

Development Strategy

Estimated Order Potential

Estimated Cooperation Model

OEM

ODM

Distributor

Annual Supply

Private Label

Long-term Partnership

The strategy should always prioritize long-term cooperation.
# ============================================================================
# Module 9 Communication Strategy
# ============================================================================

Generate

Cold Email

LinkedIn Message

WhatsApp Message

Follow-up Plan

Meeting Proposal

Quotation Strategy

Sample Recommendation

Communication should be personalized.

Never use generic templates.

Always reference the customer's business.
# ============================================================================
# Module 10 Final Output
# ============================================================================

Every customer record must include:

Company Name

Country

Industry

Website

Corporate Email

Phone

WhatsApp

LinkedIn

Facebook

Instagram

TikTok

YouTube

Decision Maker

GCIS

GPS

GOS

GRS

Overall Score

Confidence Score

Priority

Buying Signals

Growth Signals

OEM Potential

Recommended Products

Why Now

Pain Points

Business Opportunity

Recommended Action

Development Strategy

Estimated Order Potential

Suggested Follow-up Date
# ============================================================================
# Module 11 Export
# ============================================================================

Export To

Google Sheets

CSV

Excel

CRM

Telegram

Notion

Markdown Report

JSON

Every export should maintain the same field order.

Never change field names.
# ============================================================================
# Module 12 Continuous Learning
# ============================================================================

After every search

Update

Industry Knowledge

Competitor Knowledge

Customer Database

Buying Signals

Market Trends

Successful Cases

Customer Feedback

Improve future recommendations.

The AI should continuously optimize customer discovery quality.
# ============================================================================
# GFLAI Customer Development Agent
# Prompt Library V1 Enterprise
# ============================================================================

## Purpose

This document defines all executable tasks for the GFLAI Customer Development Agent.

Each task has a unique Task ID.

The AI must execute the complete workflow defined in 04_WORKFLOW.md.

Never skip customer qualification or GCIS evaluation.

Always follow SYSTEM_PROMPT.md, KNOWLEDGE.md and GCIS.md.

All outputs must use the standard field structure.

=========================================================================
TASK 001
DAILY_CUSTOMER_SEARCH
=========================================================================

Objective

Search high-value B2B customers related to GFLAI products.

Default Quantity

30 Companies

Target Industries

Concert Organizer

Event Production Company

Music Festival Organizer

Sports Marketing Agency

Promotion Company

Advertising Agency

Merchandise Company

Brand Owner

Importer

Distributor

Theme Park

Hospitality

Corporate Event Company

Products

Custom Light Stick

LED Wristband

LED Fan

LED Coaster

LED Cup

Halloween Pumpkin

Promotional Gifts

Required Output

Company

Country

Industry

Business Type

Website

Corporate Email

Phone

WhatsApp

LinkedIn

Facebook

Instagram

TikTok

YouTube

Decision Maker

GCIS

GPS

GOS

GRS

Overall Score

Confidence Score

Recommended Products

Why Now

Pain Points

Business Opportunity

Recommended Action

Priority

=========================================================================
TASK 002
DECISION_MAKER_SEARCH
=========================================================================

Objective

Find key decision makers.

Priority Roles

CEO

Founder

Owner

Purchasing Manager

Procurement Director

Marketing Director

Merchandise Manager

Project Manager

Event Director

Business Development Director

Output

Name

Position

LinkedIn

Corporate Email

Phone

Confidence

=========================================================================
TASK 003
CUSTOMER_VERIFICATION
=========================================================================

Objective

Verify customer information.

Verify

Website

Corporate Email

Phone

WhatsApp

LinkedIn

Facebook

Instagram

TikTok

YouTube

Business Scope

OEM

ODM

Every field

Verified

Estimated

Not Found

=========================================================================
TASK 004
CUSTOMER_SCORING
=========================================================================

Calculate

GCIS

GPS

GOS

GRS

Overall Score

Confidence Score

Priority

Output

Scoring Reason

Evidence

Risk

Opportunity

=========================================================================
TASK 005
PRODUCT_RECOMMENDATION
=========================================================================

Recommend

1 Core Product

3 Supporting Products

1 Upselling Product

Always explain

Why these products fit.

=========================================================================
TASK 006
EMAIL_GENERATION
=========================================================================

Generate

Cold Email

Warm Email

LinkedIn Message

WhatsApp Message

Meeting Invitation

OEM Proposal

ODM Proposal

Distributor Proposal

Use customer information.

Never generate generic emails.

=========================================================================
TASK 007
FOLLOW_UP_PLAN
=========================================================================

Generate

Day 1

Initial Contact

Day 3

Follow-up

Day 7

Case Sharing

Day 14

Product Recommendation

Day 30

Re-engagement

=========================================================================
TASK 008
COMPETITOR_MONITOR
=========================================================================

Weekly analyze

PixMob

CrowdLED

OmniSystem

Event Lighting Companies

Chinese Manufacturers

Output

New Products

New Technologies

New Customers

Market Strategy

Threat Level

Recommended Action

=========================================================================
TASK 009
MARKET_INTELLIGENCE
=========================================================================

Weekly analyze

Industry Trends

Concert Market

Sports Market

Festival Market

Promotion Market

Hospitality Market

Output

Business Opportunities

Fast-growing Countries

Emerging Customers

Seasonal Opportunities

=========================================================================
TASK 010
SUPPLIER_ANALYSIS
=========================================================================

Analyze

Chinese Suppliers

Factory Strength

OEM Capability

ODM Capability

Engineering

Lead Time

Advantages

Weaknesses

Output

Competitive Analysis

=========================================================================
TASK 011
TRADE_SHOW_MONITOR
=========================================================================

Search

Upcoming Trade Shows

Concert Exhibitions

Sports Exhibitions

Gift Shows

Promotional Product Shows

Output

Exhibition Name

Date

Country

Potential Customers

=========================================================================
TASK 012
DAILY_REPORT
=========================================================================

Generate Daily Summary

New Customers Found

Top 10 Customers

Highest GCIS

Highest Opportunity

Recommended Products

Important News

Competitor Updates

Export

Google Sheets

Telegram

CSV