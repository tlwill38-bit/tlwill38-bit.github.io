---
title: Individual Component Selection
---



### Float Switch

**External Clock Module**

1. 59630-1-T-02-A 	
SENSOR LEVEL SWITCH SINGLE FLOAT

    ![](Floatswitch.png)

    * $7.99/each
    * [link to product](https://www.digikey.com/en/products/detail/littelfuse-inc/59630-1-T-02-A/4771999?gclsrc=aw.ds&gad_source=1&gad_campaignid=20509825838&gbraid=0AAAAADrbLlhgS6gBiX18_P1FSC4Ya6Ls5&gclid=CjwKCAjwr8LHBhBKEiwAy47uUm2amo2He_7OUOuz4vKCIkU70yORPZDnrcjj5UW6E_2C8vhyiks2WhoCF10QAvD_BwE)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Realitivly Inexpensive                               | Requires external components and support circuitry for interface |
    | Compatible with PSoC                      | Needs special PCB layout.                                        |
    | Meets constraint of project | Requires Set up |

1. CTX936TR-ND surface mount oscillator

    ![](Floatswitch2.png)

    * $4.17/each
    * [Link to product](https://www.digikey.com/en/products/detail/standex-meder-electronics/LS02-1A66-PA-500W/385415?gclsrc=aw.ds&gad_source=1&gad_campaignid=20232005509&gbraid=0AAAAADrbLliL8TzXuQg7x9tLNvO4PqNgi&gclid=CjwKCAjwr8LHBhBKEiwAy47uUmjZq440IywNQ2jzZLL1ziGtNA4FLnNz39L1NnW2fEzmiRx9LQ9PThoCPxgQAvD_BwE)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Cheaper Item                                             | Cheaper Quality      |
    | Single Switch                                 | Slow shipping speed |
    | Direct interface with PSoC (no external circuitry required) range |

**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.
