
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
JavaScript    28 hrs 19 mins  █████████████████████▒░░░   85.25 %
Image (svg)   1 hr 20 mins    █░░░░░░░░░░░░░░░░░░░░░░░░   04.01 %
JSON          53 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.68 %
CSS           42 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.11 %
Java          33 mins         ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.68 %
```

<!--END_SECTION:waka-->
