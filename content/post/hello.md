+++
date = "2017-01-07T23:05:27-06:00"
title = "hello"
tags = ["misc", "test"]
categories = ["Misc"]

+++
# Header
This place will eventually contain various rants rambles and writings !

Stay tuned for more.[^1]

## Code Header 2
{{< highlight html >}}
<section id="main">
  <div>
    <h1 id="title">{{ .Title }}</h1>
    {{ range .Data.Pages }}
      {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
{{< /highlight >}}



[^1]: test footnote
