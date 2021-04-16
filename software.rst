.. _lab-software:

Software
========

Research work in BioSFGroup relies on computer software, with strong preference towards the usage of `free and open source software <https://opensource.com/article/17/11/open-source-or-free-software>`__, starting from the operating system:

- our laptops and workstations run `Ubuntu LTS <https://ubuntu.com/download/desktop>`__,
- our servers run `Debian GNU/Linux <https://www.debian.org/distrib/>`__ or `FreeBSD <https://www.freebsd.org/>`__, and
- our supercomputer `Bura <https://cnrm.uniri.hr/bura/>`__ runs `Red Hat Enterprise Linux <https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux>`__.

The reasons for the preference towards the usage of free and open source software are the limited use conditions, limited extensibility, and license cost of proprietary software, which limit the science that we can do. The developments that we do can be found on `our GitHub organization <https://github.com/svedruziclab>`__.

The list below is limited to the software we use; for a more comprehensive list of available free and open source software for molecular modelling, see:

- `Pirhadi, S. <https://sums.ac.ir/page-EnmncrcMegaMenu/en/298/form/pId47531>`__, `Sunseri, J. <https://pitt.edu/~jss97/>`__, and `Koes, D. R. <https://bits.csb.pitt.edu/>`__ `Open source molecular modeling. <https://doi.org/10.1016/j.jmgm.2016.07.008>`__ Journal of Molecular Graphics and Modelling 69, 127–143 (2016). or the `Open Source Molecular Modeling <https://opensourcemolecularmodeling.github.io/>`__ updateable list of software
- `ABC of cheminformatics <https://github.com/filipsPL/ABChemoinformatics>`__ by `Filip Stefaniak <https://filipspl.github.io/>`__
- `Directory of computer-aided Drug Design tools <https://www.click2drug.org/>`__ by `Swiss Institute of Bioinformatics <https://www.sib.swiss/>`__

.. contents:: List of software by type
   :depth: 2
   :local:



Structure visualization, analysis, and editing
----------------------------------------------

.. contents:: List of software
   :depth: 1
   :local:


.. _software-pymol:

PyMOL
^^^^^

**PyMOL** (`homepage <https://pymol.org/>`__, `Wikipedia <https://en.wikipedia.org/wiki/PyMOL>`__) is free and open source molecular visualization system, maintained by `Schrödinger <https://www.schrodinger.com/>`__.

PyMOL is available as a package in `Arch Linux <https://www.archlinux.org/packages/community/x86_64/pymol/>`__, `Debian <https://tracker.debian.org/pkg/pymol>`__, and `Fedora <https://apps.fedoraproject.org/packages/pymol>`__.

Specific uses
"""""""""""""

- `Visual approach to construction of &QMMM section of CP2K input file <https://github.com/pmamonov/pymol-cp2k-qmmm>`__


.. _software-vmd:

VMD
^^^

**VMD** (`homepage <https://www.ks.uiuc.edu/Research/vmd/>`__, `Wikipedia <https://en.wikipedia.org/wiki/Visual_Molecular_Dynamics>`__) is a freely available molecular visualization system used for displaying and animation of biomolecular systems. VMD stands for *Visual Molecular Dynamics*, and it is maintained by `Theoretical and Computational Biophysics Group <https://www.ks.uiuc.edu/>`__ at `University of Illinois at Urbana-Champaign <https://illinois.edu/>`__. VMD is distributed with source code under `VMD License <https://www.ks.uiuc.edu/Research/vmd/current/LICENSE.html>`__, and it is not free and open source software.

VMD is available as a package in `Arch User Repository <https://aur.archlinux.org/packages/vmd/>`__, but not in Debian and Fedora.

Specific uses
"""""""""""""

- `VMD psfgen Plugin <https://www.ks.uiuc.edu/Research/vmd/plugins/psfgen/>`__
- `DynamicBonds <https://www.ks.uiuc.edu/Research/vmd/current/ug/node58.html>`__


.. _software-chimera:

UCSF Chimera
^^^^^^^^^^^^

**UCSF Chimera** (`homepage <https://www.cgl.ucsf.edu/chimera/>`__, `Wikipedia <https://en.wikipedia.org/wiki/UCSF_Chimera>`__) is a freely available visualization and analysis software. Chimera works with single molecules as well as supramolecular assemblies, sequence alignments, results of docking, and molecular dynamics trajectories. Chimera is distributed in a binary form under `UCSF Chimera Non-Commercial Software License Agreement <https://www.cgl.ucsf.edu/chimera/license.html>`__, and it is not free and open source software.

