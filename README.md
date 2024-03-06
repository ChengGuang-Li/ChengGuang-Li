
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
Java             10 hrs 36 mins  █████████████████████▓░░░   86.75 %
XML              53 mins         █▓░░░░░░░░░░░░░░░░░░░░░░░   07.30 %
YAML             21 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.87 %
HTTP Request     13 mins         ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.90 %
Markdown         6 mins          ▒░░░░░░░░░░░░░░░░░░░░░░░░   00.84 %
```

<!--END_SECTION:waka-->
