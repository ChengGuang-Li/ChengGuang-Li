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
TypeScript   3 hrs 7 mins          ██████████░░░░░░░░░░░░░░░   39.53 %
Markdown     1 hr 57 mins          ██████▒░░░░░░░░░░░░░░░░░░   24.83 %
Other        1 hr 7 mins           ███▓░░░░░░░░░░░░░░░░░░░░░   14.32 %
JSON         56 mins               ███░░░░░░░░░░░░░░░░░░░░░░   11.94 %
Bash         24 mins               █▒░░░░░░░░░░░░░░░░░░░░░░░   05.14 %
```

<!--END_SECTION:waka-->