UCSF Chimera is available as a package in `Arch User Repository <https://aur.archlinux.org/packages/ucsf-chimera/>`__, but not in Debian and Fedora.

Specific uses
"""""""""""""

- `Dock Prep <https://www.cgl.ucsf.edu/chimera/docs/ContributedSoftware/dockprep/dockprep.html>`__, `AutoDock Vina <https://www.cgl.ucsf.edu/chimera/docs/ContributedSoftware/vina/vina.html>`__, and `ViewDock <https://www.cgl.ucsf.edu/chimera/docs/ContributedSoftware/viewdock/viewdock.html>`__
- `Add Charge <https://www.cgl.ucsf.edu/chimera/docs/ContributedSoftware/addcharge/addcharge.html>`__
- `MD Movie <https://www.cgl.ucsf.edu/chimera/docs/ContributedSoftware/movie/movie.html>`__


.. _software-wxmacmolplt:

wxMacMolPlt
^^^^^^^^^^^

**wxMacMolPlt** (`homepage <https://brettbode.github.io/wxmacmolplt/>`__, `Wikipedia <https://en.wikipedia.org/wiki/WxMacMolPlt>`__) is a free and open source graphical user interface for preparation and visualization of the input and output files for the GAMESS quantum chemistry package.

wxMacMolPlt is available as a package in `Arch User Repository <https://aur.archlinux.org/packages/wxmacmolplt/>`__ and `Fedora <https://apps.fedoraproject.org/packages/wxmacmolplt>`__, but not in Debian.


.. _software-modeller:

MODELLER
^^^^^^^^

**MODELLER** (`homepage <https://salilab.org/modeller/>`__, `Wikipedia <https://en.wikipedia.org/wiki/MODELLER>`__) is a proprietary software for modelling of tertiary structures of proteins.

MODELLER is available as a package in `Arch User Repository <https://aur.archlinux.org/packages/modeller/>`__, but not in Debian and Fedora.


.. _software-avogadro:

Avogadro
^^^^^^^^

**Avogadro** (`homepage <https://avogadro.cc/>`__, `Wikipedia <https://en.wikipedia.org/wiki/Avogadro_%28software%29>`__) is a free and open source molecule editor. It is maintained by `Kitware <https://www.kitware.com/>`__. Avogadro comes in two versions: orange Avogadro, and blue `Avogadro 2 <https://www.openchemistry.org/projects/avogadro2/>`__.

Avogadro (first version, the orange one) is available as a package in `Arch User Repository <https://aur.archlinux.org/packages/avogadro/>`__, `Debian <https://tracker.debian.org/pkg/avogadro>`__, and `Fedora <https://apps.fedoraproject.org/packages/avogadro>`__. Avogadro 2 (the blue one) is available as a package in `Arch User Repository <https://aur.archlinux.org/packages/avogadro2-git/>`__ and `Fedora <https://apps.fedoraproject.org/packages/avogadro2>`__, but not in Debian.


.. _software-marvin:

ChemAxon Marvin
^^^^^^^^^^^^^^^

**ChemAxon Marvin** (`homepage <https://chemaxon.com/products/marvin>`__, `Wikipedia <https://en.wikipedia.org/wiki/ChemAxon>`__) is a freely available software for drawing and visualization of molecules. Marvin is distributed in binar form under `ChemAxon EULA <https://docs.chemaxon.com/display/docs/End+User+License+Agreement>`__, and it is not free and open source software.

Marvin is available as a package in `Arch User Repository <https://aur.archlinux.org/packages/marvin/>`__, but not in Debian and Fedora.


.. _software-cresset:

Cresset
^^^^^^^

**Torch** (`homepage <https://www.cresset-group.com/products/torch/>`__) is a proprietary software.

Torch is not available as a package in Arch Linux, Debian, and Fedora.

**Spark** (`homepage <https://www.cresset-group.com/products/spark/>`__) is a proprietary software.

Spark is not available as a package in Arch Linux, Debian, and Fedora.

**Forge** (`homepage <https://www.cresset-group.com/products/forge/>`__) is a proprietary software.

Forge is not available as a package in Arch Linux, Debian, and Fedora.



Electrostatic calculation, protein-ligand docking, and molecular simulation
---------------------------------------------------------------------------

