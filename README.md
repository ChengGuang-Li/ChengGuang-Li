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
JavaScript    21 hrs 44 mins  ████████████████▓░░░░░░░░   67.12 %
JSON          1 hr 52 mins    █▒░░░░░░░░░░░░░░░░░░░░░░░   05.80 %
Image (svg)   1 hr 34 mins    █▒░░░░░░░░░░░░░░░░░░░░░░░   04.85 %
Python        1 hr 31 mins    █▒░░░░░░░░░░░░░░░░░░░░░░░   04.70 %
Markdown      1 hr 11 mins    █░░░░░░░░░░░░░░░░░░░░░░░░   03.68 %
```

<!--END_SECTION:waka-->

