Arbitrage Strategy
==================

The basic arbitrage strategy is the following:

.. raw:: html

   <ul>
   <li>

For each price change, taker and offered rates are calculated for all
futures we're interested in.

.. raw:: html

   </li>
   <li>

Then, dictionaries are updated and sorted ascending based on offered
rate and descending based on taker rate

.. raw:: html

   </li>
   <li>

Once done, for each maturity date, we take the highest taker rate and
the lowest offered rate and compare then against commission rates to
check for arbitrage opportunities.

.. raw:: html

   </li>
   <li>

In case of an opportunity, it's stored in a dictionary that instructs to
buy the minimum offered rate contract long and short the current spots,
to then short buy the future with the highest taker rate and short buy
the spot that corresponds to that future.

.. raw:: html

   </li>
   </ul>

Assumptions
-----------

.. raw:: html

   <ul>
   <li>

It is assumed the year has 365 days (not considering leap years in rate
calculations)

.. raw:: html

   </li>
   <li>

Only transactions on futures with the same maturity date are considered

.. raw:: html

   </li>
   <li>

Only one arbitrage opportunity per date is calculated, which is the best
option available, considering one has no stock trading (buying or
selling) limitations.

.. raw:: html

   </li>
   <li>

Inflation is partially disregarded though it should be taken into
account to guarantee profit against other arbitrage strategies.

.. raw:: html

   </li>
   <li>

It is assumed that on maturity date, there is 1 remaining day until the
end of a contract.

.. raw:: html

   </li>
   </ul>


