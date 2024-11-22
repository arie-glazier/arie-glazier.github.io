---
title: "Making Human-Like Trade-offs in Constrained Environments by Learning from Demonstrations"
collection: publications
category: manuscripts
permalink: /publication/2025-05-19-demonstrations
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2025-05-19
venue: 'AAMAS (under review)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arie-glazier.github.io/files/making-human-tradeoffs-from-demonstrations.pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Many real-life scenarios require humans to make difficult trade-offs: do we always follow all the traffic rules or do we violate the speed limit in an emergency? These scenarios force us to evaluate the trade-off between collective norms and our own personal objectives. To create effective AI-human teams, we must equip AI agents with a model of how humans make trade-offs in complex, constrained environments. These agents will be able to mirror human behavior or to draw human attention to situations where decision making could be improved. To this end, we propose a novel inverse reinforcement learning (IRL) method for learning implicit hard and soft constraints from demonstrations, enabling agents to quickly adapt to new settings. In addition, learning soft constraints over states, actions, and state features allows agents to transfer this knowledge to new domains that share similar aspects. We then use the constraint learning method to implement a novel system architecture that leverages a cognitive model of human decision making, multi-alternative decision field theory (MDFT), to orchestrate competing objectives. We evaluate the resulting agent on trajectory length, number of violated constraints, and total reward, demonstrating that our agent architecture is both general and achieves strong performance. Thus we are able to capture and replicate human-like trade-offs from demonstrations in environments when constraints are not explicit.