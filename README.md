```bash
#!/bin/bash

echo "Enter 'profile' to see my information, or 'quit' to exit:"
while true; do
    read INPUT_STRING
    case $INPUT_STRING in
        profile)
            echo "Name: Chengguang Li"
            echo "Interests: fitness, outdoors, football"
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

<!--Contribution Graph-->
<table>
  <tr>
    <td>
      <picture>
        <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=chengguang-li&theme=xcode&bg_color=FF000000&color=000000&hide_border=true" />
        <img src="https://github-readme-activity-graph.vercel.app/graph?username=chengguang-li&theme=xcode&bg_color=FF000000&hide_border=true" />
      </picture>
  </tr>
</table>

📊 **Weekly development breakdown**

<!--START_SECTION:waka-->

```txt
JSON         6 hrs 2 mins    ██████████████░░░░░░░░░░░   55.47 %
Python       3 hrs 37 mins   ████████▒░░░░░░░░░░░░░░░░   33.21 %
Markdown     39 mins         █▒░░░░░░░░░░░░░░░░░░░░░░░   05.98 %
Text         22 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   03.48 %
Other        10 mins         ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.66 %
```

<!--END_SECTION:waka-->

