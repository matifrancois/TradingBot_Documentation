# Use

Once the requirements are installed, you can use the program with the following code:

```shell
$ cd traderBot
$ python main.py
```

With this, the program will run and show a set of menus where you can select various settings for the usage experience. The questions and options are as follows:

<ul>
  <li>Mode?
    <ul>
      <li>No Extra Info</li>
      <li>Verbose</li>
      <li>Debugging</li>
    </ul>
  </li>
  <li>How many future dollars do you want?
    <ul>
      <li>One</li>
      <li>Five</li>
      <li>All Available (takes longer)</li>
    </ul>
  </li>
  <li>Do you want to clear the console with every price change?
  <ul>
      <li>No</li>
      <li>Yes</li>
    </ul>
  </li>
  <li>What language do you prefer?
  <ul>
      <li>English</li>
      <li>Spanish</li>
    </ul>
  </li>
</ul>

After selecting the desired settings, you can begin data download. This process may take a few seconds or even minutes, depending on the number of dollar futures you requested.

When data load is finished, the system is ready and will show updated taker and offered rates for a given future after each price change. Then, it will show a chart with the available arbitrage possibilities in all possible future dates.
