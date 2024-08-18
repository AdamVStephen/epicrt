# Inverted Pendulum Control Projects

## Theory

A number of variations on the theme of inverted pendulum experiments exist.  The dynamics are simple enough
to be easily understood, but interesting enough to demonstrate a number of physics and control theory issues.
Equipment can readily be purchased or constructed to make a physical demonstration which introduces
practical technology issues.


## STM Edukit - with UCLA

https://www.st.com/en/evaluation-tools/steval-edukit01.html

UKAEA own 3 of these kits and have a demonstration in which the control is exported from the
STM32 device as a monolithic 5000 line C program to a MARTe2 application which abstracts
the encoder position output and stepper motor driver inputs as a data source.  This 
has been demonstrated to run within a WSL container on a Windows laptop  (credit : Jawad Muhammad).

TODO : make Jawad's implementation open  on github.

## Quanser Qube

https://www.quanser.com/products/qube-servo-2/
