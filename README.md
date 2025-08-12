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
JSON         8 hrs 22 mins   █████████▒░░░░░░░░░░░░░░░   37.24 %
TypeScript   6 hrs 45 mins   ███████▓░░░░░░░░░░░░░░░░░   30.05 %
Markdown     3 hrs 3 mins    ███▒░░░░░░░░░░░░░░░░░░░░░   13.58 %
JavaScript   1 hr 46 mins    ██░░░░░░░░░░░░░░░░░░░░░░░   07.90 %
Other        1 hr 9 mins     █▒░░░░░░░░░░░░░░░░░░░░░░░   05.13 %
```

<!--END_SECTION:waka-->

