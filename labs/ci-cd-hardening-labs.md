# CI/CD Hardening Labs

## Lab 1: Pipeline Security
- Create a sample CI pipeline (GitHub Actions / GitLab CI).  
- Add linting + SAST step (e.g., Semgrep).  
- Add dependency scanning step (SCA).  
- Block build on high severity issues.  

**Goal:** Automate security checks.

---

## Lab 2: Secrets Management
- Store a secret (API key) in environment variables.  
- Replace with a secret vault (e.g., HashiCorp Vault, GitHub Secrets).  
- Show difference in pipeline logs.  

**Goal:** Prevent hardcoded secrets.

---

## Lab 3: Signed Builds
- Enable artifact signing (e.g., Cosign or GPG).  
- Verify signature before deployment.  

**Goal:** Ensure integrity of build artifacts.

---

## Lab 4: Container Security
- Build a Docker image with a vulnerable base image.  
- Run Trivy or Grype to scan vulnerabilities.  
- Replace with a minimal secure base image (e.g., distroless, Alpine).  

**Goal:** Reduce container attack surface.
