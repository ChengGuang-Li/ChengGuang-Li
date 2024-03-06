
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
Other        5 hrs 52 mins   ███████████████░░░░░░░░░░   60.13 %
Python       3 hrs 30 mins   █████████░░░░░░░░░░░░░░░░   35.96 %
Bash         8 mins          ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.41 %
Markdown     7 mins          ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.29 %
CSV          5 mins          ▒░░░░░░░░░░░░░░░░░░░░░░░░   00.90 %
```

<!--END_SECTION:waka-->