.. contents:: List of software
   :depth: 1
   :local:


.. _software-apbs-pdb2pqr:

APBS and PDB2PQR
^^^^^^^^^^^^^^^^

**APBS** (`homepage <https://www.poissonboltzmann.org/>`__, `Wikipedia <https://en.wikipedia.org/wiki/APBS_%28software%29>`__) is a free and open source software for computing the numerical solution of the Poisson-Boltzmann equation that describes electrostatic interactions between molecular solutes.

APBS is available as a package in `Arch User Repository <https://aur.archlinux.org/packages/apbs/>`__, `Debian <https://tracker.debian.org/pkg/apbs>`__, and `Fedora <https://apps.fedoraproject.org/packages/apbs>`__.

**PDB2PQR** (`homepage <https://www.poissonboltzmann.org/>`__, `Wikipedia <https://en.wikipedia.org/wiki/PDB2PQR>`__) is a free and open source software for preparation of molecular structures for electrostatic calculation.

PDB2PQR is available in `Arch User Repository <https://aur.archlinux.org/packages/pdb2pqr/>`__ and `Debian <https://tracker.debian.org/pkg/pdb2pqr>`__, but not in Fedora.


.. _software-autodock-vina:

AutoDock and AutoDock Vina
^^^^^^^^^^^^^^^^^^^^^^^^^^

**AutoDock** (`homepage <https://autodock.scripps.edu/>`__, `Wikipedia <https://en.wikipedia.org/wiki/AutoDock>`__) and **AutoDock Vina** (`homepage <https://vina.scripps.edu/>`__, `Wikipedia <https://en.wikipedia.org/wiki/AutoDock_Vina>`__) are free and open source protein-ligand docking software packages.

AutoDock is available as a package in `Debian <https://tracker.debian.org/pkg/autodocksuite>`__ and `Fedora <https://apps.fedoraproject.org/packages/autodocksuite>`__, but not in Arch Linux. AudoDock Vina is available in `Arch User Repository <https://aur.archlinux.org/packages/autodock-vina/>`__ and `Debian <https://tracker.debian.org/pkg/autodock-vina>`__, but not in Fedora.


.. _software-rxdock:

rDock and RxDock
^^^^^^^^^^^^^^^^

**rDock** (`homepage <https://www.rdock.org/>`__, `Wikipedia <https://en.wikipedia.org/wiki/RDock>`__) and **RxDock** (`homepage <https://www.rxdock.org/>`__, `Wikipedia <https://en.wikipedia.org/wiki/RxDock>`__) are free and open source protein-ligand docking software packages designed for high throughput virtual screening.

rDock and RxDock are not available as packages in Arch Linux, Debian, and Fedora.


.. _software-gromacs:

GROMACS
^^^^^^^

**GROMACS** (`homepage <http://www.gromacs.org/>`__, `Wikipedia <https://en.wikipedia.org/wiki/GROMACS>`__) is a free and open source molecular dynamics package. It supports classical molecular mechanics and provides interface to a number of quantum mechanics software packages.

GROMACS is available as a package in `Arch User Repository <https://aur.archlinux.org/packages/gromacs/>`__, `Debian <https://tracker.debian.org/pkg/gromacs>`__, and `Fedora <https://apps.fedoraproject.org/packages/gromacs>`__.

Specific uses
"""""""""""""

- `Protein-Ligand Complex <http://www.mdtutorials.com/gmx/complex/>`__
- `Umbrella Sampling <http://www.mdtutorials.com/gmx/umbrella/>`__
- `Coarse Grained <http://cgmartini.nl/>`__ (proteins in lipid bilayers, protein-protein interactions, protein kinases)


.. _software-namd:

NAMD
^^^^

**NAMD** (`homepage <https://www.ks.uiuc.edu/Research/namd/>`__, `Wikipedia <https://en.wikipedia.org/wiki/NAMD>`__) is a freely available molecular dynamics package.

NAMD is available as a package in `Arch User Repository <https://aur.archlinux.org/packages/namd/>`__, but not in Debian and Fedora.


.. _software-plumed:

PLUMED
^^^^^^

**PLUMED** (`homepage <https://www.plumed.org/>`__, `Wikipedia <https://en.wikipedia.org/wiki/PLUMED>`__) is a a free and open source library for free energy calculations in molecular systems.

PLUMED is available as a package in `Arch User Repository <https://aur.archlinux.org/packages/plumed/>`__, but not in Debian and Fedora.


