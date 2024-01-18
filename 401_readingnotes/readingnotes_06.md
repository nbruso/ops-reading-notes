# Reading Notes 6

1. **How would you preserve the three elements of the CIA triad?**:
   - **Confidentiality**: I would use encryption to protect the files. This ensures that data is accessible only to the authorized individuals. Additionally, implementing two-factor authentication would further protect access, ensuring only verified users can access sensitive information.
   - **Integrity**: To maintain the integrity of the data, I would employ hash functions. This method is like giving each file a unique 'digital fingerprint'. Any alteration in the file's content would change this fingerprint, signaling potential tampering or corruption. 
   - **Availability**: I would set up redundant systems, such as multiple backup servers. This approach ensures that files remain accessible at all times, even in the case of a system failure or other events.

2. **Explain how hashing verifies data integrity using non-technical terms**:
   - Hashing functions work by creating a unique digital fingerprint for each file. The hash identifies a file just like a patient's medical record number itentifies them in an electronic health record system. If a file is altered in any way, its hash changes which indicates that the file has been modified. Uses hashes confirms that a file remains in its original, unaltered state.

3. **How is hashing and encryption different?**:
   - **Hashing:** is a one-way process that generates a unique identifier for a file, like a fingerprint or medical record number. It's used to verify that a file has not been altered. However, you cannot reverse a hash to reconstruct the original file.
   - **Encryption:** transforms data into a coded format that can only be read with a specific key or password. It ensures that data remains confidential and secure from unauthorized access. Unlike hashing, it's a reversible process.


#### sources: https://www.jscape.com/blog/implementing-the-cia-triad-when-transferring-files-through-the-internet; https://www.howtogeek.com/67241/htg-explains-what-are-md5-sha-1-hashes-and-how-do-i-check-them/