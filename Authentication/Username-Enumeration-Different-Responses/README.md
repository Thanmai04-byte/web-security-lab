# Username Enumeration via Different Responses

## Lab Information

- **Platform:** PortSwigger Web Security Academy
- **Category:** Authentication
- **Vulnerability:** Username Enumeration
- **Difficulty:** Apprentice
- **Status:** Completed

## Objective

Identify a valid username by analyzing differences in the
application's responses to login attempts.

## Tools Used

- Burp Suite
- Web Browser
- PortSwigger Web Security Academy

## Methodology

### 1. Login Page

Opened the login page provided by the PortSwigger lab.

### 2. Intercepted Login Request

Used Burp Suite Proxy to intercept the login request.

### 3. Compared Responses

Tested different usernames and compared the responses.

I checked:

- Response message
- Response length
- HTTP status code
- Response body
- Error messages

### 4. Identified Username

A difference in the application's response helped identify
a valid username.

### 5. Lab Completion

Successfully completed the PortSwigger lab.

## What I Learned

- How to intercept login requests using Burp Suite
- How to analyze HTTP responses
- How username enumeration works
- How different responses can reveal valid usernames

## Mitigation

The application should provide a consistent error message
for both valid and invalid usernames.

Example:

`Invalid username or password`

## Evidence

Screenshots and request/response evidence will be added
to this project.
