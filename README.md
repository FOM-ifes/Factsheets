# Factsheets
Kurzübersicht der Inhalte


## TeX-Pakete nachladen mittels TinyTeX


```{r}
> tinytex::tlmgr_install("extsizes")
> tinytex::tlmgr_install("preprint")
```

ggf. vorher TinyTeX updaten mittels:

```{r}
> tinytex::reinstall_tinytex(repository = "illinois")
```

Das sind alles R-Befehle, welche in der Console eingegeben werden sollten.
