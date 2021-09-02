Use
===

Once the requirements are installed, you can use the program with the
following code:

.. code:: shell

    $ cd traderBot
    $ python main.py

With this, the program will run and show a set of menus where you can
select various settings for the usage experience. The questions and
options are as follows:

.. raw:: html

   <ul>
     <li>

Mode?

.. raw:: html

   <ul>
         <li>

No Extra Info

.. raw:: html

   </li>
         <li>

Verbose

.. raw:: html

   </li>
         <li>

Debugging

.. raw:: html

   </li>
       </ul>
     </li>
     <li>

How many future dollars do you want?

.. raw:: html

   <ul>
         <li>

One

.. raw:: html

   </li>
         <li>

Five

.. raw:: html

   </li>
         <li>

All Available (takes longer)

.. raw:: html

   </li>
       </ul>
     </li>
     <li>

Do you want to clear the console with every price change?

.. raw:: html

   <ul>
         <li>

No

.. raw:: html

   </li>
         <li>

Yes

.. raw:: html

   </li>
       </ul>
     </li>
     <li>

What language do you prefer?

.. raw:: html

   <ul>
         <li>

English

.. raw:: html

   </li>
         <li>

Spanish

.. raw:: html

   </li>
       </ul>
     </li>
   </ul>

After selecting the desired settings, you can begin data download. This
process may take a few seconds or even minutes, depending on the number
of dollar futures you requested.

When data load is finished, the system is ready and will show updated
taker and offered rates for a given future after each price change.
Then, it will show a chart with the available arbitrage possibilities in
all possible future dates.