.. _software-cp2k:

CP2K
^^^^

**CP2K** (`homepage <https://www.cp2k.org/>`__, `Wikipedia <https://en.wikipedia.org/wiki/CP2K>`__) is a free and open source molecular dynamics package. It supports both quantum and classical molecular mechanics, and allows using both of them in the same simulation with QM/MM.

CP2K is available as a package in `Arch User Repository <https://aur.archlinux.org/packages/cp2k/>`__, `Debian <https://tracker.debian.org/pkg/cp2k>`__, and `Fedora <https://apps.fedoraproject.org/packages/cp2k>`__.

Specific uses
"""""""""""""

- `Nudged Elastic Band <https://www.cp2k.org/exercises:2015_ethz_mmm:nudged_elastic_band>`__
- `QM/MM <https://www.cp2k.org/exercises:2015_uzh_molsim:chp_cu111>`__


.. _software-nwchem:

NWChem
^^^^^^

**NWChem** (`homepage <https://nwchemgit.github.io/>`__, `Wikipedia <https://en.wikipedia.org/wiki/NWChem>`__) is a free and open source molecular dynamics package.

NWChem is available as a package in `Arch User Repository <https://aur.archlinux.org/packages/nwchem/>`__, `Debian <https://tracker.debian.org/pkg/nwchem>`__, and `Fedora <https://apps.fedoraproject.org/packages/nwchem>`__.


.. _software-gamess-us:

GAMESS (US)
^^^^^^^^^^^

**GAMESS (US)** (`homepage <https://www.msg.chem.iastate.edu/gamess/>`__, `Wikipedia <https://en.wikipedia.org/wiki/GAMESS_%28US%29>`__) is a freely available quantum chemistry software.

GAMESS (US) is  available as a package in `Arch User Repository <https://aur.archlinux.org/packages/gamess/>`__, but not in Debian and Fedora.



Topology generation and file format conversion
----------------------------------------------

.. contents:: List of software
   :depth: 1
   :local:


.. _software-ambertools-acpype:

AmberTools and acpype
^^^^^^^^^^^^^^^^^^^^^

**AmberTools**, a part of **Amber** molecular dynamics package (`homepage <https://ambermd.org/>`__, `Wikipedia <https://en.wikipedia.org/wiki/AMBER>`__), is a freely available set of tools for preparation and analysis of molecular dynamics simulations. Many of the tools are free and open source software.

AmberTools is available as a package in `Arch User Repository <https://aur.archlinux.org/packages/ambertools>`__, but not in Debian and Fedora (there is `an effort to package AmberTools for Fedora <https://fedoraproject.org/wiki/AmberTools>`__).

**ACPYPE** (`homepage <https://github.com/t-/acpype>`__, `Google Code archive <https://code.google.com/archive/p/acpype/>`__) is a free and open source software for generation of molecular topologies. It uses `Antechamber and GAFF <https://ambermd.org/antechamber/antechamber.html>`__ from AmberTools.

ACPYPE is not available as a package in Arch Linux, Debian, and Fedora.


.. _software-open-babel:

Open Babel
^^^^^^^^^^

**Open Babel** (`homepage <https://openbabel.org/>`__, `Wikipedia <https://en.wikipedia.org/wiki/Open_Babel>`__) is free and open source software for conversion between different chemical file formats. It provides both command line and graphical user interfaces.

Open Babel is available as a package in `Arch Linux <https://www.archlinux.org/packages/extra/x86_64/openbabel/>`__, `Debian <https://tracker.debian.org/pkg/openbabel>`__, and `Fedora <https://apps.fedoraproject.org/packages/openbabel>`__.



Chemical kinetics simulation and quantitative molecular interactions
--------------------------------------------------------------------

.. contents:: List of software
   :depth: 1
   :local:


.. _software-kintek:

KinTek Explorer
^^^^^^^^^^^^^^^

**KinTek Explorer** (`homepage <https://kintekcorp.com/overview/>`__) is a proprietary software for chemical kinetic data analysis.

KinTek Explorer is not available as a package Arch Linux, Debian, and Fedora.


.. _software-copasi:

COPASI
^^^^^^

**COPASI** (`homepage <http://copasi.org/>`__, `Wikipedia <https://en.wikipedia.org/wiki/COPASI>`__) is a free and open source software for simulation and analysis of biochemical networks and their dynamics.

