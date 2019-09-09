# pd/automatonism

Various abstractions for use with [Automatonism](https://www.automatonism.com/) and pd-vanilla

- `midiclock_to_automatonism~.pd` grabs midi input and changes each quarter to an automatonism clock (audio signal). 
  Added some outlets like `/4+1T` which adds a quarter to each of similar outlets for straight delayed events
