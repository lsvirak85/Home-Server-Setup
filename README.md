# **Home Server Setup and Optimization**  

## **Project Description**  
This project repurposes an old PC into a fully functional home server, providing remote access, media streaming, network-wide ad blocking, and system monitoring. The goal is to optimize performance, enhance security, and automate processes for an efficient home server setup.  

## **Key Features**  

- **Installed and Configured Ubuntu Server**: Deployed Ubuntu Server for stability, security, and customization.  
- **Remote Access Management**: Configured SSH for secure remote access and static IP assignment.  
- **Media and Network Services Deployment**: Installed and managed Jellyfin, PLEX for media streaming, and Pi-hole for network-wide ad blocking.  
- **Hardware Optimization**: Upgraded storage from HDD to SSD, improved airflow, and replaced thermal paste for enhanced performance.  
- **Network Configuration & Troubleshooting**: Utilized CLI tools to configure network settings and troubleshoot connectivity issues.  
- **Process Automation & System Monitoring**: Integrated Neofetch and Htop for real-time system diagnostics.  
- **File Management & Remote Transfers**: Set up SSH and WinSCP for seamless remote file access and data handling.  
- **Security & Power Management**: Implemented automatic power recovery settings in BIOS and secured remote login credentials.  

## **Technical Specifications**  

- **Operating System**: Ubuntu Server  
- **Programming Language(s)**: Bash scripting (for automation), Linux CLI  
- **Framework(s)**: N/A (utilizing native Linux tools)  
- **Database**: N/A (media and network services operate without dedicated databases)  
- **Deployment Environment**: Self-hosted on local hardware  

## **Development Roadmap**  

### **Phase 1: Initial Setup and Configuration**  
- **Milestone 1**: Install Ubuntu Server and configure SSH for remote access  
- **Milestone 2**: Set up a static IP and network configuration for stability  

### **Phase 2: Service Deployment and Optimization**  
- **Milestone 3**: Install and configure Jellyfin, PLEX, and Pi-hole for media and network management  
- **Milestone 4**: Upgrade hardware components (SSD, cooling optimization) for better efficiency  

### **Phase 3: Automation and Security Enhancements**  
- **Milestone 5**: Implement system monitoring tools and automate critical processes  
- **Milestone 6**: Enhance security configurations and set up automated backups  

## **Important Considerations**  

- **Challenges**:  
  - Hardware limitations (older components affecting performance)  
  - Ensuring network security while enabling remote access  
  - Managing storage and resource allocation efficiently  

- **Key Design Decisions**:  
  - Opted for Ubuntu Server due to its lightweight nature and extensive community support  
  - Prioritized open-source software for cost efficiency and customization  
  - Focused on modular service deployment to ensure easy future upgrades  
