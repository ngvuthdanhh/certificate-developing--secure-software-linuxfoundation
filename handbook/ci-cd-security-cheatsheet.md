# CI/CD Security Cheat Sheet

## Source Control
- [ ] Enable branch protection rules.  
- [ ] Require code review + signed commits.  
- [ ] Scan commits for secrets.  

## Build Pipeline
- [ ] Run SAST + SCA on every build.  
- [ ] Fail builds on critical vulnerabilities.  
- [ ] Sign build artifacts.  

## Deployment
- [ ] Use minimal base images.  
- [ ] Store secrets in a vault, not code.  
- [ ] Enable automated rollback on failed deployment.  

## Monitoring
- [ ] Collect logs centrally.  
- [ ] Integrate with SIEM/IDS.  
- [ ] Enable alerting for anomalous activities.  
