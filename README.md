
```bash
#!/bin/bash

echo "Enter 'profile' to see my information, or 'quit' to exit:"
while true; do
    read INPUT_STRING
    case $INPUT_STRING in
        profile)
            echo "Name: Chengguang Li"
            echo "Interests: fitness, outdoors, soccers"
            echo "Learning: Distributed Systems, AWS, Image Processing"
            echo "Dev Devices: MSI on Windows, Macbook Pro M2"
            ;;
        quit)
            echo "Goodbye!"
            break
            ;;
        *)
            echo "Unknown command: $INPUT_STRING"
            echo "Enter 'profile' to see my information, or 'quit' to exit:"
            ;;
    esac
done

```

📊 **Weekly development breakdown**
<!--START_SECTION:waka-->

```txt
JavaScript       23 hrs 13 mins  ██████████████████████▒░░   89.20 %
JSON             1 hr 1 min      █░░░░░░░░░░░░░░░░░░░░░░░░   03.94 %
Java             33 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.15 %
Other            29 mins         ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.87 %
YAML             24 mins         ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.58 %
```

<!--END_SECTION:waka-->
