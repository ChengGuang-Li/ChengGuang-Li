
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
JavaScript       14 hrs 48 mins  ████████████████████▓░░░░   82.50 %
JSON             48 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   04.52 %
Markdown         29 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.77 %
Other            29 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.70 %
Java             28 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.66 %
```

<!--END_SECTION:waka-->
