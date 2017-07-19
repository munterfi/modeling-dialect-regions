# Modeling Dialect Regions in German-speaking Switzerland
Generating continuous spatial surfaces for the manifestations the 'infinitival complementizer' linguistic phenomena in the Swiss-German language (SADS phenomena I1, I6, I11 & IV14).

The aim of this project is to develop a new approach to model linguistic regions and their borders. In order to study the spatial distribution of linguistic phenomena, concepts from Geography and GIScience are applied on a linguistic data set, which was collected in the project 'Syntactic Atlas of German-speaking Switzerland' (SADS) during the years 2000 till 2002. Techniques from machine learning, like the Support Vector Machine (SVM) and a spatial regularization of the classification map (MRF) are combined with other well-known geographic concepts (Tobler’s first law, hiking function and least cost paths) to create linguistic regions, which take the inherent spatial dependencies between the data points into account. Also a gravity model based index finds application to weight the linguistic influence of two neighbors on each other.

The project is supervised by Curdin Derungs, head of the GISLab, a research group of the ‘Language and Space’ initiative at the University of Zurich.

## Installation

1. Install R & RStudio
2. Get the needed libraries: `install.packages('library-name')`
3. Clone the repository, by creating a new git project in RStudio

## Data

* DHM200 - Digital elevation model - [swisstopo](https://www.swisstopo.admin.ch/en/home.html)
* SADS - Syntactic Atlas of German-speaking Switzerland - [UFSP SpuR](http://www.spur.uzh.ch/en.html)
* STATPOP - Statistics of the Swiss population - [Federal Statistical Office](https://www.bfs.admin.ch/bfs/en/home.html)
* swissBOUNDARIES3D - Swiss national border - [swisstopo](https://www.swisstopo.admin.ch/en/home.html)

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Authors

* **Merlin Unterfinger** - *Development and implementation* - [munterfinger](https://github.com/munterfinger)
* **Curdin Derungs** - *Theoretical background* - [GISLab](http://www.spur.uzh.ch/de/departments/gislab/personen/curdinderungs.html)

## Built With

* [R](https://www.r-project.org) -  The R Project for Statistical Computing
* [RStudio](https://www.rstudio.com) - Open source and enterprise-ready professional software for R

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## References
Besag, J. (1986). On the Statistical Analysis of Dirty Pictures. Journal of the Royal Statistical Society, 48(3):259–302.

Beygelzimer, A., Kakadet, S., Langford, J., Arya, S., Mount, D., and Li, S. (2013). FNN: Fast Nearest Neighbor Search Algorithms and Applications.

Bivand, R., Keitt, T., and Rowlingson, B. (2016). rgdal: Bindings for the Geospatial Data Abstraction Library.

Bivand, R. and Rundel, C. (2016). rgeos: Interface to Geometry Engine - Open Source (GEOS).

Bivand, R. S., Pebesma, E., and Gomez-Rubio, V. (2013). Applied spatial data analysis with {R}, Second edition. Springer, NY.

Bucheli, C. and Glaser, E. (2002). The Syntactic Atlas of Swiss German Dialects: Empirical and Methodological Problems. In Barbiers, S., Cornips, L., and van der Kleij, S., editors, Syntactic Microvariation, pages 41–73. Meertens Institute Electronic Publications in Linguistics, Amsterdam, 2 edition.

Geman, S. and Geman, D. (1984). Stochastic Relaxation, Gibbs Distributions, and the Bayesian Restoration of Images. IEEE Transactions on Pattern Analysis and Machine Intelligence, 6(6):721–741.

Jeszenszky, P. and Weibel, R. (2016). Modeling transitions between syntactic variants in the dialect continuum. In The 19th AGILE International Conference on Geographic Information Science, Helsinki (Finnland), 14 June 2016 - 17 June 2016, number June.

Karatzoglou, A., Meyer, D., and Hornik, K. (2006). Support Vector Algorithm in R. Journal of Statistical Software, 15(9):1–28.

Metropolis, N., Rosenbluth, A. W., Rosenbluth, M. N., Teller, A. H., and Teller, E. (1953). Equation of state calculations by fast computing machines. Journal Chemical Physics, 21(6):1087–1092.

Meyer, D., Dimitriadou, E., Hornik, K., Weingessel, A., and Leisch, F. (2015). e1071: Misc Functions of the Department of Statistics, Probability Theory Group (Formerly: E1071), TU Wien.

Pebesma, E. J. and Bivand, R. S. (2005). Classes and methods for spatial data in {R}. R News, 5(2):9–13.

Perpiñán, O. and Hijmans, R. (2016). rasterVis.

R Core Team (2016). foreign: Read Data Stored by Minitab, S, SAS, SPSS, Stata, Systat, Weka, dBase, ... R package version 0.8-67.

Tarabalka, Y., Fauvel, M., Chanussot, J., and Benediktsson, J. A. (2010). SVM and MRF-Based Method for Accurate Classification of Hyperspectral Images. IEEE Geoscience and Remote Sensing Letters, 7(4):736–740.

Tobler, W. (1993). Non-Isotropic Geographic Modeling. NCGIA Technical Reports, 93(1):5.

Trudgill, P. (1974). Linguistic change and di usion: description and explanation in sociolinguistic dialect
geography. Language in Society, 2:215–246.

van Etten, J. (2017). {R} Package {gdistance}: Distances and Routes on Geographical Grids. Journal of
Statistical Software, 76(13):1–21.

Wickham, H. (2009). ggplot2: Elegant Graphics for Data Analysis. Springer-Verlag New York.
