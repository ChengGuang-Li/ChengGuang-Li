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
JavaScript       12 hrs 27 mins  ██████████████▒░░░░░░░░░░   57.57 %
Java             6 hrs 24 mins   ███████▒░░░░░░░░░░░░░░░░░   29.63 %
XML              44 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   03.39 %
Markdown         39 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   03.02 %
Other            26 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.06 %
```

<!--END_SECTION:waka-->

