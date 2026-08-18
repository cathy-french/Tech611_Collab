## hello? we are back department? i'd like to file a claim.
- [ ] take a walk
- [x] steal the moon

```mermaid
pie title people who enjoy radiohead
    "yes" : 40
    "yes in a different color" : 14
```


```mermaid
flowchart TD
    Money["Do you have money?"]
    Buy["BUY FERRAN TORRES JERSEY"]
    NotFor["Not for Ferran Torres jersey"]
    Blasphemy["BLASPHEMY"]
    Job["Do you have a job?"]
    Pay["They pay you?"]
    Possessions["Do you have possessions?"]
    SellThem["Sell them"]
    Soul["Do you have a soul?"]
    SellIt["Sell it"]
    Liar["Liar"]

    Money -->|YES| Buy
    Money -->|NO| Job
    Money --> NotFor
    NotFor --> Blasphemy
    Blasphemy --> Buy

    Job -->|YES| Pay
    Job -->|NO| Possessions

    Pay -->|YES| Buy
    Pay -->|NO| Possessions

    Possessions -->|YES| SellThem
    SellThem --> Buy
    Possessions -->|NO| Soul

    Soul -->|YES| SellIt
    SellIt --> Buy
    Soul -->|NO| Liar
    Liar --> Soul
```
