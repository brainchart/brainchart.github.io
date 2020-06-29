---
permalink: /
title: "main"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Under construction


## Example of displaying htmlwidgets on a Github pages site

```{r, warning = FALSE, echo = FALSE, message = FALSE}
# Source: http://www.htmlwidgets.org/showcase_plotly.html
library(plotly)
p <- ggplot(data = diamonds, aes(x = cut, fill = clarity)) +
            geom_bar(position = "dodge")
ggplotly(p)
```
