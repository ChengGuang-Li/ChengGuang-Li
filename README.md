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
Python       11 hrs 10 mins  ██████████████████████░░░   88.26 %
Markdown     34 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   04.59 %
JSON         29 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   03.82 %
Other        18 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.43 %
Git Config   6 mins          ▒░░░░░░░░░░░░░░░░░░░░░░░░   00.80 %
```

<!--END_SECTION:waka-->

