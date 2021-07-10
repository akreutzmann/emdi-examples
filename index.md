## Welcome to emdiToUse

The R package [**emdi**](https://cran.r-project.org/web/packages/emdi/index.html) provides a large collection of small area estimation methods. The package documentation and the vignettes serve the purpose to explain the available methods and/or to shows the functionality. This page will offer small examples for specific applications. 

For the most recent technical and methodological updates, **emdi** is available on [GitHub](https://github.com/SoerenPannier/emdi).

### Overview of the content in **emdi**

The methods implemented in **emdi** can be classified into following categories: 
- Direct estimation 
- Area-level models 
- Unit-level models 

While direct estimation is provided, the focus of the package are the small area estimation methods. Therefore, the following descriptions will focus on the small area estimation methods. 

#### Area-level models 

With function ´fh´, package **emdi** provides a large range of area-level models basically following the idea of Fay and Herriot (1979). The function includes following modelling options: 

* Basic area-level model
* Usage of transformations: log and arcsin 
* Spatial correlation 
* Measurement errors

#### Unit-level models 

Most unit-level models are based on the model proposed by Battesse, Harter and Fuller (1988). The model implemented in the package **emdi** is the empirical best prediction approach following Molina and Rao (2010). Additional features comprise the usage of transformations (Rojas-Perilla et al. 2020) and the inclusion of sampling weights (Guadarrama et al. 2018).


