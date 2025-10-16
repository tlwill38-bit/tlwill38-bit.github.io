---
title: Individual Component Selection
---



### Float Switch

**External Clock Module**

1. 59630-1-T-02-A 	
SENSOR LEVEL SWITCH SINGLE FLOAT

    ![](Floatswitch.png)

    * $1/each
    * [link to product](https://www.digikey.com/en/products/detail/littelfuse-inc/59630-1-T-02-A/4771999?gclsrc=aw.ds&gad_source=1&gad_campaignid=20509825838&gbraid=0AAAAADrbLlhgS6gBiX18_P1FSC4Ya6Ls5&gclid=CjwKCAjwr8LHBhBKEiwAy47uUm2amo2He_7OUOuz4vKCIkU70yORPZDnrcjj5UW6E_2C8vhyiks2WhoCF10QAvD_BwE)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive                               | Requires external components and support circuitry for interface |
    | Compatible with PSoC                      | Needs special PCB layout.                                        |
    | Meets surface mount constraint of project |

1. CTX936TR-ND surface mount oscillator

    ![](image3.png)

    * $1/each
    * [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Outputs a square wave                                             | More expensive      |
    | Stable over operating temperature                                 | Slow shipping speed |
    | Direct interface with PSoC (no external circuitry required) range |

**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.
