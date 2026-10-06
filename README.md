# State-of-the-UNIONS-Candidates
Storage location for data products relating to the paper "State of the UNIONS: Four Milky Way companions discovered in a systematic search for northern Local Group satellites", S.E.T. Smith et al. 2026

Four newly discovered satellites are presented here: UNIONS 2, UNIONS 3, Boötes VI, & Draco III.  
In the candidate lists where they are found, their names are demarcated with two asterisks (e.g. UNIONS 2**).

**link to arxiv/ads, when available**

## candidate-lists

A matched-filter search was applied to the *gri* broadband photometry from the UNIONS survey. For each pair of filters, both the north galactic cap (NGC, 4600 deg<sup>2</sup>) and south galactic cap (SGC, 300 deg<sup>2</sup>) contiguous regions were searched independently. For each search, the top 100 most prominent statistical overdensities were recorded (once duplicates had been filtered out) and saved as lists, which can be found in this repository under the candidate-lists directory.  

The naming convention is *filterpair*_*region*.csv  
Thus, for the $gr$ search in the NGC region, we have: gr_ngc.csv  

## mcmc-chains

An MCMC-based fitting routine (based on Martin et al. 2008, 2016) was used to obtain structural parameters for the stellar distribution of each system using an elliptical exponential model. The full chains resulting from the fitting routine can be found in the mcmc-chains directory for full reproducibiliy.
