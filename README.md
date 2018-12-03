# SAE

## Description

    To perform data related functins such as to import the target dataset to a more manageable
    format for the simulations; to export the resulting simulations to a dataset of the user’s
    preference; and to compare the variables between the sources of data.

      ----------------------------------------------------------------------
      sae data import        import sae data into Mata data file
      sae data export        export sae Mata data file to Stata data
      ----------------------------------------------------------------------

    To perform first stage estimation on sae data. This routine is for obtaining the GLS estimates
    of the first stage. The sub-routines, sae model lmm (linear mixed model) and sae model povmap
    (povmap) are used interchangeably

      ----------------------------------------------------------------------
      sae model lmm          model first stage estimations for the linear mixed models
      ----------------------------------------------------------------------

    To perform second stage estimation on sae data. This routine and sub-routine obtains the GLS
    estimates of the first stage, and goes on to perform the Monte Carlo simulations

      ----------------------------------------------------------------------
      sae sim lmm            simulate based on first stage models for the linear mixed models
      ----------------------------------------------------------------------

    The stats and inds sub-routines are useful for processing Mata formatted simulation output and
    producing indicators with new thresholds or weights, as well as profiling.

      ----------------------------------------------------------------------
      sae proc stats         produce the statistics based on simulated data
      sae proc ind           prodiuce Poverty and Inequality indictors based on simulated data
      ----------------------------------------------------------------------


## References

    Bedi, T., A. Coudouel, and K. Simler (2007). More than a pretty picture: using poverty maps to
    design better policies and interventions. World Bank Publications.

    Demombynes, G., C. Elbers, J. O. Lanjouw, and P. Lanjouw (2008). How good is a map? putting
    small area estimation to the test. Rivista Internazionale di Scienze Sociali, 465–494.

    Elbers, C., J. O. Lanjouw, and P. Lanjouw (2002). Micro-level estimation of welfare. 2911.

    Elbers, C., J. O. Lanjouw, and P. Lanjouw (2003). Micro–level estimation of poverty and
    inequality. Econometrica 71 (1), 355–364.

    Foster, J., J. Greer, and E. Thorbecke (1984). A class of decomposable poverty measures.
    Econometrica:  Journal of the Econometric Society, 761–766.

    Harvey, A. C. (1976). Estimating regression models with multiplicative heteroscedasticity.
    Econometrica:  Journal of the Econometric Society, 461–465.

    Haslett, S., M. Isidro, and G. Jones (2010). Comparison of survey regression techniques in the
    context of small area estimation of poverty. Survey Methodology 36 (2), 157–170.

    Henderson, C. R. (1953). Estimation of variance and covariance components. Biometrics 9 (2),
    226–252.

    Huang, R. and M. Hidiroglou (2003). Design consistent estimators for a mixed linear model on
    survey data.

    Proceedings of the Survey Research Methods Section, American Statistical Association (2003),
    1897–1904.

    Molina, I. and J. Rao (2010). Small area estimation of poverty indicators. Canadian Journal of
    Statistics 38 (3), 369–385.

    Rao, J. N. and I. Molina (2015). Small area estimation. John Wiley & Sons.

    Tarozzi, A. and A. Deaton (2009). Using census and survey data to estimate poverty and
    inequality for small areas. The review of economics and statistics 91 (4), 773–792.

    Van der Weide, R. (2014). GLS estimation and empirical bayes prediction for linear mixed
    models with heteroskedasticity and sampling weights: a background study for the povmap
    project. World Bank Policy Research Working Paper (7028).

    Zhao, Q. (2006). User manual for povmap. World Bank. [link](http://siteresources.worldbank.org/INTPGI/Resources/342674-1092157888460/Zhao_ManualPovMap.pdf)
