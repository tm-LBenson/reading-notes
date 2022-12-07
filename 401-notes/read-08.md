# Reading: Access Control (ACL)  
## Reading  
[5 steps to RBAC](https://www.csoonline.com/article/3060780/5-steps-to-simple-role-based-access-control.html)  
  
### What is Role Based Access Control (RBAC), and why do we care?  
  
  RBAC allows users access to data based on assigned roles, such as an admin having access to configs or a doctor having access to patient data. 
  We care because we need a way to separate data from different groups of people. 
  
### Describe a Role/Permission hierarchy that you might implement using RBAC.  
  
  admin > manager > superviser > Basic users 
  
### What approach might you take to implement RBAC?  
>1. Inventory your systems  
>  
>2. Analyze your workforce and create roles  
>
>3. Assign people to roles  
>
>4. Never make one-off changes  
>
>5. Audit  
>
  
  
[wiki - RBAC](https://en.wikipedia.org/wiki/Role-based_access_control)  
  
### If Authentication is "you are who you say you are," what is Authorization?  
  
  The authorization has permission to access data because of the role assigned to you. 
  
### Name three primary rules defined for RBAC.  
  
>Role assignment: A subject can exercise permission only if the subject has selected or been assigned a role.   
>
>Role authorization: A subject's active role must be authorized for the subject. With rule 1 above, this rule ensures that users can take on only roles for which they are authorized.  
>
>Permission authorization: A subject can exercise a permission only if the permission is authorized for the subject's active role. With rules 1 and 2, this rule ensures that users can exercise only permissions for which they are authorized.  
>
  
### Describe RBAC to a non-technical friend.  
  
  RBAC is like allowing a doctor to see your medical history but not allowing other patients to view your files, even if they share the same doctor. Instead, the doctor has a role that allows him access to that information. 
  
  
## Videos  
  
[RBAC tutorial](https://www.youtube.com/watch?v=C4NP8Eon3cA&ab_channel=Udacity)  
  
### What Are access rights Associated with? The User? or The Role? Explain.  
  
  Rights are associated with the role. The role decides which rights the user can access because a user can be assigned a role. 
  
  
### Access Rights, or Authorization, is activated after a user successfully does what?  
  
  After a user successfully authenticates, access rights or authorization can be activated. 
  
### Explain how RBAC might benefit a business.  
  
  It can allow supervisors or managers to access different data than general users or employees. For example, a learning environment can enable a teacher to view all student's assignments but not let students see each other's work. 
  
## Reflection  
  
### What are your learning goals after reading and reviewing the class README?  
  My goals are to understand how to implement role access for all user types and build my applications with this structure in mind. 
  
  
  
