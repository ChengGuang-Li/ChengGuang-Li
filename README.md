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
TypeScript    22 hrs 59 mins  ███████████████████████░░   91.81 %
CSS           40 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.69 %
HTML          34 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.29 %
JavaScript    32 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.19 %
Image (svg)   15 mins         ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.01 %
```

<!--END_SECTION:waka-->

