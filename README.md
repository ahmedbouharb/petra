# petra
Un modèle économique Python simulant la formation des prix d'équilibre sur un marché financier avec deux types d'investisseurs : averses au risque et amateurs de risque. Le projet démontre comment les préférences face au risque affectent l'équilibre de marché.
Ce modèle sert à modéliser l'interaction offre/demande avec hétérogénéité des agents et analyser l'impact de la prime de risque sur les prix d'équilibre.
Les Variables:
-P : Prix du titre.
-R : Prime de risque.
-θ : Proportion d'investisseurs averses au risque.
-σ₁, σ₂ : Sensibilités au risque (négative pour averses, positive pour amateurs).
Le projet inclut plusieurs scénarios prédéfinis :
-Marché baissier : Prime de risque élevée.
-Marché haussier : Prime de risque faible.
-Choc de préférences : Variation de θ.
ENGLISH
A Python-based economic model simulating equilibrium price formation in a financial market with two types of investors: risk-averse and risk-seeking agents.
The project illustrates how heterogeneous risk preferences influence market equilibrium and how changes in the risk premium affect price dynamics.

The model captures the interaction between supply and demand in a market where agents react differently to perceived risk. It provides a framework to analyze how variations in investor composition or market conditions drive equilibrium price adjustments.

Variables

P: Asset price

R: Risk premium

θ: Proportion of risk-averse investors

σ₁, σ₂: Risk sensitivities (σ₁ negative for risk-averse agents, σ₂ positive for risk-seeking agents)

Included Scenarios

The project implements several predefined simulation scenarios:

Bear Market
Characterized by a high risk premium, reflecting increased uncertainty and heightened aversion to risk.

Bull Market
Corresponds to a low risk premium, indicating favorable market expectations.

Preference Shock
A sudden change in the proportion θ of risk-averse investors, allowing the analysis of shifts in market sentiment or structural changes in investor composition.
