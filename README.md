# Simple Java Spring Boot Application

This repository contains a snapshot of a simple Java Spring Boot application.

## Getting Started

To get the application running on your server, follow these steps:

1. Clone this repository by running the following command:

  ```bash
   git clone https://github.com/ityourway/java-app-snapshot.git
   ```   

2. Navigate into the cloned repository:

   ```bash
   cd java-app-snapshot/
   ```

3. Install Java 17 by running the appropriate commands for your operating system:

   - For Ubuntu:
     ```bash
     sudo apt update
     sudo apt install openjdk-17-jdk -y
     ```

   - For Amazon Linux:
     ```bash
     sudo amazon-linux-extras install java-openjdk17 -y
     ```

4. After installing Java, run the application with the following command:

   ```bash
   java -jar blog-0.0.1-SNAPSHOT.jar &
   ```

   This command starts the application in the background.

5. Access the application on port 8081. Ensure that your firewall, security groups, and Network Access Control Lists (NACLs) allow inbound traffic on port 8081.

   Example URL: `http://your_server_public_ip:8081`

That's it! You should now have the Java Spring Boot application up and running on your server.
