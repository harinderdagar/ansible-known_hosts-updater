# ansible-known_hosts-updater

Managing SSH keys manually can be cumbersome, especially in environments with many servers or frequently changing infrastructure.

### **Key Challenges:**
- **Manual Key Management:** Adding, updating, and maintaining SSH host keys manually in the `known_hosts` file is time-consuming and error-prone.
- **Scalability:** In large environments, manually updating the `known_hosts` file for each server becomes impractical.

### Solution Provided by the Script:
This Ansible playbook automates the process of fetching and adding SSH host keys to the `known_hosts` file for a specified group of hosts. By doing so, it ensures that:
- **Automated Key Management:** Host keys are automatically fetched and added, reducing manual effort.
- **Scalability:** The script can handle a large number of hosts, making it suitable for dynamic and large-scale environments.
