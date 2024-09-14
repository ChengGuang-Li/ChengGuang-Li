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
TypeScript    21 hrs 48 mins  ████████████████▓░░░░░░░░   66.85 %
YAML          5 hrs 2 mins    ████░░░░░░░░░░░░░░░░░░░░░   15.46 %
Docker        2 hrs 37 mins   ██░░░░░░░░░░░░░░░░░░░░░░░   08.07 %
Other         49 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.55 %
JSON          33 mins         ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.74 %
```

<!--END_SECTION:waka-->

