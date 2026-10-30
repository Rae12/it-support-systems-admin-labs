
# Ticket 001: [Expired Password Preventing Computer Login]

## Ticket Information
- **Platform:** ServiceDesk Simulator
- **Status:** Resolved
- **Priority:** High
- **Ticket Type:** [Account Access / Password expiration]
- **Environment:** Simulated IT support environment

## 1. Issue Summary
A user returned from a three-week vacation and was unable to sign in to their computer.
The sign-in screen indicated that the user's password had expired and prompted them to change it,
but the user could not complete the password change from the login screen.

## 2. Business Impact

The ticket was marked High priority because the affected user was the lead developer on a 
payment-processing module with an approaching sprint deadline.

The inability to access the development environment could delay development work 
and affect the team's delivery timeline.

## 3. Troubleshooting Performed
1. [Located the user account:] Opened Tools → Directory, searched for the username mgarcia, and selected the matching directory entry.
2. [Opened authentication settings:] Navigated to the Authentication tab.
3. [Initiated identity verification:] Selected Send Verification Code.
4. [Verified the user's identity:] Contacted the user through Company Chat, requested the verification code, and entered it into the simulator.
5. [Reset the password:] After the identity verification succeeded, selected Reset Password to generate a temporary password.
6. [Delivered the temporary password:] Sent the temporary password through Company Chat, following the simulator's specified workflow rather than sending it by email.
7. [Communicated next steps:] Instructed the user to change the temporary password at their first login.

## 4. Resolution
The user's identity was verified, a temporary password was generated, and the user was provided with instructions to change it at their first login.

The ServiceDesk Simulator ticket displayed a Resolved status.

## 5. Verification
Identity verification:] The user supplied the verification code, which was entered into the simulator before the password reset.

Ticket status:] The simulator displayed the ticket as Resolved.

Post-reset login:] A successful login was not independently documented in the available evidence.

## 7. Technical Skills Demonstrated
- [User directory navigation and account lookup]
- [Identity verification and authentication workflows]
- [Password-reset procedures and temporary credentials]
- [Secure account-recovery practices]
- [User communication and support documentation]
- [Incident prioritization based on business impact]
- [Following a structured troubleshooting process]

## 8. Lessons Learned
Password-expiration issues may require additional troubleshooting when the user cannot change their password through the normal login process.

Verifying identity before resetting credentials is essential to protecting user accounts. Clear communication also helps users understand how to regain access and what they must do after receiving a temporary password.

## 9. Evidence
- Screenshot: ([it-support-systems-admin-labs/screenshots/Ticket001.PNG](https://github.com/Rae12/it-support-systems-admin-labs/blob/main/screenshots/Ticket001.PNG))
- Notes: [Add any relevant observations]

## 10. Reflection
What would I do differently or investigate further
in a real-world IT environment?
