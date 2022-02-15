# bayesnet_attribution

We have 3 channels that drive a conversion

(C1, C2, C3) all drive Conv

C1 also drives (C2, C3)

We can estimate most conditional probabilites like P(conv|C1, C2, C3) etc.

We populate the BN and then get the channel effect as $P(conv|C1) - P(conv|\neg C1)$

🦇
