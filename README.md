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
Python       2 hrs 24 mins   ██████████████████▓░░░░░░   74.65 %
Bash         24 mins         ███░░░░░░░░░░░░░░░░░░░░░░   12.56 %
Markdown     18 mins         ██▒░░░░░░░░░░░░░░░░░░░░░░   09.39 %
Other        4 mins          ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.53 %
Git Config   1 min           ▒░░░░░░░░░░░░░░░░░░░░░░░░   00.68 %
```

<!--END_SECTION:waka-->