COPASI is available as a package in `Arch User Repository <https://aur.archlinux.org/packages/copasi/>`__ and `Fedora <https://apps.fedoraproject.org/packages/COPASI>`__, but not in Debian.


.. _software-tenua:

Tenua
^^^^^

**Tenua** (`homepage <http://bililite.com/tenua/>`__, `Wikipedia <https://en.wikipedia.org/wiki/Tenua>`__) is a free and open source software for chemical kinetics simulation.

Tenua is not available as a package in Arch Linux, Debian, and Fedora.



Data processing and visualization
---------------------------------

.. contents:: List of software
   :depth: 1
   :local:


.. _software-r-bio3d:

R and Bio3D
^^^^^^^^^^^

**R** (`homepage <https://www.r-project.org/>`__, `Wikipedia <https://en.wikipedia.org/wiki/R_%28programming_language%29>`__) is a free and open source software environment and a programming language for statistical computing.

R is available as a package in, `Arch Linux <https://www.archlinux.org/packages/extra/x86_64/r/>`__, `Debian <https://tracker.debian.org/pkg/r-base>`__, and `Fedora <https://apps.fedoraproject.org/packages/R>`__.

**Bio3D** (`homepage <http://thegrantlab.org/bio3d/>`__) is an R package for analyzing the protein sequence, structure, and trajectory data.

Bio3D is available as a package in `Debian <https://tracker.debian.org/pkg/r-cran-bio3d>`__, but not in Arch Linux and Fedora.

.. _software-maxima:

Maxima
^^^^^^

**Maxima** (`homepage <https://maxima.sourceforge.io/>`__, `Wikipedia <https://en.wikipedia.org/wiki/Maxima_%28software%29>`__) is a free and open source computer algebra system.

Maxima is available as a package in `Arch Linux <https://www.archlinux.org/packages/extra/x86_64/maxima/>`__, `Debian <https://tracker.debian.org/pkg/maxima>`__, and `Fedora <https://apps.fedoraproject.org/packages/maxima>`__.


.. _software-libreoffice-calc:

LibreOffice Calc
^^^^^^^^^^^^^^^^

**LibreOffice** (`homepage <https://www.libreoffice.org/>`__, `Wikipedia <https://en.wikipedia.org/wiki/LibreOffice>`__) is a free and open source office suite. The spreadsheet component is called `Calc <https://www.libreoffice.org/discover/calc/>`__.

LibreOffice is available as a package in `Arch Linux <https://www.archlinux.org/packages/extra/x86_64/libreoffice-fresh/>`__ (`still branch <https://www.archlinux.org/packages/extra/x86_64/libreoffice-still/>`__), `Debian <https://tracker.debian.org/pkg/libreoffice>`__, and `Fedora <https://apps.fedoraproject.org/packages/libreoffice>`__.


.. _software-gnuplot:

gnuplot
^^^^^^^

**gnuplot** (`homepage <http://www.gnuplot.info/>`__, `Wikipedia <https://en.wikipedia.org/wiki/Gnuplot>`__) is a free and open source graphing software.

Gnuplot is available as a package in, `Arch Linux <https://www.archlinux.org/packages/extra/x86_64/gnuplot/>`__, `Debian <https://tracker.debian.org/pkg/gnuplot>`__, and `Fedora <https://apps.fedoraproject.org/packages/gnuplot>`__.


.. _software-scidavis:

SciDAVis
^^^^^^^^

**SciDAVis** (`homepage <http://scidavis.sourceforge.net/>`__, `Wikipedia <https://en.wikipedia.org/wiki/SciDAVis>`__) is a free and open source visualization software.

SciDAVis is available as a package in `Arch User Repository <https://aur.archlinux.org/packages/scidavis/>`__, `Debian <https://tracker.debian.org/pkg/scidavis>`__, and `Fedora <https://apps.fedoraproject.org/packages/scidavis>`__.



Laboratory protocols, methods, notes, and other documentation
-------------------------------------------------------------

.. contents:: List of software
   :depth: 1
   :local:


.. _software-docutils-sphinx:

Docutils and Sphinx
^^^^^^^^^^^^^^^^^^^

**Docutils** (`homepage <https://docutils.sourceforge.io/>`__, `Wikipedia <https://en.wikipedia.org/wiki/ReStructuredText>`__) is a free and open source text processing software for converting plaintext-like `reStructuredText <https://docutils.sourceforge.io/rst.html>`__ into LaTeX/PDF and HTML.

