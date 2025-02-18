[![Platform: MATLAB](https://img.shields.io/badge/MATLAB-orange.svg?style=plastic)](https://www.mathworks.com)
[![GitHub contributors](https://img.shields.io/github/contributors/fieldtrip/fieldtrip)](https://github.com/fieldtrip/fieldtrip/graphs/contributors)
[![Last commit](https://img.shields.io/github/last-commit/fieldtrip/fieldtrip?style=plastic)](https://github.com/fieldtrip/fieldtrip)
[![GitHub commit activity (branch)](https://img.shields.io/github/commit-activity/m/fieldtrip/fieldtrip)](https://github.com/fieldtrip/fieldtrip/commits/master)
[![GitHub Repo stars](https://img.shields.io/github/stars/fieldtrip/fieldtrip)](https://scholar.google.com/scholar?cites=3328911510682538425&scisbd=1)
[![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg?style=plastic)](https://www.gnu.org/licenses/gpl-3.0)

# FieldTrip 

FieldTrip is the MATLAB software toolbox for MEG and EEG analysis that is being
developed at the Donders Institute for Brain, Cognition and Behaviour in Nijmegen,
the Netherlands together with collaborating institutes.

The toolbox offers advanced analysis methods of MEG, EEG, and invasive
electrophysiological data, such as time-frequency analysis, source reconstruction
using dipoles, distributed sources and beamformers and non-parametric statistical
testing. It supports the data formats of all major MEG systems (CTF,
Neuromag/Elekta/Megin, BTi/4D, Yokogawa/Ricoh, FieldLine) and of most popular EEG
systems, and new formats can be added easily. FieldTrip contains high-level functions
that you can use to construct your own analysis protocols in MATLAB. Furthermore, it
easily allows methods researchers to incorporate new methods for EEG/MEG analysis.

For more information, documentation, and tutorials, please visit http://www.fieldtriptoolbox.org

## Installation

To install the FieldTrip toolbox on your computer, you can clone this repository or
download the zip file, unzip it, and add it to your MATLAB path. Subsequently you call
the `ft_defaults` function, which will add the required subdirectories to the path.

We recommend that you add the `addpath(...)` and the `ft_defaults` command to your
[startup.m](https://www.mathworks.com/help/matlab/ref/startup.html) file. See 
also https://www.fieldtriptoolbox.org/faq/installation/

Note that you should not use `addpath(genpath(...))` and we recommend not to use the
"add with subdirectories" button in the graphical path setup tool, as there are a
number of external toolboxes and backward compatibility directories that you should
not add to your path. If those directories are needed, then `ft_defaults` and
`ft_hastoolbox` will take care of them.

## Copyright

The FieldTrip software is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version. See the file COPYING for more details.

The functions in the FieldTrip toolbox are copyrighted by their respective authors:
  
  - Robert Oostenveld, DCCN, FCDC, SMI, MBFYS
  - Jan-Mathijs Schoffelen, DCCN, MPI, CCNi, FCDC
  - Pascal Fries, FCDC
  - Eric Maris, DCC, FCDC
  - Arjen Stolk, DCCN
  - Eelke Spaak, DCCN
  - Ingrid Nieuwenhuis, DCCN, FCDC
  - Jens Schwarzbach, FCDC
  - Jorn Horschig, DCCN
  - Lilla Magyari, MPI, DCCN
  - Markus Siegel, FCDC, UKE
  - Martin Vinck, DCCN, SILS
  - Ole Jensen, FCDC
  - Roemer van der Meij, DCC 
  - Saskia Haegens, DCCN, FCDC
  - Vladimir Litvak, UCL
  - and many other contributors

The authors are or were working at a range of academic institutions:

  - Copyright (C) 2008-2023, Donders Institute for Brain, Cognition and Behaviour, Radboud University, The Netherlands (DCCN, DCC, DCN)
  - Copyright (C) 2014-2023, Karolinska Institute, Stockholm, Sweden (NatMEG)
  - Copyright (C) 2012-2018, Max Planck Institute for Psycholinguistics, The Netherlands (MPI)
  - Copyright (C) 2008-2017, The Wellcome Trust Centre for Neuroimaging, University College London, UK (UCL)
  - Copyright (C) 2010-2013, Swammerdam Institute for Life Sciences, University of Amsterdam (SILS)
  - Copyright (C) 2008-2009, Centre for Cognitive Neuroimaging in Glasgow, United Kingdom (CCNi)
  - Copyright (C) 2009-2009, Netherlands Institute for Neuroscience (NIN)
  - Copyright (C) 2003-2008, F.C. Donders Centre, Radboud University Nijmegen, The Netherlands (FCDC)
  - Copyright (C) 2004-2007, Nijmegen Institute for Cognition and Information, The Netherlands (NICI)
  - Copyright (C) 2004-2005, Universitatsklinikum Hamburg-Eppendorf, Germany (UKE)
  - Copyright (C) 2003-2004, Center for Sensory Motor Interaction, University Aalborg, Denmark (SMI)
  - Copyright (C) 1999-2003, Department of Medical Physics, Radboud University Nijmegen, The Netherlands (MBFYS)

The FieldTrip software is a toolbox, i.e. a library with functions, which in turn
an depend on other functions. The release of this toolbox includes functions from
other toolboxes that are covered under their respective licenses. See
fieldtrip/external for details. Unauthorised copying and distribution of functions
that are not explicitly covered by the GPL is not allowed.
