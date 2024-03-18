
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
JavaScript    28 hrs 9 mins   ████████████████████▓░░░░   82.50 %
Image (svg)   1 hr 23 mins    █░░░░░░░░░░░░░░░░░░░░░░░░   04.08 %
Java          1 hr 22 mins    █░░░░░░░░░░░░░░░░░░░░░░░░   04.05 %
YAML          1 hr 7 mins     ▓░░░░░░░░░░░░░░░░░░░░░░░░   03.30 %
CSS           42 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.05 %
```

<!--END_SECTION:waka-->
