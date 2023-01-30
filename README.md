# permanent-ink
Prove the existence of data on Web2 in anticipation that it will later be censored

# Concept

There was a recent exposé of a supposed Pfizer executive, making alarming claims on hidden camera. Later, little information was available online which demonstrated this individual's connection to the company. Supporters of the exposé claimed that the information was scrubbed from the internet, some even claiming that it was done with the cooperation of tech giants such as Google. It is in everyone's best interest -- regardless of how you feel about the claims being made -- to have the ability to prove the existence of data on the web at a given time. Given the centralized nature of Web2, it's possible to remove information, or adjust search results, to hide or destroy evidence without a trace. However, if we can anticipate this possiblity before, say, we launch an undercover investigation on an individual, it is possible for us to use decentralized technology to prove the existence of such information before it is removed.

General technical implementation:
1. Design a contract which accepts an API endpoint and necessary credentials as arguments.
1. Using the Internet Computer (https://internetcomputer.org/) or an appropriate oracle, make the request from within the contract, which undeniably proves the source of the data.
2. Write the resulting data to a ledger.
