
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
JavaScript    28 hrs          ████████████████████▓░░░░   82.11 %
Image (svg)   1 hr 23 mins    █░░░░░░░░░░░░░░░░░░░░░░░░   04.09 %
Java          1 hr 23 mins    █░░░░░░░░░░░░░░░░░░░░░░░░   04.06 %
YAML          55 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.69 %
Other         47 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.30 %
```

<!--END_SECTION:waka-->
