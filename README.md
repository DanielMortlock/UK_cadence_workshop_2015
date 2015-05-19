# LSST:UK Survey Strategy Workshop

Kavli Institute for Cosmology, Institute of Astronomy, University of Cambridge, May 18-20, 2015

This is the repository for the notebooks generated at the workshop, and the slides from the talks and tutorials.

## Talks

* [Introduction to the LSST System and Survey](https://github.com/LSST-nonproject/UK_cadence_workshop_2015/blob/master/presentations/Cambridge_intro_LSST.pdf) - Andy Connolly
* [Strong Lens Time Delay Metric Example](https://github.com/LSST-nonproject/UK_cadence_workshop_2015/blob/master/presentations/Time_Delay_Example.pdf) - Phil Marshall

## Notebooks

At the workshop, the working groups produced the following notebooks:

* [Persistent Variables: notes, plans and simple extensions of the Variability notebook]()
*  ...
*  ...

All the LSST sims team's example notebooks are [available on GitHub](https://github.com/lsst-sims/sims_maf_notebooks). They call the metric code defined in the `sims_maf_contrib` and `lsst/sims/maf` modules.

    git clone https://github.com/lsst-sims/sims_maf_notebooks
    git clone https://github.com/LSST-nonproject/sims_maf_contrib.git

Don't forget to:

    loadLSST.csh
    setup sims_maf -t sims
    setup sims_maf_contrib
in the right places.



## Other Useful Links

* [OpSim output database fields](https://confluence.lsstcorp.org/display/SIM/Summary+Table+Column+Descriptions). These are the ones accessible from MAF - the complete list can be viewed [here](http://opsimcvs.tuc.noao.edu/docs/simulator/architecture.html#output-tables-in-opsim) (its the `ObsHistory` table that contains the most relevant fields for metric analysis). 
