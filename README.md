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
TypeScript    18 hrs 34 mins  ██████████████████████▓░░   90.46 %
JavaScript    1 hr 37 mins    ██░░░░░░░░░░░░░░░░░░░░░░░   07.95 %
CSS           14 mins         ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.19 %
HTML          2 mins          ░░░░░░░░░░░░░░░░░░░░░░░░░   00.19 %
Image (svg)   2 mins          ░░░░░░░░░░░░░░░░░░░░░░░░░   00.17 %
```

<!--END_SECTION:waka-->

