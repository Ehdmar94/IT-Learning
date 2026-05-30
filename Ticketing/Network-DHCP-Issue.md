# Network Connectivity Issue (DHCP Failure)

## Issue

User reported being connected to WiFi but unable to access websites or internet resources.

## Troubleshooting

- Confirmed user was connected to WiFi
- Guided user to open PowerShell and run `ipconfig`
- Verified system had a 169.254.x.x IP address and no default gateway
- Determined device failed to obtain a valid IP address from DHCP

## Resolution

- Instructed user to run `ipconfig /release`
- Instructed user to run `ipconfig /renew`
- Verified device received a valid IP address and default gateway

## Outcome

Internet connectivity was restored and websites loaded successfully.

## Skills Demonstrated

- Network Troubleshooting
- DHCP Fundamentals
- Command Line Usage
- IP Address Analysis
- End User Support