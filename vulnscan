#This is a bash script
#!/bin/bash

#For open PORTS
echo "Enter target IP Address/Hostname:"
read Target_IP

echo "Checking open ports on $Target_IP from 0 to 5000.."
for ((PORT=0; PORT<=5000; PORT++ )); do
        (echo > /dev/tcp/$Target_IP/$PORT) > /dev/null 2>&1 && echo "PORT $PORT is open"
done

#For Software Version
echo "Enter URL to check Software Version :"
read URL

echo "Checking Software Version for $URL"
VERSION_INFO=$(curl -I $URL 2>/dev/null | grep -i "Server:")
if [ -n "$VERSION_INFO" ]; then
        echo "Software Version info: $VERSION_INFO"
else
        echo "Could not get Software Version info."
fi
