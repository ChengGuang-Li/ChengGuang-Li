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
Markdown     8 hrs 12 mins         ████████▓░░░░░░░░░░░░░░░░   34.67 %
Other        5 hrs 25 mins         █████▓░░░░░░░░░░░░░░░░░░░   22.89 %
TypeScript   3 hrs 49 mins         ████░░░░░░░░░░░░░░░░░░░░░   16.13 %
JSON         2 hrs 47 mins         ███░░░░░░░░░░░░░░░░░░░░░░   11.75 %
Bash         1 hr 43 mins          █▓░░░░░░░░░░░░░░░░░░░░░░░   07.29 %
```

<!--END_SECTION:waka-->

