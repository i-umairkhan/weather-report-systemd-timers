systemd service and timer file to show weather reports to logged-in users.

`cp weather-report.service /etc/systemd/system` </br>
`cp weather-report.timer /etc/systemd/system` </br>
`sudo systemctl deamon-relaod` </br>
`sudo systemctl eanable weather-relaod.timer` </br>
