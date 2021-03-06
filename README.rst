======================================================
 Simple visualization of a sequence in a helical wheel
======================================================

:Authors:       Katrin Reichel
:Company:       `ProteinQure Inc. <https://www.proteinqure.com>`
:Year:          2019
:Licence:       MIT License
:Copyright:     © 2019 Katrin Reichel

Description
===========

The provided python script generates a helical wheel based on an input sequence. For a random sequence it looks like this:

.. image::  /img/hw_example.png
    :height: 100px

Dependencies and Software Requirements
======================================

* Python (>=3.6)
* Python packages: numpy, matplotlib


Usage
=====

To generate a helical wheel with an input sequence, simply do the following::

      python hw_visualization.py \
         -s ACDEFGHIKLMNPQRSTVWYACDE \
         -o hw_output.png

Help
====

Please, if you encounter any issues with the tool, open an issue here on the github repository https://github.com/proteinqure/visualize_hw/issues.

If you have any questions or suggestions, please contact team@proteinqure.com.

