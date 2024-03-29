









```
r language BS10, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis granüler hücreli tümör, kolon , echo = (language == "TR")
## BS10 - granüler hücreli tümör, kolon {#sec-BS10 }
```


```
asis granular cell tumor, colon , echo = (language == "EN")
## BS10 - granular cell tumor, colon {#sec-BS10 }
```






```
r BS10 screenshot HE1, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS10-HE1_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS10/HE1.html",
  file = "./screenshots/BS10-HE1_screenshot.png"
)
}
```






```
r BS10 screenshot HE2, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS10-HE2_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS10/HE2.html",
  file = "./screenshots/BS10-HE2_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link







```
asis, echo = (language == "TR")

**granüler hücreli tümör, kolon**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS10-HE1_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS10/HE1.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS10/HE1.html)
```

```
asis, echo = (language == "EN")

**granular cell tumor, colon**

[![Click for Full Screen WSI](./screenshots/BS10-HE1_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS10/HE1.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS10/HE1.html)

```






```
asis, echo = (language == "TR")

**granüler hücreli tümör, kolon**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS10-HE2_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS10/HE2.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS10/HE2.html)
```

```
asis, echo = (language == "EN")

**granular cell tumor, colon**

[![Click for Full Screen WSI](./screenshots/BS10-HE2_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS10/HE2.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS10/HE2.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS10/HE1.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS10/HE1.html" style="height:600px;width:100%;" data-external="1"></iframe>

```







```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS10/HE2.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS10/HE2.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

granüler hücreli tümör, kolon

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

granular cell tumor, colon

:::

```









:::::












