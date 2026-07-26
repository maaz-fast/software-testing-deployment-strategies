# NexaCare Solutions: Non Functional Requirements Kit

**Prepared by:** Muhammad Maaz Bin Imtiaz  
**Role:** Systems Analyst  
**Project:** Appointment Scheduling Platform – Version 3.0 Release  
**Date:** 26/07/2026

---

## 8. Non-functional requirements and performance plan

### A. Non-functional requirements (NFRs) definition

| NFR category | Specific requirement | Target value | Measurement method |
| :--- | :--- | :--- | :--- |
| **Performance** | Appointment booking completion time | < 3 seconds | APM API response time monitoring |
| **Scalability** | Peak concurrent users capacity | 2500 users | Load testing & Real-time active sessions |
| **Reliability** | System uptime during operational hours | 99.9% | Synthetic ping monitoring |
| **Availability** | Real-time availability update propagation | < 5 seconds | End-to-end telemetry |
| **Latency** | SMS delivery trigger latency | < 2 minutes | Application log timestamps |

### B. Golden signals monitoring plan

| Golden signal | Metric name | How to measure | Target/Threshold | Business impact |
| :--- | :--- | :--- | :--- | :--- |
| **Latency** | API response time P95 | APM Dashboard | < 3 seconds | Slow bookings cause frustration and clinic inefficiency. |
| **Traffic** | Active concurrent users | Real-time sessions | > 2500 (Alert) | Informs auto-scaling triggers to handle Monday peaks. |
| **Errors** | HTTP 5xx error rate | Error tracking tool | < 0.5% | Failed bookings lead directly to lost appointments and revenue. |
| **Saturation** | Database connection pool utilization | Database metrics | < 80% | Connection exhaustion causes cascading system failures. |

### C. Peak traffic preparation (Monday 8-10 AM)

**Infrastructure Adjustments:** 
Pre-provision additional application servers via Auto-Scaling Groups at 7:30 AM on Monday to proactively handle the 3-5x traffic spike (1500-2500 users), rather than waiting for reactive scaling triggers. Enable Redis caching for read-heavy operations like provider availability.

**Adjusted Thresholds:**

| Metric | Normal threshold | Peak period threshold | Reasoning |
| :--- | :--- | :--- | :--- |
| **Database CPU** | > 80% alert | > 92% alert | Higher utilization is expected; adjust to avoid alert fatigue while maintaining safety. |
| **API response time (P95)** | > 2s alert | > 4s alert | Accept slightly degraded performance during the massive rush rather than paging on-call for expected strain. |
| **Active Users** | > 600 alert | > 2600 alert | Baseline traffic increases 5x; alerts should only trigger if traffic exceeds predicted peak capacity. |

**Performance Degradation Plan:** 
If API response times exceed 5 seconds, non-critical background jobs (e.g., daily report generation) will be automatically suspended to free up database resources for core booking workflows.
