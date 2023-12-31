systemd service and timer file to show weather report to logged in users.

`cp weather-report.service /etc/systemd/system`
`cp weather-report.timer /etc/systemd/system`
`sudo systemctl deamon-relaod`
`sudo systemctl eanable weather-relaod.timer`