# Easy Mix Modeling

**Flagship technical project**

[View public repository](https://github.com/matheusfrote/Easy-Mix-Modeling-2)

## Problem

Marketing teams need to estimate incremental media contribution, understand uncertainty and allocate budget across channels without relying on last-click attribution alone.

## Solution

Easy Mix Modeling is a full-stack Marketing Mix Modeling application designed around Bayesian modeling and budget optimization. The public repository documents a React/TypeScript frontend, Express/Node backend and a Python statistical service using Google Meridian.

## Implemented / documented in the current repository

- Bayesian MMM workflow
- geometric adstock and Hill saturation concepts
- baseline vs. paid-media contribution
- marginal ROI and budget optimization
- what-if scenario simulation
- data-readiness diagnostics
- deterministic, auditable recommendation rules
- optional generative-AI narrative layer that does not perform the calculations
- local execution, test and production build workflow
- Python `mmm-service` with requirements and tests

## Stack

React 19 · TypeScript · Tailwind CSS · Recharts · Node.js · Express · Python · Google Meridian

## Product / engineering perspective

The project is not presented only as a statistical notebook. It combines model execution, user-facing workflows, diagnostics, budget decisions, reports and a local full-stack application.

## Current boundaries

The portfolio reflects what is documented in the public repository. Future connectors, infrastructure or product expansions should be treated as roadmap until they are present and validated in code.

## Business takeaway

MMM becomes useful when statistical output is translated into a decision: **where to invest, how much, with what expected incremental return and uncertainty**.
