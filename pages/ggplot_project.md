
---

### 📄 **ggplot_project.md**

```markdown
---
layout: single
title: "ggplot Project"
permalink: /ggplot_project/
author_profile: true

feature_row4:
  - image_path: assets/images/ggplot.jpg
    alt: "ggplot Project"
    excerpt: "Visualizations using ggplot2 in R."
    url: "/ggplot_project/"
    btn_class: "btn--inverse"
    btn_label: "See Visualizations"
---

# 📊 ggplot Visualization Project  

{% include feature_row id="feature_row4" type="left" %}

---

In this project, we visualized plant growth data using `ggplot2` in R.

### Example Code:
```r
library(ggplot2)
data <- data.frame(
  CO2 = c('Ambient', 'Elevated', 'Ambient', 'Elevated'),
  Growth = c(15, 20, 17, 22)
)

ggplot(data, aes(x = CO2, y = Growth, fill = CO2)) +
  geom_bar(stat = "identity") +
  theme_minimal() +
  labs(title = "Plant Growth Under CO2 Conditions", y = "Growth (cm)")
