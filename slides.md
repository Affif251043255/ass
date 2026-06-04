---
title-slide: false
bibliography: references.bib
csl: vancouver.csl
citeproc: true
theme: serif
background-color: "#ffffff"
transition: slide
navigationMode: linear
hash: true
---

# Machine 1 SPC Report

---

:::: {.columns}
::: {.column width="50%"}
### Machine 1 Stability
**Control Analysis:**
- Pressure: 200kPa
- Temp: 338K
- Individual Control Chart (I-Chart)
:::

::: {.column width="50%"}
<iframe data-src='media/plots/m1_ichart.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Machine 1 Capability
**Statistical Summary:**
- Target: 50 | LSL: 45 | USL: 55
- Process Capability Analysis
- Calculated $C_{{pk}}$: 1.345
:::

::: {.column width="50%"}
<iframe data-src='media/plots/m1_cap.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Machine 2 Stability
**Control Analysis:**
- Pressure: 200kPa
- Temp: 338K
- Individual Control Chart (I-Chart)
:::

::: {.column width="50%"}
<iframe data-src='media/plots/m2_ichart.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Machine 2 Capability
**Statistical Summary:**
- Target: 50 | LSL: 45 | USL: 55
- $C_{{pk}}$ Performance
- Machine 2 demonstrates process centeredness under target conditions.
:::

::: {.column width="50%"}
<iframe data-src='media/plots/m2_cap.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Machine 1 Stability (User Data)
**Conditions:**
- Pressure: 200kPa | Temp: 338K
- Individual Control Chart
:::

::: {.column width="50%"}
<iframe data-src='media/plots/m1_ichart_custom.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Machine 1 Capability (User Data)
**Specs:**
- LSL: 45 | USL: 55 | Target: 50
- Calculated $C_{{pk}}$ Performance
:::

::: {.column width="50%"}
<iframe data-src='media/plots/m1_cap_custom.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::
