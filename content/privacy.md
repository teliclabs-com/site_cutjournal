---
title: "Privacy Policy"
description: "CutJournal AI Privacy Policy - How we handle your data"
layout: "single"
---

# Privacy Policy

**Last updated: March 15, 2026**

CutJournal AI ("we", "our", or "us") is developed by Telic Labs (Christopher Townsend). This Privacy Policy explains how information is handled when you use the CutJournal AI iOS application ("the App"). This policy applies to all users of the App and is intended to satisfy the requirements of the Apple App Store.

## AI Body Fat Estimate Feature

### Overview

CutJournal AI includes an optional AI-powered body fat estimation feature. When you choose to use this feature, certain data is transmitted securely for real-time analysis. This section explains exactly what data is involved, how it is processed, and what protections are in place.

### Data Collected

| Data Type | What Is Sent | Purpose | Retention |
|-----------|-------------|---------|-----------|
| Progress Photos | Front and side photos you capture | Visual analysis for body fat estimation | Immediately discarded after processing |
| Body Measurements | Waist, neck, hip, and other measurements you enter | Used alongside photos to improve estimate accuracy | Immediately discarded after processing |
| Profile Information | Height, weight, age, and sex | Provides context for accurate body composition analysis | Immediately discarded after processing |
| Device Identifier | Anonymous `identifierForVendor` | Manages API access and credit usage | Retained on server for access management only |

### How Your Data Is Processed

- All data is transmitted over **TLS-encrypted connections**
- Processing occurs entirely within our **AWS infrastructure**
- The AI model (Anthropic's Claude) is accessed via **AWS Bedrock** — your data remains within AWS and is **not sent to Anthropic directly**
- No third party outside of AWS has access to your data during processing

### Data Retention

- Photos, measurements, and profile data are processed in **real time** and **immediately discarded** — they are never written to disk, cached, or stored on any server
- The only data retained on our servers is your **anonymous device identifier** and **credit balance**, used solely for API access management

### Service Providers

**Amazon Web Services (AWS)** is the sole third-party service provider involved in processing AI estimates. AWS acts as a data processor under our direction. The Anthropic Claude AI model is accessed through AWS Bedrock, meaning your data stays within the AWS environment and is not transmitted to Anthropic separately.

### Third-Party AI Disclosure (Apple Guideline 5.1.2(i))

This feature uses a customized **Anthropic Claude** model, a third-party AI model, to analyze your photos and measurements for body fat estimation. The model is accessed through **AWS Bedrock**, and your data is processed within AWS infrastructure. Anthropic does not directly receive, store, or have access to your data. No data is used to train AI models.

### Your Consent and Control

- The AI body fat estimation feature is **entirely optional** — the App functions fully without it
- You must provide **explicit consent** before any data is sent for AI analysis
- You can choose not to use the feature at any time with no impact on other App functionality

## Analytics and Tracking

We do **not** use any analytics frameworks, advertising SDKs, or tracking technologies. There are no cookies, no session tracking, and no behavioral profiling.

## Third-Party Services

When you request an AI estimate, your photos are processed within our AWS infrastructure. The AI model (Anthropic's Claude) is accessed through AWS Bedrock — Anthropic does not directly receive your data. Your photos are used solely to generate your estimate and are not stored or used for any other purpose. We do not sell, trade, or share any information with third parties for marketing or advertising purposes.

## Data Retention

- **On-device data:** Retained until you delete it within the App or uninstall the App.
- **Device identifier, credits purchased, and credits used:** Retained on our server only as long as needed for API access management. No other data is retained.

## Your Rights and Choices

You have full control over your data:

- **Delete all App data** at any time by uninstalling the App from your device
- **Revoke Apple Health permissions** through iOS Settings at any time
- **Contact us** to request deletion of your device identifier and credit data from our server

## Apple Health Integration

With your explicit permission, CutJournal AI can read and write data to Apple Health (such as weight and body fat percentage). This integration is managed entirely by iOS. Health data accessed through this integration remains on your device and is governed by Apple's privacy policies. **We do not have access to your Apple Health data.**

You can grant or revoke Apple Health permissions at any time through **Settings > Health > Data Access & Devices** on your device.


## Children's Privacy

CutJournal AI is not directed at children under the age of 13. We do not knowingly collect any information from children under 13. Since we do not collect personal data, there is no risk of children's data being stored.

## International Users

The anonymous device identifier and credit data may be processed on servers located in the United States. Since this data cannot be linked to any individual, no personal data is transferred internationally.

## Changes to This Policy

We may update this Privacy Policy from time to time. Any changes will be reflected on this page with an updated "Last updated" date. Continued use of the App after changes constitutes acceptance of the updated policy.

## Contact Us

If you have questions or concerns about this Privacy Policy, please contact us at:

**Email:** {{< email user="hello" domain="teliclabs.com" >}}

**Developer:** Telic Labs / Christopher Townsend
