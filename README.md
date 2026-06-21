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
TypeScript   2 hrs 42 mins         █████████▓░░░░░░░░░░░░░░░   38.25 %
Other        1 hr 51 mins          ██████▓░░░░░░░░░░░░░░░░░░   26.06 %
Python       1 hr 23 mins          █████░░░░░░░░░░░░░░░░░░░░   19.49 %
Markdown     1 hr 3 mins           ███▓░░░░░░░░░░░░░░░░░░░░░   14.83 %
Prisma       5 mins                ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.28 %
```

<!--END_SECTION:waka-->

