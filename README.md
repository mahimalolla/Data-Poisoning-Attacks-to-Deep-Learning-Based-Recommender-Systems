# Data-Poisoning-Attacks-to-Deep-Learning-Based-Recommender-Systems


Many web services, including Amazon, YouTube,
and Google News, use recommendation systems to help users
find interesting information. In industry, a wide range of
recommendation systems have been developed and deployed,
including neighborhood-based, association-rule-based, matrix-
factorization-based, and deep learning-based. Due to their supe-
rior performance, deep learning-based recommendation systems
are becoming increasingly popular. Data poisoning attacks on
deep learning recommendation systems are examined for the
first time in this work. In order to achieve this goal, an attacker
manipulates a recommendation system so that many users are
recommended the attacker’s chosen items. Our attack injects
carefully crafted ratings from fake users into a recommendation
system to achieve this goal. The target items are recommended
to as many normal users as possible using the injected ratings,
which is an optimization problem. As a non-convex integer
programming problem, the optimization problem is challenging
to solve. Several techniques are developed to approximate the
solution to the optimization challenge. We found that our attack
outperformed existing attacks on three real-world data sets,
including small and large ones. Additionally, we analyze normal
and fake users’ rating patterns statistically to detect fake users.
Even with such a detector deployed, our attack remains effective
and outperforms existing attacks
