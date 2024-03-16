
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
JavaScript    30 hrs 15 mins  █████████████████████▓░░░   86.84 %
Image (svg)   55 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.66 %
Other         53 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.58 %
JSON          49 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.38 %
Java          33 mins         ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.60 %
```

<!--END_SECTION:waka-->
