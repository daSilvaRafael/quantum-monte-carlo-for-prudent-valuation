# Quantum Monte Carlo for prudent valuation

## Abstract

This paper explores the application of Quantum Monte Carlo (QMC) algorithms to the prudent valuation of financial derivatives, which is for critically important for regulatory compliance in the financial industry. Quantum computing leverages quantum-mechanical principles to increase computational efficiency, presenting opportunities for solving complex problems in quantitative finance, in particularly derivatives pricing. While QMC methods have been explored in various financial contexts, this is the first time that QMC algorithms have been discussed in the context of prudent valuation. To assess the feasibility and potential utility of QMC algorithms, the performance of the maximum likelihood quantum amplitude estimation (MLQAE) algorithm, a QMC variant, is compared against classical Monte Carlo (MC) simulations and the Black--Scholes formula for pricing European call options via a quantum simulator. The results indicate that while small instances of the MLQAE algorithm can outperform classical MC simulation in specific scenarios, challenges remain in terms of probability distribution discretization, payoff linear approximation, and current quantum hardware resources. This research pushes the boundaries of applying quantum computing to real-world financial problems and contributes to the literature on quantum computational finance, a recent multidisciplinary field that has the potential to revolutionize how financial institutions approach risk management. 



## Installation

Install requirements locally (ideally, in a virtual environment):

    pip install -r requirements.txt


## License

Released under the Apache License 2.0. See LICENSE file.
