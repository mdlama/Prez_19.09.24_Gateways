# Gateway design features for undergraduate education communities: A case study
### by M. Drew LaMar and Sam Donovan

This respository consists of the presentation slides for a talk given at [Gateways 2019](https://sciencegateways.org/web/gateways2019), September 23-25, 2019.

* **Conference Presentation**: LaMar, M. Drew; Donovan, Sam (2019): *Gateway design features for undergraduate education communities: A case study*. Gateways 2019. [doi:10.17605/OSF.IO/R5938](https://doi.org/10.17605/OSF.IO/R5938)
* **Conference Proceeding**: LaMar, M. Drew; Donovan, Sam (2019): *Gateway design features for undergraduate education communities: A case study*. Gateways 2019. [doi:10.17605/OSF.IO/35ZWS](https://doi.org/10.17605/OSF.IO/35ZWS)
* [Slideshow](https://mdlama.github.io/Prez_19.09.24_Gateways)

## Printing slides

After knitting the presentation, the slides can be printed to PDF using [decktape.js](https://github.com/astefanutti/decktape).  The following xaringan command should hopefuly work:

```r
xaringan::decktape("https://mdlama.github.io/Prez_19.09.24_Gateways", "EducationGateways.pdf", docker = TRUE)
```

This assumes you have the `astefanutti/decktape` docker container installed. To install the docker container:

```bash
docker pull astefanutti/decktape
```

## Acknowledgements

Slides created via the R package <a href="https://github.com/yihui/xaringan">xaringan</a>.

###### <img src="www/img/nsf-logo.jpg" height="50px" align="left">This material is based upon work supported by the National Science Foundation under DBI 1346584, DUE 1446269, DUE 1446258, and DUE 1446284.  Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation.