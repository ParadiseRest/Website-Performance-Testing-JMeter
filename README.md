# Website-Performance-Testing-JMeter
Performance testing of a website using JMeter.
# Website Performance Testing using JMeter

This project demonstrates performance testing on a website using Apache JMeter. We perform load testing to simulate multiple users accessing the application and collect performance metrics such as response time and throughput.

## Project Structure
- `website_performance_test.jmx`: JMeter script to load test a website.
- `performance_test_results.md`: Detailed report of the performance testing.

## How to Run the Test
1. Install [JMeter](https://jmeter.apache.org/download_jmeter.cgi).
2. Open JMeter and load the `website_performance_test.jmx` file.
3. Run the test to simulate 50 users accessing the website over a 10-second ramp-up period.
4. Review the test results in JMeter's "Aggregate Graph" or "View Results Tree".

## Test Summary
- **Website URL**: https://example.com
- **Test Duration**: 15 seconds
- **Number of Users**: 50
- **Metrics Collected**: Response time, throughput, error rate, and more.
