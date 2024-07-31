This is the code I wrote for my research on AGN feedback and it's role in dwarf galaxy evolution. I set out to elucidate disparities in out understanding of feedback's role in galactic evolution between dwarf galaxies and massive galaxies; the paper's abstarct can be found below.

**Abstract**

Black holes (BHs) are thought to reside at the center of every galaxy in the known universe. Often taking the form of active galactic nuclei (AGN), these cosmic bodies regulate various interactions with their host galaxies, which in turn influence the AGN. This forms a coevolutionary relationship between AGNs and their host. Current models such as ΛCDM accurately describe this relationship in massive galaxies (M* > 5 × 10^9 M⊙), however a lack of comprehension of the driving mechanisms behind AGN feedback in dwarf galaxies (M* < 5 × 10^9 M⊙) has limited previous research in further exploring these coevolutionary trends. Using populations of massive and dwarf galaxies, both with subgroups of AGN and star forming (SF) dominated feedback, this research explored various galactic properties from both mass ranges to corroborate theory with observation in the realms of gas velocity dispersion, galactic mass, total bolometric luminosity, ionized gas fraction, and stellar quenching. In dwarf galaxies, results indicate that galactic mass has a significant effect on velocity dispersion in the Hα broadband for both AGN and SF-dominated feedback (r = -0.613, r = -0.586; p < 0.001). Galactic mass was shown to have little effect on Hα velocity dispersion in both AGN and SF populations (r = -0.142, r = -0.97; p < 0.001), suggesting that energy injected into massive galaxies by central AGN is consistent through most populations. Given these results, we can reasonably conclude that massive and dwarf galaxies follow different mechanisms of feedback driving, and thus evolution. Advancing our understanding of the AGN-galaxy relationship is pivotal in producing accurate understandings of galactic evolution in all cohorts.

The files contained within were used to extract date from the MaNGA survey of SDSS DR17, create plots to visiualize my results, and to conduct statistical tests. 

**In order for the code to operate as intended, it must be run in a Jupyter Notebook, within a container from SciServer running the "SciServer Essentials 2.0" image**

For each Jupyter Notebook file (.ipynb), there is an accopanying Python file (.py). When uploading the files to Jupyter Notebook, .ipynb files are strongly recommended however the Python files exist for anyone seeking that option.

When running the 'Sample Selection' code, the dwarf and massive galaxy files will generate .xlsx (Excel) files containing the MaNGA IDs for the AGN and SF dominated feedback galaxies in each mass group. If you do not want to run these code files, you can download the .xlsx files containing each cohort's MaNGA IDs in the folder titled 'MaNGA IDs'.                                                                                         

**IMPORTANT:** These .xlsx files are used in the other code files to determine which galaxies from the raw data are in the study's sample. The .xlsx files MUST be uploaded to the same directory as the code wishing to use them.

For inquiries, I am availible at mgiambona86@gmail.com.
