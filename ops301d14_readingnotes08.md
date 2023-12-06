## Part 1 

1. **Explain each of the three A’s as you would to a non-technical family member. Use an analogy or a story.**

   - **Authentication:** It's like checking a patient's ID bracelet before allowing them into a secured medical area. You want to be sure they are who they say they are.

   - **Authorization:** Once inside, authorization is akin to the level of access different healthcare professionals have – a nurse might access to basic patient records, while a doctor has broader access for treatment decisions.

   - **Accounting:** Think of it as keeping a detailed record of every interaction with a patient – when they were seen, what treatments were given, ensuring a thorough history so there is a log of all the care received. You can go back through the log and make sure they got the right care and that the care was actually given.

2. **What should the administrator do if the ACS server fails to authenticate a user during AAA implementation?**

   - If the ACS server fails, use the local device's records as a backup for authentication.

3. **What is the role of the NAS in the AAA implementation using an ACS server? Use a diagram.**

   - **Diagram:**
   
     ```
     [User/Device] <--> [NAS] <--> [ACS Server]
     ```

   - **Role:**  It checks with the ACS Server to verify if the user/device has the right credentials before granting access to the network.

## Part 2

1. **What are the benefits of using RADIUS for authentication and authorization?**

   - **Centralized User Profiles:** RADIUS allows companies to maintain user profiles centrally, enhancing security and enabling consistent policies across all remote servers.

   - **Improved Security:** Centralized databases enable better security measures and policy enforcement, reducing vulnerabilities associated with distributed user management.

   - **Usage Tracking:** RADIUS facilitates easy tracking of user usage for billing and network statistics, crucial for internet service providers and network administrators.

2. **What is RADIUS and what does it stand for?**

   - **Definition:** RADIUS stands for Remote Authentication Dial-In User Service. It is a client-server protocol and software that enables remote access servers to communicate with a central server for authenticating dial-in users and authorizing their access to systems or services.

3. **Research: What encryption algorithms does RADIUS use?**

   - **Encryption Algorithms:** Password Authentication Protocol (PAP) or Challenge Handsake Authentication Protocol (CHAP).

### sources: https://www.geeksforgeeks.org/computer-network-aaa-authentication-authorization-and-accounting/; https://archive.is/27Y19#selection-867.0-2090.0