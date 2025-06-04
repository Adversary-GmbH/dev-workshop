# Setup

Challenges/Chapters marked with ⚠️ need some special feature/background knowledge we haven't talked about. Ask Martin for details.

## Account
Set up your account at https://portswigger.net/users/register

## Tool
1. Download the current version of Caido from caido.io
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

## Medium
* https://portswigger.net/web-security/sql-injection/examining-the-database/lab-querying-database-version-mysql-microsoft
* https://portswigger.net/web-security/server-side-template-injection/exploiting/lab-server-side-template-injection-basic
* https://portswigger.net/web-security/file-upload/lab-file-upload-web-shell-upload-via-path-traversal

## Hard
* https://portswigger.net/web-security/file-upload/lab-file-upload-web-shell-upload-via-race-condition (⚠️ Needs special Burp functionality)

# A04:2021 Insecure Design

## Easy
* https://portswigger.net/web-security/logic-flaws/examples/lab-logic-flaws-excessive-trust-in-client-side-controls
* https://portswigger.net/web-security/logic-flaws/examples/lab-logic-flaws-flawed-enforcement-of-business-rules

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

* https://portswigger.net/web-security/authentication/password-based/lab-username-enumeration-via-subtly-different-responses (⚠️ Needs special Burp functionality)

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
