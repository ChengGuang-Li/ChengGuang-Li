
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
JavaScript       14 hrs 47 mins  ███████████████████▓░░░░░   78.32 %
JSON             49 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   04.39 %
Java             46 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   04.11 %
Markdown         42 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   03.74 %
YAML             30 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.70 %
```

<!--END_SECTION:waka-->
