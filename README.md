# NetTrace

NetTrace is a Kotlin-based network monitoring and diagnostic tool designed to help users understand network instability, detect connection interruptions, and compare Wi-Fi network performance.

# Project Goal

Online gaming requires a stable network connection, but unexpected latency spikes and disconnections can occur even when Wi-Fi signal strength appears strong.

NetTrace aims to help users investigate these problems by continuously monitoring network connectivity, recording network events, and analyzing network performance over time.

# MVP Scope

The first version of NetTrace will focus on four core features:

1. Network Connectivity Monitoring
    * Monitor connectivity to the default gateway and an external server.
    * Measure network latency at regular intervals.
2. Connection Failure Detection
    * Detect connection timeouts and failed connectivity checks.
    * Identify significant latency spikes.
3. Network Event Logging
    * Record latency measurements and connection failures.
    * Save timestamps and network statistics in CSV files.
4. Wi-Fi Benchmarking and Comparison
    * Calculate average latency, jitter, and connection failure rates.
    * Compare benchmark results collected from different Wi-Fi networks.
      
# Future Plans

The following features are planned for future development:

* 1. GUI: Build a desktop dashboard to visualize network performance.
  
* 2. Advanced Network Diagnostics: Provide more detailed analysis of potential network problems.
  
* 3. Automatic Wi-Fi Information Collection: Collect SSID, signal strength, frequency band, and access point information.

* 4. Real-Time Notifications: Alert users when significant latency spikes or connection interruptions occur.

# Technology Stack

Category	Technology
Programming Language: Kotlin (JVM 21)
Networking: Java Networking API
System Utilities:	macOS ping, route, networksetup
Build Tool:	Gradle (Kotlin DSL)
Data Storage:	CSV
Testing:	JUnit
Version Control: GitHub
Development Environment:	IntelliJ IDEA

# Project Documentation

The project planning documents are available in the docs/ directory.

Development Plan

The project will be developed incrementally through the following milestones:

1. Initialize the Kotlin project and Git repository.
2. Implement basic network connectivity checks.
3. Add automatic gateway detection.
4. Implement continuous network monitoring.
5. Add CSV logging for network measurements.
6. Implement Wi-Fi benchmarking.
7. Add benchmark comparison and basic diagnostics.
8. Test, document, and finalize the application.
