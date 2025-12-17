# Risk Matrix

## Purpose
The risk matrix helps prioritize threats by combining their **likelihood** and **impact**. This allows security managers to focus resources where they are most needed.

## Risk Rating Scale

| Likelihood | Description |
|------------|-------------|
| Low        | Unlikely to occur in the foreseeable future |
| Medium     | May occur occasionally |
| High       | Likely to occur frequently |

| Impact | Description |
|--------|-------------|
| Low    | Minor damage or disruption |
| Medium | Moderate damage, operational disruption |
| High   | Severe damage, threat to life, critical disruption |

## Risk Matrix Table

| Threat / Vulnerability | Likelihood | Impact | Risk Level |
|------------------------|-----------|--------|------------|
| Bomb Threat / Poor access control | High      | High   | Extreme    |
| Unauthorized Access / Weak locks | Medium    | Medium | Medium     |
| Insider Threat / Lack of procedures | Low       | High   | Medium     |
| Theft / Inadequate CCTV coverage  | Medium    | Medium | Medium     |

## Instructions
1. Identify all threats (see `threat-identification.md`)
2. Identify vulnerabilities (see `vulnerability-assessment.md`)
3. Assign Likelihood and Impact for each combination
4. Calculate Risk Level:  
   - Low + Low → Low  
   - Medium + Medium → Medium  
   - High + High → Extreme
5. Prioritize mitigation based on Risk Level

## Notes
- Review and update periodically
- Include new threats or changes to facility layout
- Document mitigation actions in `/04-standard-operating-procedures`
