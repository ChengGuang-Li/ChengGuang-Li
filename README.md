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
TypeScript   11 hrs 58 mins  █████████████████████▒░░░   85.01 %
Other        42 mins         █▒░░░░░░░░░░░░░░░░░░░░░░░   05.02 %
Prisma       39 mins         █▒░░░░░░░░░░░░░░░░░░░░░░░   04.72 %
YAML         22 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.69 %
SQL          7 mins          ▒░░░░░░░░░░░░░░░░░░░░░░░░   00.86 %
```

<!--END_SECTION:waka-->

