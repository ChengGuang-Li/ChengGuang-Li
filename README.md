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
TypeScript   9 hrs 8 mins    ██████████░░░░░░░░░░░░░░░   40.07 %
JSON         6 hrs 14 mins   ███████░░░░░░░░░░░░░░░░░░   27.38 %
Markdown     3 hrs 11 mins   ███▒░░░░░░░░░░░░░░░░░░░░░   13.98 %
JavaScript   1 hr 44 mins    ██░░░░░░░░░░░░░░░░░░░░░░░   07.61 %
Other        1 hr 9 mins     █▒░░░░░░░░░░░░░░░░░░░░░░░   05.06 %
```

<!--END_SECTION:waka-->

