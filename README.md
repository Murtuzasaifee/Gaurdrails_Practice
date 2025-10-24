# Guardrails AI Practice

A comprehensive exploration of **Guardrails AI**, an open-source framework for building reliable and safe LLM applications through input/output validation and guardrails.

## Overview

This project demonstrates various validation techniques using Guardrails AI to protect LLM applications from malicious inputs and unsafe outputs.

## Validators Implemented

- **Prompt Injection & Jailbreak Detection** - Detects and blocks prompt injection attacks and jailbreak attempts using ML-based detection
- **PII Detection** - Identifies and redacts personally identifiable information in text
- **Toxic Language Detection** - Filters out toxic, hateful, or offensive content
- **JSON Validation** - Ensures LLM outputs conform to expected JSON schemas
- **Custom Validation** - Implements custom validation logic using regex patterns
- **General Validators** - Explores core Guardrails AI validation capabilities

## Key Features

- **Guard Framework** - Uses Guardrails' `Guard` class to chain multiple validators
- **Hub Validators** - Leverages pre-built validators from Guardrails Hub
- **Custom Logic** - Implements custom validation patterns (e.g., regex-based prompt injection detection)
- **Validation Results** - Provides detailed validation feedback with scores and error messages

## Notebooks

All implementations are organized in Jupyter notebooks under the `notebooks/` directory for interactive exploration and testing.

## About Guardrails AI

Guardrails AI is a framework that helps developers:
- Validate and sanitize LLM inputs and outputs
- Implement safety guardrails for production LLM applications
- Combine multiple validators for comprehensive protection
- Create custom validators for domain-specific requirements

Learn more: [Guardrails AI Documentation](https://www.guardrailsai.com/docs)
