# Young SNe Ib
Data products of LCO spectral data of young Type Ib from Yesmin et al. 2024
This release contains new SuperNova IDentification (SNID; Blondin & Tonry 2007) spectral templates of SNe Ib presented in Yesmin et al. 2024, that are mainly based on Las Cumbres Observatory (LCO) data. SN 2019odp and SN 2016bau have additional data that were presented in Schweyer et al. 2023 and Aryan et al. 2021. 

Adding these templates to the default library of SESN spectra of SNID (https://people.lam.fr/blondin.stephane/software/snid/) and the extended SESNe Modjaz Group Sample (MGS; Modjaz et al. 2014; Liu et al. 2016, 2017; Williamson et al. 2019) will increase the number of SNID templates of premaximum spectra of SNe Ib by ∼43%. Templates in the database will help SN classification via SNID. These templates are compliant with SNID version SNID-5.0.

The text file SNIDtemplate-youngIb-info.txt includes detailed information about the SNe in the sample and their spectra that were used to construct the templates. Its columns list for each SN:
template name
IAU name
the redshift (which was used to de-redshift the spectra)
the date of maxium light, according to which the spectra are referenced for their phase 
filter in which the date of max is reported in
method with which the date of maximum was determined

The subdirectory called "templates_yesmin" includes the .lnw files for the SNID templates.

For comparison: there were 235 spectra (with 91 premaximum spectra) of 22 SNe Ib in Blondin's release (templates-2.0) + MGS. In this release, there are at total 91 photospheric spectral templates of 8 SNe Ib with 39 premaximum spectra. Thus, this data set significantly enhances the number of premaximum spectral templates of SNe Ib. 
