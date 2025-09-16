# Setup

Challenges/Chapters marked with ⚠️ need some special feature/background knowledge we haven't talked about. Ask Martin for details.

## Accounts
1. Set up your account at https://portswigger.net/users/register
2. Use the following [Link](https://id.secdim.com/account/login?token=eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJjb21wYW55X2d1aWQiOjQ0MjI2NzIzNTQsImV4cCI6MTc1MTI3MTgxNX0.eBRPld6r7stR9qQ_q4J1N33d2R_6zc1oGR4bYnBW24MJ6Ovt9BuU5fnijn3Z7LaCkSygETpIJ1qKi-ugCJObhhqE-pdrNfL-E46P1l2iVe-tXmHQVcAISfSLvQU-9NWaRb1G2Drd0BhFVmA2KfUqw0Fh2N4UQ9pWm1KilAZ-doOMrT8CSyW8ugFdvCJsXSvJfAK6ynzzH1P9nFQZTh-ZrVeC83gtaSJ6Zwc4Q2QqjTsF-aafdEqkp87E5gh-psm03bZGSPBrbFg7fL3ccBZRLcP33rjRXSgxrL6srM8QH0RKYWFpttJlsSeoXQrWpYHyqlrlcXBraoxTPMTL-Z17qZAryF0uxQUqjaLkZ6SlzGephe53Gr9Zbzudwv-c1Fd0xGxJj9KePe85E519c3wPAvkK-8HOvVdeb1hvYqMREvvUjk4nv_D0Bj2DAuN8Uq9F9dkE99_0DkH1IPp2Tq3Wtzyp5bHVbc4uRPhedWabioW0ALvZitsN8-pTvIMJOEx4QroVoCtAr6CPHh8IZokLKME9AIDWLpH9iGnpJe4iHAtWDKTeRGPWN7YLFC6fi0zwru32bkctSQ9gCoDU1Jwqvo7SqEPSBexQV9XZ23h8hqs9O-crYgpEh7za4nHvwuqYJ5OKevI51lL8t19zMNCDiJmdSk9nMEO-dyLZUFQAHWc) to create an Account on SecDim
```
https://id.secdim.com/account/login?token=eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJjb21wYW55X2d1aWQiOjQ0MjI2NzIzNTQsImV4cCI6MTc1MTI3MTgxNX0.eBRPld6r7stR9qQ_q4J1N33d2R_6zc1oGR4bYnBW24MJ6Ovt9BuU5fnijn3Z7LaCkSygETpIJ1qKi-ugCJObhhqE-pdrNfL-E46P1l2iVe-tXmHQVcAISfSLvQU-9NWaRb1G2Drd0BhFVmA2KfUqw0Fh2N4UQ9pWm1KilAZ-doOMrT8CSyW8ugFdvCJsXSvJfAK6ynzzH1P9nFQZTh-ZrVeC83gtaSJ6Zwc4Q2QqjTsF-aafdEqkp87E5gh-psm03bZGSPBrbFg7fL3ccBZRLcP33rjRXSgxrL6srM8QH0RKYWFpttJlsSeoXQrWpYHyqlrlcXBraoxTPMTL-Z17qZAryF0uxQUqjaLkZ6SlzGephe53Gr9Zbzudwv-c1Fd0xGxJj9KePe85E519c3wPAvkK-8HOvVdeb1hvYqMREvvUjk4nv_D0Bj2DAuN8Uq9F9dkE99_0DkH1IPp2Tq3Wtzyp5bHVbc4uRPhedWabioW0ALvZitsN8-pTvIMJOEx4QroVoCtAr6CPHh8IZokLKME9AIDWLpH9iGnpJe4iHAtWDKTeRGPWN7YLFC6fi0zwru32bkctSQ9gCoDU1Jwqvo7SqEPSBexQV9XZ23h8hqs9O-crYgpEh7za4nHvwuqYJ5OKevI51lL8t19zMNCDiJmdSk9nMEO-dyLZUFQAHWc
```

## Tool
1. Download the current version of Caido from https://caido.io/download
2. Install and run it
3. When you see the instance "localhost:8080", click "Start"
4. You're prompted for a login, we can "continue as guest" for today

## Wordlists
If you need a list of $SOMETHING, this one should be enough for our needs today:
https://raw.githubusercontent.com/danielmiessler/SecLists/refs/heads/master/Discovery/Web-Content/common.txt


# A01:2021 Broken Access Controls

## Easy
* https://portswigger.net/web-security/access-control/lab-unprotected-admin-functionality
* https://portswigger.net/web-security/access-control/lab-user-id-controlled-by-request-parameter-with-password-disclosure
* https://portswigger.net/web-security/access-control/lab-insecure-direct-object-references


## Medium
* https://portswigger.net/web-security/file-path-traversal/lab-validate-start-of-path
* https://portswigger.net/web-security/file-path-traversal/lab-sequences-stripped-non-recursively
* https://portswigger.net/web-security/api-testing/lab-exploiting-unused-api-endpoint

# A02:2021 Cryptographic Failures

# A03:2021 Injections

## Easy
* https://portswigger.net/web-security/os-command-injection/lab-simple
* https://portswigger.net/web-security/sql-injection/lab-login-bypass
* https://portswigger.net/web-security/nosql-injection/lab-nosql-injection-bypass-authentication
* https://portswigger.net/web-security/cross-site-scripting/reflected/lab-html-context-nothing-encoded
* https://portswigger.net/web-security/file-upload/lab-file-upload-remote-code-execution-via-web-shell-upload
* https://portswigger.net/web-security/file-upload/lab-file-upload-web-shell-upload-via-content-type-restriction-bypass
* https://portswigger.net/web-security/llm-attacks/lab-exploiting-llm-apis-with-excessive-agency

## Medium
* https://portswigger.net/web-security/sql-injection/examining-the-database/lab-querying-database-version-mysql-microsoft
* https://portswigger.net/web-security/server-side-template-injection/exploiting/lab-server-side-template-injection-basic
* https://portswigger.net/web-security/file-upload/lab-file-upload-web-shell-upload-via-path-traversal
* https://portswigger.net/web-security/llm-attacks/lab-indirect-prompt-injection

## Hard
* https://portswigger.net/web-security/file-upload/lab-file-upload-web-shell-upload-via-race-condition (⚠️ Needs special functionality)

## LLMs
- https://gandalf.lakera.ai

# A04:2021 Insecure Design

## Easy
* https://portswigger.net/web-security/logic-flaws/examples/lab-logic-flaws-excessive-trust-in-client-side-controls
* https://portswigger.net/web-security/logic-flaws/examples/lab-logic-flaws-flawed-enforcement-of-business-rules (this one might be a bit far fetched)

## Medium
* https://portswigger.net/web-security/logic-flaws/examples/lab-logic-flaws-authentication-bypass-via-flawed-state-machine

# A05:2021 Security Misconfigurations

## Easy
* https://portswigger.net/web-security/information-disclosure/exploiting/lab-infoleak-in-error-messages
* https://portswigger.net/web-security/information-disclosure/exploiting/lab-infoleak-authentication-bypass

## Medium
* https://portswigger.net/web-security/information-disclosure/exploiting/lab-infoleak-in-version-control-history

# A06:2021 Vulnerable and Outdated Components

# A07:2021 Identification and Authentication Failures

## Easy
* https://portswigger.net/web-security/authentication/multi-factor/lab-2fa-simple-bypass
* https://portswigger.net/web-security/authentication/password-based/lab-username-enumeration-via-different-responses

## Medium
* https://portswigger.net/web-security/logic-flaws/examples/lab-logic-flaws-authentication-bypass-via-flawed-state-machine
* https://portswigger.net/web-security/authentication/multi-factor/lab-2fa-broken-logic

# OAuth

⚠️ Ask Martin to explain the exploit server.

## Medium

* https://portswigger.net/web-security/oauth/lab-oauth-account-hijacking-via-redirect-uri
* https://portswigger.net/web-security/oauth/lab-oauth-stealing-oauth-access-tokens-via-an-open-redirect

# A08:2021 Software and Data Integrity Failures

## Easy
* https://portswigger.net/web-security/deserialization/exploiting/lab-deserialization-modifying-serialized-objects

## Medium
* https://portswigger.net/web-security/deserialization/exploiting/lab-deserialization-exploiting-java-deserialization-with-apache-commons

# A09:2021 Logging and Monitoring Failures

# A10:2021 Server-Side Request Forgery

## Easy
* https://portswigger.net/web-security/ssrf/lab-basic-ssrf-against-localhost

## Medium
* https://portswigger.net/web-security/ssrf/lab-basic-ssrf-against-backend-system