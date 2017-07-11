# Resource Monitor
Resource uptime monitor (e.g Internet and power)

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/b93ad4f1c7194112afcd942128f7150c)](https://www.codacy.com/app/neo_2/resource-monitor?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=neoighodaro/resource-monitor&amp;utm_campaign=Badge_Grade)

> *Note:* Ubuntu users may need to run the script through this `sed -i 's/\r$//' monitor.sh` for it to work

## Mac Beacon Installation
* Create the resource on the remote server and copy the UUID of the resource.
* Copy the `monitor.example.sh` to `monitor.sh` and then update the configuration inside. Update the `ACCESS_TOKEN` to match the value in your `.env` file.