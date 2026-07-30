# Business Requirements Document (BRD)

## Module

Login

---

## Purpose

The Login module allows authorized users to securely access the Apache Fineract Core Banking System.

Only authenticated users should be able to access the application.

---

## Business Objectives

- Allow authorized users to log in securely.
- Prevent unauthorized access.
- Protect sensitive banking information.
- Maintain user session security.

---

## Functional Requirements

### FR-001

The system shall allow users to log in using a valid username and password.

### FR-002

The system shall reject invalid login credentials.

### FR-003

The password field shall mask entered characters.

### FR-004

Username and Password are mandatory fields.

### FR-005

The system shall display an appropriate error message for invalid credentials.

### FR-006

Authenticated users shall be redirected to the Dashboard.

### FR-007

Users shall be able to log out successfully.

### FR-008

After logout, users shall not be able to access secured pages using the browser Back button.

### FR-009

User sessions shall expire after a predefined period of inactivity.

---

## Business Rules

- Username must be unique.
- Passwords are case-sensitive.
- Blank credentials are not allowed.
- Only active users can log in.
- Session timeout should occur after inactivity.

---

## Assumptions

- User account already exists.
- Application server is available.
- Database is accessible.

---

## Out of Scope

- User Registration
- Forgot Password
- Multi-Factor Authentication (MFA)

These modules will be covered separately.
