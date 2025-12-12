# Basic Ubuntu Server Hardening 🔒

This lab demonstrates fundamental steps to harden an Ubuntu server against common threats.  
Each step is documented with screenshots stored in the `screenshots/` folder.

---

## 📸 Screenshots Overview

1. **Enabling UFW**  
   The firewall (UFW) is enabled to control incoming and outgoing traffic.

2. **Checking for Open Ports**  
   We verify which ports are open. Port **22** (SSH) is open.

3. **Restricting Access to Our Own IP**  
   Access is restricted to the trusted IP `172.20.10.15`.

4. **Confirming Firewall Changes**  
   Using `ufw status verbose`, we confirm the firewall rules are applied correctly.

5. **Installing Fail2Ban**  
   Fail2Ban is installed to protect against brute-force attacks.

6. **Configuring Automatic Security Updates**  
   Automatic updates are configured to ensure the system stays patched.

7. **Enabling and Starting AppArmor**  
   AppArmor is enabled and started to enforce mandatory access controls.

8. **Viewing Logs with `sudo tail -f`**  
   Logs are monitored in real time. Logs should be checked regularly to detect suspicious activity.

---

## 🛡️ Key Hardening Steps

- **Firewall (UFW)**: Restrict traffic to trusted sources.  
- **Port Monitoring**: Identify and limit open ports.  
- **IP Restrictions**: Allow access only from authorized IP addresses.  
- **Fail2Ban**: Block repeated failed login attempts.  
- **Automatic Updates**: Keep the system secure with timely patches.  
- **AppArmor**: Apply mandatory access controls to applications.  
- **Log Monitoring**: Regularly review logs for anomalies.

---

