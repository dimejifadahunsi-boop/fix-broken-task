There is an Apache-style access log at /app/access.log. Analyze the traffic it
records and write a summary report to /app/report.json.

The report must be a single JSON object with these three keys:

1. "total_requests" — integer: the total number of requests (non-empty lines) in
   the log.
2. "unique_ips" — integer: the number of distinct client IP addresses that made
   requests.
3. "top_path" — string: the request path that was requested most often (e.g.
   "/some/page.html").

You succeed when:

1. /app/report.json exists and contains a valid JSON object.
2. "total_requests" equals the number of requests in the log.
3. "unique_ips" equals the number of distinct client IPs in the log.
4. "top_path" is the most frequently requested path in the log.

You have 120 seconds to complete this task. Do not cheat by using online solutions or hints specific to this task.