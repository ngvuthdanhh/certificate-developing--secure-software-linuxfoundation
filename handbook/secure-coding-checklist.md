# Secure Coding Checklist

## Input Validation
- [ ] Validate all inputs (length, type, format).  
- [ ] Reject by default, allow only safe values.  
- [ ] Use whitelisting instead of blacklisting.  

## Authentication
- [ ] Enforce strong password policies.  
- [ ] Store passwords using Argon2/bcrypt/scrypt.  
- [ ] Enable MFA.  
- [ ] Prevent brute force with rate limiting.  

## Authorization
- [ ] Enforce least privilege.  
- [ ] Use role-based or attribute-based access control.  
- [ ] Re-check authorization on every request.  

## Error Handling
- [ ] No stack traces or sensitive info in responses.  
- [ ] Log errors securely.  

## Cryptography
- [ ] Encrypt sensitive data at rest and in transit.  
- [ ] Use TLS 1.2+ only.  
- [ ] Rotate keys regularly.  

## Dependencies
- [ ] Maintain SBOM.  
- [ ] Automate dependency updates.  
- [ ] Scan with SCA tools.  
