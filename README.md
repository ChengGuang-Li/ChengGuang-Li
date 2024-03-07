
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
Java             11 hrs 17 mins  ████████████████████▓░░░░   83.17 %
XML              1 hr 2 mins     ██░░░░░░░░░░░░░░░░░░░░░░░   07.74 %
HTTP Request     26 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   03.28 %
YAML             24 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   03.06 %
Markdown         18 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.30 %
```

<!--END_SECTION:waka-->
