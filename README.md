# CivilizAgent (Demo): Large Language Model-based Multi-Agent Simulation of Historical Events
(Demo is based on a fictional scenario and countries)
(Video was too large to put into repository, google drive link available at the bottom)

**What is really going on at the crossroads of history?**
Throughout human history everyone from scholars to statesmen have sought to find the answer. In this simulation, we seek to shed light upon the question using the recent advances of Artificial Intelligence and Large Language Models (LLMs). Introducing **CivilizAgent**, an LLM-powered multi-agent AI system, thats simulates the decision-making between countries at turning points in history. Not only does the system model the interactions from country to country, it also focuses on the internal desicion-making process driven by the factions within each nation. 
Scenarios include the Peloponnesian War and the Southern Ming Era in Ancient China among others.
By evaluating the simulation effectiveness, we examine the advancements and limitations of cutting-edge AI systems' abilities in studying complex collective human behaviors in diverse settings. In these simulations, the emergent interactions among agents also offer a novel perspective for examining the triggers and conditions that lead to war. Our findings offer data-driven and AI-augmented insights that can redefine how we approach conflict resolution and peacekeeping strategies. The implications stretch beyond historical analysis, offering a blueprint for using AI to understand human history and possibly prevent future international conflicts.

## CivilizAgent Architecture
- Faction Agent & Faction Agent Interaction: Each country system consists of faction agents. The factions are defined in the facitons profile for each country. In each internal round, the faction agent reacts to the current situation by generating internal factions actions as well as supporting/opposing country decisions from the action space.
- Country Agent & Country Agent Interaction: Each country agent is defined by its corresponding country profile. In each round, the agent reacts to the current situation and their country's decisions by generating corresponding messages.
- Faction Agent & Secretary Agent Interaction: Each faction agent employs a designated “secretary agent” to verify the appropriateness and basic logical consistency of their actions.
- Board and Stick: The Board is designed to manage international relationships and the Stick functions as an internal record-keeping system for each country that represents the domestic statutes.

### Demo
link to [video](https://drive.google.com/drive/u/0/folders/14lYc-cVJFHQq8ZpaYwwZhGCi8xUGKjlo) demo folder with a 12-minute demo using a fictional scenario
