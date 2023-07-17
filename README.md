# Telco Customer Churn Prediction
By: Revalde Raditya Candra
_____

## Context

This repository revolves around a telecommunications company (telco) that provides high-speed internet service. The significant concern for the company is understanding why customers choose not to continue with the service they currently have. This phenomenon, also known as churn, can significantly impact the company's revenue and operational strategies.

## Churn Definition

- **No/0**: The customer continues with the current internet company.
- **Yes/1**: The customer does not continue with the current internet company.

## Problem Statement

The telecommunications sector is characterized by intense competition and market saturation. High churn rates in a company could suggest issues related to service quality, pricing, or customer service. Furthermore, many telco services depend on long-term contracts or service agreements. Consequently, when a customer decides not to renew their agreement or terminates it prematurely, it results in financial losses and logistical complications for the company.

## Goals

The primary goal of this project is to understand the characteristics of customers who are potentially at risk of churning. We aim to identify factors contributing to customer churn to implement changes effectively and retain our customers.

## Analytic Approach

The analytics approach involves the development, assessment, and deployment of a machine learning model. The purpose of this model is to predict whether a customer will churn or not based on their historical data.

## Metrics Evaluation

The key evaluation metrics in this project are False Positive Rate and False Negative Rate.

- **False Positive**: This occurs when the model wrongly predicts that a customer will churn when they actually do not. This scenario might result in unnecessary resources being used to retain a customer who was not actually at risk of leaving.

- **False Negative**: This happens when the model incorrectly predicts that a customer will not churn, when in fact they do. This is a more significant issue as the company could lose a customer without having an opportunity to implement any retention strategies. A false negative can result in a direct loss of revenue, and the company may also incur additional costs to acquire new customers to replace the ones that were lost.

In the context of churn prediction, False Negatives are typically more harmful because they represent missed opportunities for intervention. If a customer who is actually at risk of churning is incorrectly labeled as non-churning by the model, the company loses the chance to proactively retain that customer, resulting in a direct loss of revenue.
