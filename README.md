
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
Java             9 hrs 43 mins   ████████████████████░░░░░   80.25 %
XML              59 mins         ██░░░░░░░░░░░░░░░░░░░░░░░   08.22 %
Markdown         39 mins         █▒░░░░░░░░░░░░░░░░░░░░░░░   05.40 %
YAML             24 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   03.43 %
HTTP Request     12 mins         ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.75 %
```

<!--END_SECTION:waka-->
