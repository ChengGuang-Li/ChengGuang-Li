
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
Java             6 hrs 33 mins   ███████████████████▒░░░░░   77.04 %
XML              44 mins         ██░░░░░░░░░░░░░░░░░░░░░░░   08.61 %
Markdown         39 mins         ██░░░░░░░░░░░░░░░░░░░░░░░   07.67 %
YAML             14 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.83 %
HTTP Request     12 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.49 %
```

<!--END_SECTION:waka-->
