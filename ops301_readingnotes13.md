## Reading Notes 13

1. **What exactly is “Active Directory” and are the key services it provides?**
   - AD is Microsoft’s identity service for Windows networks.
   - Key services: AD DS, AD LDS, AD CS, AD FS, and AD RMS.
   - Manages users, resources, issues certificates, facilitates identity sharing, and controls access.

2. **What are the differences between a domain, forest, and tree in Active Directory?**
   - *Domain:* Objects with the same AD database.
   - *Tree:* Domains with a common DNS root.
   - *Forest:* Multiple trees sharing schema, global catalog, and config but not a contiguous namespace.

3. **How can objects (e.g. users, devices) within a domain be grouped?**
   - Objects grouped into OUs for simplified administration.
   - OUs mirror functional, geographical, or business structures.
   - Group policies applied to OUs for resource management.

4. **Explain the benefits of Active Directory, as you would to a family member.**
   - *Security:* Helps keep our digital stuff safe by controlling who can access it.
   - *Simplicity:* Makes it easier to manage our computer accounts and access to files.
   - *Extensibility:* Helps sort and arrange our digital things neatly.
   - *Resilency:* Keeps our computer stuff working even if one part breaks.


#### source: https://www.cyberark.com/what-is/active-directory/