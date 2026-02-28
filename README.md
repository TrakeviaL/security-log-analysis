 Security Log Analysis Project
## Objective
Analyze authentication and firewall logs to identify potential security threats and determine whether malicious activity is present.
## Scenario
A system generated multiple failed login alerts within a short period. The objective is to determine whether this activity represents a brute-force attack or normal user behavior.
## Log Review Process
1. Reviewed authentication logs for failed login attempts.
2. Identified repeated failed attempts from a single IP address.
3. Analyzed timestamps to determine frequency pattern.
4. Checked whether multiple user accounts were targeted.
5. Evaluated whether successful login followed failed attempts.
## Indicators Observed
- High volume of failed login attempts within short time window
- Attempts originating from single external IP address
- Multiple usernames targeted
  ## Analysis
The repeated failed authentication attempts from a single IP address targeting multiple accounts within a short time frame are consistent with brute-force attack behavior.
## Conclusion
The activity observed indicates a likely brute-force login attempt. Recommended actions would include:
- Blocking the originating IP address
- Enforcing account lockout policies
- Reviewing affected accounts for compromise
- Monitoring for continued suspicious activity
## Skills Demonstrated
- Log analysis
- Threat pattern recognition
- Incident triage
- Escalation decision-making
- Documentation of findings
