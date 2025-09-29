# Secure Coding Labs

## Lab 1: Input Validation
- Write a simple web form in Python/Flask or Node.js.  
- Implement input sanitization for text, email, and numeric fields.  
- Test against malicious payloads (e.g., `<script>alert(1)</script>`).  

**Goal:** Prevent injection attacks (XSS, SQLi).

---

## Lab 2: Safe File Handling
- Write a program that uploads and stores files.  
- Restrict allowed file types and size.  
- Implement random file naming to prevent path traversal.  

**Goal:** Ensure secure file uploads.

---

## Lab 3: Secure Password Storage
- Build a registration/login system.  
- Store passwords using bcrypt or Argon2.  
- Demonstrate difference between plaintext vs. hashed passwords.  

**Goal:** Understand secure password management.

---

## Lab 4: Error Handling
- Write a program with controlled error responses.  
- Log errors securely without leaking sensitive information.  

**Goal:** Avoid information disclosure via error messages.
