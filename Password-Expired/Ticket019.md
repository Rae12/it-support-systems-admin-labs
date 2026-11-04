# Ticket 019: Executive Account Lockout and Expired Password

## Ticket Information
- **Platform:** ServiceDesk Simulator
- **Incident ID:** INC302041
- **Status:** Resolved
- **Priority:** Critical
- **Ticket Type:** Account Access / Account Lockout and Password Expiration
- **Environment:** Simulated IT support environment
- **Reported By:** Derek Chambers
- **Reported Via:** Voicemail
- **Employee ID:** EMP-0445
- **Username:** dchambers
- **Department:** Finance
- **Position:** CFO
- **Contact:** Extension 4010

## 1. Issue Summary

Derek Chambers, the company's CFO, contacted IT through voicemail because he was locked out of his computer.

He was frustrated because he needed to finish quarterly financial reports that were due to the SEC that same day.

Since he couldn't log in, he wasn't able to access the information and systems needed to complete his work.

After reviewing the issue, I needed to check his account in the Directory, verify his identity, and restore his access.

## 2. Business Impact

This ticket was marked Critical priority because Derek was unable to access his computer while working on time-sensitive financial reports.

The quarterly SEC reports were due that day, and being locked out could delay the reporting process.

Since this involved an executive account and an important financial deadline, restoring access quickly was necessary.

However, I still needed to follow the proper security procedures before making changes to his account.

## 3. Troubleshooting Performed

1. **Opened the Directory:** Navigated to the Directory from the ServiceDesk Simulator dashboard.

2. **Located the user's account:** Searched for the username "dchambers" and selected Derek Chambers's account.

3. **Started identity verification:** Used the Directory's verification process to send Derek a verification code.

4. **Verified the user's identity:** Completed the verification process before making any changes to his account.

5. **Checked the account status:** Confirmed that Derek's account was locked because of failed login attempts.

6. **Unlocked the account:** Once his identity was verified, unlocked his account to remove the login restriction.

7. **Reset the expired password:** Reset Derek's expired password so he could regain access to his computer.

8. **Verified the login:** Confirmed that Derek was able to sign in successfully after the account was unlocked and the password was reset.

## 4. Resolution

The issue was caused by Derek's account being locked after multiple failed login attempts, along with an expired password.

I located his account in the Directory and completed the identity verification process before making any changes.

Even though Derek was frustrated and needed immediate access, I made sure to follow the proper security steps.

After verifying his identity, I unlocked the account and reset the expired password.

I then confirmed that Derek could log in successfully.

The ServiceDesk Simulator displayed the ticket as Resolved.

## 5. Verification

**Account lookup:** Located Derek's account using the username dchambers.

**Identity verification:** Completed the verification process before making account changes.

**Account status:** Confirmed that the account was locked due to failed login attempts.

**Account unlock:** Removed the account lockout.

**Password reset:** Reset the expired password.

**Login confirmation:** Confirmed that Derek could successfully sign in.

**Ticket status:** The ServiceDesk Simulator displayed the incident as Resolved.

## 6. Technical Skills Demonstrated

- User account management
- Directory navigation and account lookup
- Account lockout troubleshooting
- Password expiration troubleshooting
- Identity verification and authentication
- Password reset procedures
- Unlocking user accounts
- Handling critical IT incidents
- Supporting executive users
- Incident prioritization based on business impact
- Following security procedures under pressure
- User communication and incident resolution

## 7. Lessons Learned

This ticket taught me how important it is to stay calm and follow security procedures, even when someone is frustrated or needs immediate help.

Derek was upset because he couldn't access his computer, and he had an important deadline coming up.

Even though the situation was urgent, I couldn't skip identity verification just to resolve the issue faster.

I had to make sure I was working with the correct person before unlocking the account or resetting the password.

I also learned that an account lockout and an expired password can happen at the same time.

Simply unlocking the account wouldn't have completely fixed the problem because Derek's password still needed to be reset.

By addressing both issues, I was able to restore his access.

## 8. Evidence

- Screenshot: ![Ticket 019 - Executive Account Lockout](../screenshots/Ticket019.PNG)

## 9. Reflection

**What would I do differently or investigate further in a real-world IT environment?**

In a real IT environment, I would first verify Derek's identity using the company's approved verification process before making any account changes.

I would also review the account's login history to understand why it became locked.

For example, I would check whether the failed login attempts were caused by an expired password, incorrect credentials, or another authentication issue.

If the account was managed through Active Directory or Microsoft Entra ID, I would review the available account status and sign-in information.

After unlocking the account and resetting the password, I would have Derek sign in himself and confirm that he could access the systems needed for his financial reporting.

I would also check whether there were any signs of suspicious login activity that needed to be reported to the security team.

Since this was a Critical priority incident, I would keep communication clear and provide updates while working on the issue.

Finally, I would document the steps taken and make sure no passwords or verification codes were recorded in the ticket.
