# Registration Form

## Overview
This registration form provides a simple interface for users to create a new account.

## Form Fields

### Username
- **Type**: Text input
- **Required**: Yes
- **Constraints**: 3-20 characters, alphanumeric and underscores only

### Email
- **Type**: Email input
- **Required**: Yes
- **Validation**: Must be a valid email format

### Password
- **Type**: Password input
- **Required**: Yes
- **Constraints**: Minimum 8 characters, must include uppercase, lowercase, and numbers

### Confirm Password
- **Type**: Password input
- **Required**: Yes
- **Validation**: Must match the Password field

### Terms & Conditions
- **Type**: Checkbox
- **Required**: Yes
- **Description**: User must agree to terms before submission

## Submission

- **Submit Button**: Validates all fields before processing
- **Error Handling**: Displays field-specific error messages
- **Success**: Redirects to login page upon successful registration

## Features

- Real-time field validation
- Clear error messages
- Responsive design
- Secure password handling
