import_serial test data
=======================

Test data for import_serial task in CCP4 - available at https://github.com/MartinMalyMM/import_serial

You can try to run these commands:

.. code ::

   $ ccp4-python -m import_serial --hklin 116720-721.lst-asdf-scale.hkl --half-dataset 116720-721.lst-asdf-scale.hkl1 116720-721.lst-asdf-scale.hkl2 --spacegroup P21 --cell 39.4 78.5 48.0 90 97.94 90
   $ ccp4-python -m import_serial --hklin 116720-721.lst-asdf-scale.hkl --spacegroup P21 --cell 39.4 78.5 48.0 90 97.94 90 --nbins 20 --dmin 1.65 --project protein --dataset 01

Developed by Martin Maly, University of Southampton, `martin.maly@soton.ac.uk <mailto:martin.maly@soton.ac.uk>`_
