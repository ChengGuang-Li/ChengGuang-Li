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
JavaScript    8 hrs 19 mins   █████████████████████░░░░   83.99 %
JSON          1 hr 13 mins    ███░░░░░░░░░░░░░░░░░░░░░░   12.30 %
Bash          14 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.48 %
HTML          6 mins          ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.02 %
Other         0 secs          ░░░░░░░░░░░░░░░░░░░░░░░░░   00.06 %
```

<!--END_SECTION:waka-->

