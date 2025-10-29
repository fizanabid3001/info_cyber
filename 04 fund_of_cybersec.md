# fundamentals of computer security
## Identification, Authentication, and Authorization
|Concept                  |Description             |Examples                             |
|-------------------------|------------------------|-------------------------------------|
|**identification**       | Claiming and Identitiy | Typing username                     |
|**Authentication**       | Proving identity       | Entering password/Fingerprint       |
|**Authorization**        | Granting Access        | Accessing certain files after Login |

## Key Principle:
"Authentication verifies who you are, AUthorization decides what you can do."


# Authenticatoin methods
- Knowledge based: Paassword, Pins
- possession based: Smart cards, OTP Tokens
- Inherence Authentication (MFA): Combination of 2 or more above
- Single SIgn-on (SSO): One time login  across multiple systems (e.g, Google or Microsoft SSO)

 # Authorizatioin models
- DAC (Discretionary Access Control): owner decides who can access (windows permissions).
- MAC (Mandatory Access control): Access based on classification levels (military systems),
- RBAC (Role-Based Access control): Permissions assigned to role (admin, manager, user).
- ABAC (Attribute-based access control): Access based on conditions (time, location, user type).

 ## Example
 An "HR Manager" role can view employee data, While "Employee" role can only view their own profiles

 # Best practices
- Use strong, unique passwords
- Apply MFA wherever possible
- review role-based permission reuglarly
- Log All authentication and access events
