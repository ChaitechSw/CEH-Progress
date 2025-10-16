## Module-3. Access Control Concepts

### Security Controls
1. Access control 
	- A safeguard designed preserve CIA triad 
	- Involves limiting what objects can be available to what subjects according to what rules.
	- Subjects: Any entity requesting access to assets, its active
	- Objects: Anything that a subject attempts to access, its passive
	- Rules: An instruction to allow or deny access to object for a validited identity of subject to an access control list (ACL)
### Control Assessments
### Defense in Depth
1. Assets are secured with 3 layers of security
	- Physical controls (outermost layer eg. biometric scanner)
	- Logical/Technical controls (eg. firewall)
	- Administrative controls (eg. ACL)
	
### Least Priviledge
1. Principal: Each user is granted access to only the items they need and nothing further.
2. The more critical information a person has access to, the greater the security should be around that access.

### Privileged access management (PAM)
1. PAM includes:
	- role-based specific subsets of privileges which are only activated in real time when the user identity is requesting the use of resource or service.
### Privileged Accounts
1. Classes of users with elevated/privileged accounts include:
	- System admins
	- IT support
	- Security analysts
 	- Supervisors
	- Leaderships
2. Measures for monitoring the possibility of elevated risks:
	- More extensive and detailed logging than regular user accounts
	- As compared to regular user accounts the access control for elevated users should be more stringent (eg. MFA)
	- Trust verification should be deeper for privileged users should be deeper than that of regular users. (eg. Background check, NDA)
	- More auditing than regular user accounts.
### Seperation of duties
1. Seperation of duties
	- No one person should control an entire high-risk transaction from start to finish.
	- Collusion is a fraud committed by two/more individuals willfully working together to bypass the seperation of duties.
	- Some personnel know one of the part of a security control (eg. a lock) and some know the other, but no one individually knows both of the parts. This is called as dual control.
2. Two-person integrity
	- Two person rule is a security control that requires minimum of two people to be in an area together, making it impossible for a person to be in an area alone.

### Authorized vs unauthorized personnel
1. Authentication, Authorization
	- Authentication is confirming the identity of a user while authorization refers to giving access to objects depending based on rules set to allow the user to complete the action.

