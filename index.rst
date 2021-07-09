.. role:: raw-html(raw)
    :format: html

######################
Natural Quantum Script 
######################

About NQS
**********

Natural Quantum Script is a special domain programming language that aims to simplify the first contact with quantum computing for people who have prior knowledge in quantum circuits, but not in quantum software development.

Scripts written in NQS seek to visually resemble quantum circuits as much as possible. For example:

q0 q1
X
H
.--- X
c1

NQS is initially based on Qiskit, but seeks to go mainstream in the future. This is an OS project whose initial goal was to make it easier to write basic scripts in Qiskit and to bridge the gap for people who don't dare to delve into quantum computing.

Advantages
==========

1. NQS is written 100% in python. :raw-html:`<br />`
2. Scripts written in NQS seek to visually resemble quantum circuits as much as possible.


Sofware (for developers)
************************

Get the last version of this software here <https://github.com/PythonForChange/FilesFormat>`__

.. image:: https://readthedocs.org/projects/pyfoch/badge/?version=latest

###########
Quick Start
###########

Installation (last stable version)
**********************************

Under construction

3. Enjoy!

Writting PFCF code with `Pyfoch Editor <https://pythonforchange.github.io/pyfoch>`__
*************************************************************************************

Example
=======

1. Open `Pyfoch <https://pythonforchange.github.io/pyfoch>`__.

2. Write the following lines:
 
    q0  q1 :raw-html:`<br />`
        X :raw-html:`<br />`
    H :raw-html:`<br />`
    .---X :raw-html:`<br />`
    c1 :raw-html:`<br />`
    $host qasm_simulator :raw-html:`<br />`
    $hist true :raw-html:`<br />`
    $draw true :raw-html:`<br />`

3. In "File" menu, click on "Export". :raw-html:`<br />`
4. Give a name to your exported file and save. :raw-html:`<br />`
5. Open the exported file. :raw-html:`<br />`
6. The exported file will have the following text:

    q0  q1 :raw-html:`<br />`
        X :raw-html:`<br />`
    H :raw-html:`<br />`
    .---X :raw-html:`<br />`
    c1 :raw-html:`<br />`
    $host qasm_simulator :raw-html:`<br />`
    $hist true :raw-html:`<br />`
    $draw true :raw-html:`<br />`

7. Enjoy!

                
##################
UNDER CONSTRUCTION
##################

##############
Style commands
##############

Adding a new line
*****************
Add the comma symbol to create a new line.

    This is a line,This is other line ::

Our exported file will be something like this:

    This is a line
    :raw-html:`<br />`
    This is other line ::

#################################
Introduction to the changeability
#################################

The heart of PFCF language is the changeability. Changeable code has a marked tendency to change. :raw-html:`<br />`
PFCF use the changeability in order to improve the efficience in the coding development experience.

Add the "$" symbol to write a new changeability command. For example, let's say Pyfoch we want to start a new text block.

    $block begin ::

The general sintaxis is simple:

    $command parameter ::

Always we must write in a new line after writting a changeability command.


