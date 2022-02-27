How does Aave interest Rate Uber Model work?

Stable coins Interest Rate Model:
  Base rate:
    Set a base rate(ex: 1.5%) that no matter the utilization of the token pool, anyone borrowers from the pool will be charged base rate at minimum
    We can use same base rate to every USD Stable coin or we can also use different Base rate to different stable coins
  Demand added rate:
    Set a 5% Demand added rate that will variance based on the utilization of the token pool utilization
    It’s similar to every stable coin that max rate of any pools equals (Base rate + 5% Demand added Rate)
Discount rate:
    Only applicable to VIP user
    Set a limit that if any borrowers pays X amount or larger in interest, then the protocol will gives 10%(of fees) discount(so we can inspire users to borrow larger amount for longer time)
    The charging rate has to be above Discount rate to eligible to discount
Token distribution &  Base rate insurance fund token distribution:
    If any circumstances any stable coins earns below base rate, then there will be token distribution to guarantee LPs that they will always earn above the base rate
    
Pic URL:
    https://www.figma.com/file/Jfall3XQTfmp0nGqnSZjcd/AAVE-Interest-Rate-Uber-Model?node-id=0%3A1
-----------------------------------------------------------------------------------------------------    
    
Gas token Interest Rate Modle:
  Gas tokens: BTC, ETH, AVAX, and so on
  It will work like Stable coin interest rate model, but with different base rate for each tokens.
-----------------------------------------------------------------------------------------------------

Gov tokens interest Rate Model:
  Gov tokens: AAVE, YFI, UNI, COMP, so on
    Gov token unlike stable coins users only borrower for short periods of time, and only borrow ones in a while, so borrowers doesn’t really cares about the interest rate amount
    So interest rate can be higher, and borrowers still borrow it
  Option 1: use Stable coin like interest rate model, and set higher base rate
  Option 2: set Fixed daily based interest rate that charge 0.1%/day(and minimum 0.1%(base rate))
  Option 3 : At normal times will lend as unusual, and at the gov proposal voting period will change  0.1% of the token value for per 24 hours 
----------------------------------------------------------------------------------------------------

Stable coin LP base rate guarantee:
  Stable coin LPs are the root of the protocol, so we have to guarantee the LPs that always will earns above the base rate
    Based on current borrowing rate there won’t happen earning lower than base rate, but it might happen in the future
      If utilization goes down grammatically, then will happen 
    Guarantee mean is not unlimited
      There will be distribution limitation if there will be large amount of distribution needed
      If the Distribution amount is not as big, then Will be distributed immediately
  If the LPs earns lower than base rate, then AAVE will incentivizes with  gov token to give LPs guaranteed base rate
  The liquidity at first comes from AAVE token Distribution program, in the future comes from Base Rate Insurance fund pool
  Main purpose of Stable coin base rate guarantee is to attract as much stable coin liquidity as possible, and promise them there always will be guaranteed yield,  so don’t withdraw the liquidity even when low utilization happens
-----------------------------------------------------------------------------------------------------

Much more:
  https://docs.google.com/document/d/17dVyb5M1lowYgvEF8nTGm6vatvTfJq0R9Bicj24Q_Os/edit?usp=sharing





  
