# tubeplayR
play youtube by RStudio(RStudio Server).

![](src/pics/tubeplayR.png)

## install

```
devtools::install_github("kazutan/tubeplayR")
```

## How to Use

First, run `tubeplay()`, and YouTube video start at RStudio.

If you want another YouTube video, run `tubeplay(url = "want/play/the/url")`. 
Note argument `url` is a url for watch, **not embed url**.

Yes, Youtube playlist is compatible. 

## Envirnment to use this package

This package can use in follow environmnent:

- RStudio Server(Browser)
- RStudio Desktop version on Mac

RStudio Desktop version on Windows and Linux are not compatible. This causes RStudio's Qt... Please use virtual instance(e.g., Rocker).

## License

MIT.
