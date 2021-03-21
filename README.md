# OrbitDeterminationScripts

extractAngularMeasurements.py is used for extracting angular position measurements from differenc image data.
create_config_file is used for creating yaml file that contains all the intial guess for orbit determination
OrblestSqFit_FinalVersion does orbit determination in two steps and also calculates unceratinities by boostraping.


Example execution of scripts (note:- there are some hardcoded bugs, but works fine for current data set)
TODO:- remove hardcoded behaviour
python  /astro/mwasci/sprabu/path/PawseyPathFiles/orbInfo_mc.py --obs 1165762576 --noradid 20580 --beam ../../beam5amin.fits --user ${spaceTrackUser} --passwd ${spaceTrackPassword} --filePrefix 6Sigma1Floodfilllr14SigmaRFIBinaryMapPeakFlux --niter 1 --debug True
