# Security Best Practices Handbook

## General
- Treat security as part of quality.  
- Follow “secure by default” principle.  

## Web Applications
- Use prepared statements for SQL queries.  
- Escape/encode output to prevent XSS.  
- Implement CSRF protection.  

## APIs
- Always require authentication.  
- Implement rate limiting & quotas.  
- Prefer JWT with short expiration.  

## Infrastructure
- Apply least privilege to cloud IAM roles.  
- Encrypt storage buckets by default.  
- Scan containers before deployment.  

## Incident Response
- Maintain an IR plan.  
- Keep emergency contacts updated.  
- Run tabletop exercises quarterly.  