Docutils are available as a package in `Arch Linux <https://www.archlinux.org/packages/community/any/python-docutils/>`__, `Debian <https://tracker.debian.org/pkg/python-docutils>`__, and `Fedora <https://apps.fedoraproject.org/packages/python-docutils>`__.

**Sphinx** (`homepage <https://www.sphinx-doc.org/>`__, `Wikipedia <https://en.wikipedia.org/wiki/Sphinx_%28documentation_generator%29>`__) is a free and open source documentation generator that builds on top od Docutils and makes it easy to create beautiful documentation.
 
Sphinx is available as a package in `Arch Linux <https://www.archlinux.org/packages/community/any/python-sphinx/>`__, `Debian <https://tracker.debian.org/pkg/sphinx>`__, and `Fedora <https://apps.fedoraproject.org/packages/python-sphinx>`__.


.. _software-pandoc:

Pandoc
^^^^^^

**Pandoc** (`homepage <https://pandoc.org/>`__, `Wikipedia <https://en.wikipedia.org/wiki/Pandoc>`__) is a free and open source document converter between different markup formats.

Pandoc is available as a package in `Arch Linux <https://www.archlinux.org/packages/community/x86_64/pandoc/>`__, `Debian <https://tracker.debian.org/pkg/pandoc>`__, and `Fedora <https://apps.fedoraproject.org/packages/pandoc>`__.


.. _software-libreoffice-writer:

LibreOffice Writer
^^^^^^^^^^^^^^^^^^

**LibreOffice** (`homepage <https://www.libreoffice.org/>`__, `Wikipedia <https://en.wikipedia.org/wiki/LibreOffice>`__) is a free and open source office suite. The word processor component is called `Writer <https://www.libreoffice.org/discover/writer/>`__.

LibreOffice is available as a package in `Arch Linux <https://www.archlinux.org/packages/extra/x86_64/libreoffice-fresh/>`__ (`still branch <https://www.archlinux.org/packages/extra/x86_64/libreoffice-still/>`__), `Debian <https://tracker.debian.org/pkg/libreoffice>`__, and `Fedora <https://apps.fedoraproject.org/packages/libreoffice>`__.


.. _software-graphviz:

Graphviz
^^^^^^^^

**Graphviz** (`homepage <https://www.graphviz.org/>`__, `Wikipedia <https://en.wikipedia.org/wiki/Graphviz>`__) is a free and open source graph visualization software initially developed by `AT&T Labs <https://about.att.com/innovation/labs>`__.

Graphviz is available as a package in `Arch Linux <https://www.archlinux.org/packages/extra/x86_64/graphviz/>`__, `Debian <https://tracker.debian.org/pkg/graphviz>`__, and `Fedora <https://apps.fedoraproject.org/packages/graphviz>`__.


.. _software-font-awesome:

Font Awesome
^^^^^^^^^^^^

**Font Awesome** (`homepage <https://fontawesome.com/>`__, `Wikipedia <https://en.wikipedia.org/wiki/Font_Awesome>`__) is a free and open source set of icons `licensed under the terms of Creative Commons Attribution 4.0 license <https://fontawesome.com/license>`__.

Font Awesome is available as a package in `Arch <https://www.archlinux.org/packages/community/any/ttf-font-awesome/>`__ `Linux <https://www.archlinux.org/packages/community/any/otf-font-awesome/>`__, `Debian <https://tracker.debian.org/pkg/fonts-font-awesome>`__, and `Fedora <https://apps.fedoraproject.org/packages/fontawesome-fonts>`__.



Software development
--------------------

.. contents:: List of software
   :depth: 1
   :local:


.. _software-vs-code:

Visual Studio Code
^^^^^^^^^^^^^^^^^^

**Visual Studio Code** (`homepage <https://code.visualstudio.com/>`__, `Wikipedia <https://en.wikipedia.org/wiki/Visual_Studio_Code>`__) is a proprietary source-code editor built on a number of free and open source software projects. Notable extensions are `Python for Visual Studio Code <https://marketplace.visualstudio.com/items?itemName=ms-python.python>`__ and `C/C++ for Visual Studio Code <https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools>`__.

Visual Studio Code is available as a package in `Arch User Repository <https://aur.archlinux.org/packages/visual-studio-code-bin/>`__, but not in Debian and Fedora. Official binaries for Debian and Fedora (among others) are `provided by Microsoft <https://code.visualstudio.com/Download>`__.
