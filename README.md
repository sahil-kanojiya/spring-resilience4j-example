# Spring Resilience4j Fault Tolerance Examples

Implementation of distributed resilience patterns in Spring Boot microservices.

## Patterns Covered
- **Circuit Breaker**: Prevent cascading service failures when remote dependencies fail.
- **Rate Limiter**: Throttle incoming requests to protect internal capacity.
- **Retry**: Automated exponential backoff and jitter for transient errors.
- **Bulkhead**: Isolate resources (thread pools) per downstream service.
- **TimeLimiter**: Enforce timeouts on remote calls.

## Tech Stack
- Java 21 LTS
- Spring Boot, Resilience4j
- Spring Boot Actuator for health and metrics
- Maven Wrapper
