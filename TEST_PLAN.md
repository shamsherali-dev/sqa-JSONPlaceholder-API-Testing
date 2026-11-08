# Software Test Plan: ReqRes REST API Integration

## 1. Project Overview
This document outlines the testing approach for validating HTTP request methods, payload validation schemas, status codes, and error responses for the ReqRes backend platform.

## 2. Scope of Testing
- **Endpoints in Scope:** `/api/users`, `/api/login`, `/api/register`.
- **HTTP Methods:** `GET`, `POST`, `PUT`, `DELETE`.
- **Validation Criteria:** Response Status Codes ($200$, $201$, $400$, $404$), Response Headers, Payload Structures, and Latency Thresholds (< 2000ms).

## 3. Tools Used
- **API Tool:** Postman Desktop / Web Execution Environment.
- **Assertions:** JavaScript Test Scripts built into Postman collections.
