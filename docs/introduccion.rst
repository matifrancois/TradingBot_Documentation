Welcome to Trading Bot
======================

This python-developed module implements a simple trading bot that looks
for arbitrage opportunities based on future implicit rates calculations.

To do that, it takes the relevant futures and spots information from
yfinance and the remarket environment. There is a connection established
through websockets with that remarket environment so that each change in
the stocks of the environment triggers an action set locally to get the
spots data from yfinance and then, with that data, it can calculate the
taker and offered rates to then check for arbitrage possibilities.

How to Download
---------------

to download the library go to `TraderBot in
Github <https://github.com/matifrancois/AlmaFintechTraderBot>`__, and
follow the instrucction bellow:

Installation
------------

To use this program you must clone the repository locally.

Once done, you should run the file requirements.txt which indicates all
necessary requirements to run the software. You can do this with the
following lines, and it's really convenient that the installation of any
requirements is done in a virtual environment to avoid dependency issues
with other locally-installed packages.

.. code:: shell

    $ cd <proyect_path>/AlmaFintechTraderBot
    $ pip install -r requirements.txt