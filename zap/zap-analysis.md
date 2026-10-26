# OWASP ZAP Web Application Testing

## Objective

To learn basic web application traffic inspection using OWASP ZAP in a controlled local environment.

## Tool

* OWASP ZAP 2.17.0
* Python HTTP Server

## Target

`http://127.0.0.1:8081`

## Activities Performed

1. Started a local Python HTTP server.
2. Opened OWASP ZAP.
3. Accessed the local target URL through ZAP.
4. Observed the HTTP GET request in the Sites and History panels.
5. Checked the Alerts panel for reported security issues.

## Observations

* The local website responded with HTTP status `200 OK`.
* ZAP recorded a GET request to the local target.
* Security alerts must be documented only after reviewing the Alerts panel.

## Conclusion

OWASP ZAP was used to inspect HTTP traffic from a locally hosted test website. This exercise provided practical experience with request history and basic security alert review.

## Scope

Testing was limited to a local application controlled by the user.
