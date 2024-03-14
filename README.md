
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
JavaScript       15 hrs 57 mins  █████████████████████░░░░   83.97 %
JSON             1 hr 1 min      █▒░░░░░░░░░░░░░░░░░░░░░░░   05.39 %
Java             34 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.99 %
Other            29 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.56 %
YAML             26 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.35 %
```

<!--END_SECTION:waka-->
