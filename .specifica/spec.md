# VulnerableApp — Learned Spec (sample)

> Placeholder inserted to verify the card + Approve→PR flow. A real
> cognium-ai `generate-spec` run replaces this.

## Overview
A Java/Spring web application that deliberately exposes a catalog of
web-security vulnerabilities for training and scanner benchmarking.

## Requirements
- The system **shall** expose HTTP endpoints demonstrating SQL injection,
  XSS, LDAP injection, SSRF, XXE, and path traversal.
- Each vulnerability **shall** be selectable by a difficulty level.
- The system **shall** persist car/user records via JDBC.
