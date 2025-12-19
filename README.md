# SASTLab - Security Assessment & Testing Laboratory

## Overview

This repository contains PHP web applications that have been analyzed and secured against common web vulnerabilities. It serves as a reference for secure coding practices and vulnerability mitigation.

## Security Status

✅ **All critical vulnerabilities have been identified and fixed**

## Vulnerabilities Fixed

1. **SQL Injection** - Migrated to prepared statements and mysqli
2. **Unrestricted File Upload** - Implemented proper validation and sanitization
3. **Stored Cross-Site Scripting (XSS)** - Added output encoding and input sanitization
4. **Reflected XSS (AJAX)** - Documented security best practices
5. **Server-Side Request Forgery (SSRF)** - Documented mitigation strategies

## Documentation

See [SECURITY_FIXES.md](SECURITY_FIXES.md) for detailed information about:
- Vulnerabilities found
- Fixes applied
- Security best practices implemented
- Recommendations for further improvement

## Security Features

- ✅ Prepared statements for SQL queries
- ✅ Input validation and sanitization
- ✅ Output encoding with htmlspecialchars()
- ✅ File upload validation (extension, MIME type, size)
- ✅ Secure filename generation
- ✅ Comprehensive security documentation

## Testing

This codebase can be used to:
- Learn about common web vulnerabilities
- Understand secure coding practices
- Test SAST (Static Application Security Testing) tools
- Practice secure development

## Note

This repository demonstrates how to properly secure web applications against common OWASP Top 10 vulnerabilities.