# XTB
Popular semiempirical extended tight-binding program package

Description & Use:
XTB is a favourite general-purpose tight-binding code used for electronic structure investigations. Our application contains the XTB program along with the XTB4STDA, STDA executables for the electronic spectra modelling, and with QCxMS, PlotMS programs for calculating the custom MS spectra (slow). Together with OPSIN, OpenBABEL and X11-Basic interpreter the app enables performing of a desired calculation protocol starting from either the English IUPAC name, or SMILES string, or XYZ input structure, up to custom graphical output (e.g. spectra visualization). All the programs features are available offline. 

License: GNU Lesser General Public License v3.0
App source code: https://github.com/alanliska/XTB

Contact:
Compilation of the source code for Android as well as the Android app development was done by Alan Liška (alan.liska@jh-inst.cas.cz) and Veronika Růžičková (sucha.ver@gmail.com), J. Heyrovský Institute of Physical Chemistry of the CAS, v.v.i., Dolejškova 3/2155, 182 23 Praha 8, Czech Republic.
Website: http://www.jh-inst.cas.cz/~liska/MobileChemistry.htm

A brief list of used third-party software:
ACPDFVIEW (Bhuvaneshw), ANDROID SHELL (Jorrit "Chainfire" Jongma, JRummy Apps Inc.), BLAS, DFTD4 (Eike Caldeweyher, Christoph Bannwarth, Stefan Grimme, Sebastian Ehlert, Andreas Hansen, Hagen Neugebauer, Sebastian Spicher, Jan-Michael Mewes), DOCS (XTB, taken from: https://xtb-docs.readthedocs.io/en/latest/contents.html), GBSA parameters (please see XTB for authors), GRAPHVIEW (Jonas Gehring), LAPACK, MCTC-LIB (Sebastian Ehlert, Eisuke Kawashima, Marcel Stahn, Kjell Jorner and others - please see the source code page), MSTORE (Sebastian Ehlert, Kjell Jorner, Eisuke Kawashima), MULTICHARGE (Sebastian Ehlert, Eisuke Kawashima, Daniel Mejia-Rodriguez, Kjell Jorner), OPENBABEL (N M O'Boyle, M Banck, C A James, C Morley, T Vandermeersch, G R Hutchison and others), OPSIN (Rich Apodaca, Albina Asadulina, Peter Corbett, Daniel Lowe - current maintainer, John Mayfield, Peter Murray-Rust, Noel O'Boyle, Mark Williamson), PLOTMS (Jeroen Koopman, Johannes Gorges, Sebastian Ehlert and others - please see the source code page), QCXMS (Jeroen Koopman, Sebastian Ehlert, Johannes Gorges), S-DFTD3 (Sebastian Ehlert, Robert Cohn, Eisuke Kawashima, Shirong Wang, Kjell Jorner and others - please see the source code page), STDA (Marc de Wergifosse, Shoubhik Maiti, Pierre Beaujean, Sebastian Ehlert and others - please see the source code page), TBLITE (Sebastian Ehlert, Daniel Mejia-Rodriguez, Marvin Friede, Zeyuan Tang, Hagen Neugebauer, Konstantin Karandashev and others - please see the source code page), TEST-DRIVE (Sebastian Ehlert, Jeremie Vandenplas, Christopher Howard), TOML-F (Sebastian Ehlert, Robert Cohn, Bálint Aradi, Asdrubal Lozada-Blanco, Rohit Goswami, Ben Hourahine, Emily Kahl, Daniel Mejia-Rodriguez, Kjell Jorner), X11-BASIC (Markus Hoffmann), XTB (C. Bannwarth, E. Caldeweyher, S. Ehlert, A. Hansen, P. Pracht, J. Seibert, S. Spicher, S. Grimme, P. Shushkov, M. Stahn, H. Neugebauer, J.-M. Mewes, V. Asgeirsson, C. Bauer, J. Koopman), XTB4STDA (Sebastian Ehlert, Pierre Beaujean, Shoubhik Maiti, Jonathon Vandezande). 

IMPORTANT !!!
Although this app is composed of open-source codes and resources, licenses for some components require the users to cite the original references when publishing the results. Please check all the licensing information under the buttons 'License' and 'About the app'.
All the users of the XTB app comply by downloading, installing and using it with all the licensing conditions of the individual software components and take the responsibility for keeping them. 

More info on licenses & references - please refer to the licensing information inside of the app.

==================================================================================================

Licenses and references to used third-party software:

 * ACPDFVIEW
 Author: Bhuvaneshwaran (Github)
 Source code: https://github.com/Bhuvaneshw/acpdfview
 License: GNU GPL-3.0

 * ANDROID SHELL
 Author: Jorrit "Chainfire" Jongma (JRummy Apps Inc.)
 Source code: https://github.com/aa668086/android-shell-master
 License: Apache License, Version 2.0

 * BLAS
 Source code: https://netlib.org/blas/
 License: freely-available software package

 * DFTD4
 Authors: Eike Caldeweyher, Christoph Bannwarth, Stefan Grimme, Sebastian Ehlert, Andreas Hansen, Hagen Neugebauer, Sebastian Spicher, Jan-Michael Mewes
 Ref.: Eike Caldeweyher, Christoph Bannwarth and Stefan Grimme, J. Chem. Phys., 2017, 147, 034112. DOI: 10.1063/1.4993215
       Eike Caldeweyher, Sebastian Ehlert, Andreas Hansen, Hagen Neugebauer, Sebastian Spicher, Christoph Bannwarth and Stefan Grimme, J. Chem Phys, 2019, 150, 154122. DOI: 10.1063/1.5090222 chemrxiv: 10.26434/chemrxiv.7430216
       Eike Caldeweyher, Jan-Michael Mewes, Sebastian Ehlert and Stefan Grimme, Phys. Chem. Chem. Phys., 2020, 22, 8499-8512. DOI: 10.1039/D0CP00502A chemrxiv: 10.26434/chemrxiv.10299428
 Source code: https://github.com/dftd4/dftd4
 License: GNU GPL v3 and GNU LGPL v3

 * DOCS (XTB)
 Taken from: https://xtb-docs.readthedocs.io/en/latest/contents.html
 License: This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0). To view a copy of this license, visit creative commons or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

 * GBSA parameters
 Authors/contributors: please see XTB for authors and references
 Source code: https://github.com/grimme-lab/gbsa-parameters
 License: Attribution-ShareAlike 4.0 International

 * GRAPHVIEW
 Author: Jonas Gehring
 Source code: https://github.com/jjoe64
 License: Apache License, Version 2.0

 * LAPACK
 Source code: https://netlib.org/lapack/
 License: freely-available software package, modified BSD license

 * MCTC-LIB
 Authors/contributors: Sebastian Ehlert, Eisuke Kawashima, Marcel Stahn, Kjell Jorner and others (please see the source code page)
 Source code: https://github.com/grimme-lab/mctc-lib
 License: Apache v2

 * MSTORE
 Authors/contributors: Sebastian Ehlert, Kjell Jorner, Eisuke Kawashima
 Source code: https://github.com/grimme-lab/mstore
 License: Apache v2

 * MULTICHARGE
 Authors/contributors: Sebastian Ehlert, Eisuke Kawashima, Daniel Mejia-Rodriguez, Kjell Jorner
 Source code: https://github.com/grimme-lab/multicharge
 License: Apache v2

 * OPENBABEL
 Ref.: N M O'Boyle, M Banck, C A James, C Morley, T Vandermeersch, and G R Hutchison. "Open Babel: An open chemical toolbox." J. Cheminf. (2011), 3, 33. DOI:10.1186/1758-2946-3-33
       The Open Babel Package, version 2.3.1 http://openbabel.org (accessed Oct 2011)
 Source code: http://openbabel.org/wiki/Main_Page, https://github.com/openbabel/openbabel, https://sourceforge.net/projects/openbabel/

 * OPSIN
 Authors/developers: Rich Apodaca, Albina Asadulina, Peter Corbett, Daniel Lowe (Current maintainer), John Mayfield, Peter Murray-Rust, Noel O'Boyle, Mark Williamson
 Ref.: Lowe, Daniel M., Peter T. Corbett, Peter Murray-Rust, and Robert C. Glen. "Chemical name to structure: OPSIN, an open source solution." (2011): 739-753.
 Source code: https://github.com/dan2097/opsin
 License: MIT License

 * PLOTMS
 Authors/contributors: Jeroen Koopman, Johannes Gorges, Sebastian Ehlert and others (please see the source code page)
 Source code: https://github.com/qcxms/PlotMS
 License: GNU GPL v3 and GNU LGPL v3

 * PYTHON
 Source code: https://www.python.org/downloads/source/
 License: PSF license agreement, check the homepage https://docs.python.org/3.7/license.html for details

 * QCXMS
 Authors/contributors: Jeroen Koopman, Sebastian Ehlert, Johannes Gorges
 Source code: https://github.com/qcxms/QCxMS
 License: GNU GPL v3 and GNU LGPL v3

 * S-DFTD3
 Authors/contributors: Sebastian Ehlert, Robert Cohn, Eisuke Kawashima, Shirong Wang, Kjell Jorner and others (please see the source code page)
 Ref.: S. Grimme, J. Antony, S. Ehrlich and H. Krieg J. Chem. Phys, 132 (2010), 154104.
       S. Grimme, S. Ehrlich and L. Goerigk J. Comput. Chem, 32 (2011), 1456-1465.
 Source code: https://github.com/dftd3/simple-dftd3
 License: GNU GPL v3 and GNU LGPL v3

 * STDA
 Authors/contributors: Marc de Wergifosse, Shoubhik Maiti, Pierre Beaujean, Sebastian Ehlert and others (please see the source code page)
 Ref: S. Grimme, A simplified Tamm–Dancoff density functional approach for the electronic excitation spectra of very large molecules, J. Chem. Phys., 2013, 138, 244104. DOI: 10.1063/1.4811331
      C. Bannwarth, S. Grimme, A simplified time-dependent density functional theory approach for electronic ultraviolet and circular dichroism spectra of very large molecules, Comput. Theor. Chem., 2014, 1040 – 1041, 45 – 53. DOI: 10.1016/j.comptc.2014.02.023
      S. Grimme and C. Bannwarth, Ultra-fast computation of electronic spectra for large systems by tight-binding based simplified Tamm-Dancoff approximation (sTDA-xTB) J. Chem. Phys., 2016, 145, 054103. DOI: 10.1063/1.4959605
      M. de Wergifosse, C. Bannwarth, S. Grimme, A simplified spin-flip time-dependent density functional theory (SF-sTD-DFT) approach for the electronic excitation spectra of very large diradicals, J. Phys. Chem. A, 2019, 123 (27), 815–5825. DOI: 10.1021/acs.jpca.9b03176
      M. de Wergifosse, S. Grimme, Nonlinear-response properties in a simplified time-dependent density functional theory (sTD-DFT) framework: Evaluation of the first hyperpolarizability, J. Chem. Phys., 2018, 149 (2), 024108. DOI: 10.1063/1.5037665
      M. de Wergifosse, S. Grimme, Nonlinear-response properties in a simplified time-dependent density functional theory (sTD-DFT) framework: Evaluation of excited-state absorption spectra, J. Chem. Phys., 2019, 150, 094112. DOI: 10.1063/1.5080199
      M. de Wergifosse, J. Seibert, S. Grimme, Simplified time-dependent density functional theory (sTD-DFT) for molecular optical rotation, J. Chem. Phys., 2020, 153, 084116. DOI: 10.1063/5.0020543
      M. de Wergifosse, S. Grimme, A unified strategy for the chemically intuitive interpretation of molecular optical response properties, J. Chem. Theory Comput., 2020, 16 (12), 7709–7720. DOI: 10.1021/acs.jctc.0c00990
      M. de Wergifosse, P. Beaujean, S. Grimme, Ultrafast evaluation of two-photon absorption with simplified time-dependent density functional theory, J. Phys. Chem. A, 2022, XX, XXXX. DOI: 10.1021/acs.jpca.2c02395
 Source code: https://github.com/grimme-lab/stda
 License: GNU GPL v3 and GNU LGPL v3

 * TBLITE
 Authors/contributors: Sebastian Ehlert, Daniel Mejia-Rodriguez, Marvin Friede, Zeyuan Tang, Hagen Neugebauer, Konstantin Karandashev and others (please see the source code page)
 Source code: https://github.com/tblite/tblite
 License: GNU GPL v3 and GNU LGPL v3

 * TEST-DRIVE
 Authors/contributors: Sebastian Ehlert, Jeremie Vandenplas, Christopher Howard
 Source code: https://github.com/fortran-lang/test-drive
 License: Apache v2, MIT

 * TOML-F
 Authors/contributors: Sebastian Ehlert, Robert Cohn, Bálint Aradi, Asdrubal Lozada-Blanco, Rohit Goswami, Ben Hourahine, Emily Kahl, Daniel Mejia-Rodriguez, Kjell Jorner
 Source code: https://github.com/toml-f/toml-f
 License: Apache v2, MIT

 * X11-BASIC
 Author: Markus Hoffmann
 Source code: https://github.com/kollokollo/X11Basic
 License: GPL-2.0

 * XTB
 Authors: C. Bannwarth, E. Caldeweyher, S. Ehlert, A. Hansen, P. Pracht, J. Seibert, S. Spicher, S. Grimme, P. Shushkov, M. Stahn, H. Neugebauer, J.-M. Mewes, V. Asgeirsson, C. Bauer, J. Koopman
 Ref.: 
   -General Reference to xtb and the implemented GFN methods:
    C. Bannwarth, E. Caldeweyher, S. Ehlert, A. Hansen, P. Pracht, J. Seibert, S. Spicher, S. Grimme WIREs Comput. Mol. Sci., 2020, 11, e01493. DOI: 10.1002/wcms.1493
   -for GFN-xTB:
    S. Grimme, C. Bannwarth, P. Shushkov, J. Chem. Theory Comput., 2017, 13, 1989-2009. DOI: 10.1021/acs.jctc.7b00118
    C. Bannwarth, S. Ehlert and S. Grimme., J. Chem. Theory Comput., 2019, 15, 1652-1671. DOI: 10.1021/acs.jctc.8b01176
    P. Pracht, E. Caldeweyher, S. Ehlert, S. Grimme, ChemRxiv, 2019, preprint. DOI: 10.26434/chemrxiv.8326202.v1
   -for GFN-FF:
    S. Spicher and S. Grimme, Angew. Chem. Int. Ed., 2020, 59, 15665–15673 DOI: 10.1002/anie.202004239
   -for GBSA and ALPB implicit solvation:
    S. Ehlert, M. Stahn, S. Spicher, S. Grimme, J. Chem. Theory Comput., 2021, 17, 4250-4261 DOI: 10.1021/acs.jctc.1c00471
   -for DFT-D4:
    E. Caldeweyher, C. Bannwarth and S. Grimme, J. Chem. Phys., 2017, 147, 034112. DOI: 10.1063/1.4993215
    E. Caldeweyher, S. Ehlert, A. Hansen, H. Neugebauer, S. Spicher, C. Bannwarth and S. Grimme, J. Chem. Phys., 2019, 150, 154122. DOI: 10.1063/1.5090222
    E. Caldeweyher, J.-M. Mewes, S. Ehlert and S. Grimme, Phys. Chem. Chem. Phys., 2020, 22, 8499-8512. DOI: 10.1039/D0CP00502A
   -for sTDA-xTB:
    S. Grimme and C. Bannwarth, J. Chem. Phys., 2016, 145, 054103. DOI: 10.1063/1.4959605
   -in the mass-spec context:
    V. Asgeirsson, C. Bauer and S. Grimme, Chem. Sci., 2017, 8, 4879. DOI: 10.1039/c7sc00601b
    J. Koopman and S. Grimme, ACS Omega, 2019, 4, 12, 15120-15133. DOI: 10.1021/acsomega.9b02011
    J. Koopman and S. Grimme, J. Am. Soc. Mass Spectrom., 2021, 32, 7, 1735-1751. DOI: 10.1021/jasms.1c00098
   -for metadynamics refer to:
    S. Grimme, J. Chem. Theory Comput., 2019, 155, 2847-2862. DOI: 10.1021/acs.jctc.9b00143
   -for SPH calculations refer to:
    S. Spicher and S. Grimme, J. Chem. Theory Comput., 2021, 17, 1701–1714. DOI: 10.1021/acs.jctc.0c01306
 Source code: https://github.com/grimme-lab/xtb
 License: GNU GPL v3 and GNU LGPL v3

 * XTB4STDA
 Authors/contributors: Sebastian Ehlert, Pierre Beaujean, Shoubhik Maiti, Jonathon Vandezande
 Ref.: S. Grimme and C. Bannwarth, J. Chem. Phys., 2016, 145, 054103. DOI: 10.1063/1.4959605
 Source code: https://github.com/grimme-lab/xtb4stda
 License: GNU GPL v3 and GNU LGPL v3

Other references:

 * UV-Vis spectra convolution: Tirri, Bernardino. Détermination d’un protocole de calcul pour la prédiction de spectres UV-vis de molécules en solution. Diss. Université Paris sciences et lettres, 2022.


Info on licenses: please see the full-text licenses under the button Licenses. 