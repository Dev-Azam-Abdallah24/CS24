# Comprehensive Definitions for AI Lectures

This document contains a comprehensive list of definitions and key concepts from the three provided AI lectures. It is designed to be a study guide for memorization.

## Lecture 1: Introduction to AI (AI_introCh1.pdf)




### Key Definitions from AI_introCh1.pdf

*   **Artificial Intelligence (AI):** Computer systems that can simulate tasks that typically require human intelligence, like learning, problem-solving, and decision-making [1, p. 2].
*   **Agent/Intelligent Agent:** A machine that solves problems that are challenging for humans [1, p. 4]. Anything that can be viewed as perceiving its environment through sensors and acting upon that environment through actuators [2, p. 3].
*   **Narrow AI:** Focuses on intelligent agents to solve a specific problem [1, p. 4].
*   **Artificial General Intelligence (AGI):** A hypothetical intelligent agent which can understand or learn any intellectual task that human beings can [1, p. 4].
*   **Turing Test:** A test that tries to define what acting like a human means. It assesses a machine's ability to exhibit intelligent behavior equivalent to, or indistinguishable from, that of a human [1, p. 6].
*   **Natural Language Processing (NLP):** An AI area focused on enabling computers to understand, interpret, and generate human language [1, p. 6].
*   **Knowledge Representation:** An AI area concerned with how knowledge is stored and organized in a way that allows AI systems to use it for reasoning [1, p. 6].
*   **Automated Reasoning:** An AI area focused on enabling computers to draw conclusions from existing knowledge using logical inference [1, p. 6].
*   **Machine Learning (ML):** A subfield of AI that allows computers to learn from data without explicit programming [1, p. 2].
*   **Rationality:** Drawing sensible conclusions from facts, logic, and data [1, p. 8].
*   **Acting Rational:** Trying to achieve the “best” outcome, often measured by the economic concept of utility [1, p. 10].
*   **Moravec’s Paradox:** The observation that it is comparatively easy to make computers exhibit adult-level performance on intelligence tests or playing checkers, and difficult or impossible to give them the skills of a one-year-old when it comes to perception and mobility [1, p. 17].
*   **AI Effect:** As soon as a machine gets good at performing some task, the task is no longer considered to require much intelligence [1, p. 18].
*   **Algorithmic Bias:** Systematic and repeatable errors in a computer system that create unfair outcomes, such as privileging one arbitrary group of users over others [1, p. 33].
*   **AI Safety:** Preventing accidents, misuse, or other harmful consequences of AI [1, p. 34].




## Lecture 2: AI Agents (AI_agentsCh2.pdf)

### Key Definitions from AI_agentsCh2.pdf

*   **Agent:** Anything that can be viewed as perceiving its environment through sensors and acting upon that environment through actuators [2, p. 3].
*   **Agent Function:** A mathematical function that maps from the set of all possible percept sequences P* to the set of actions A (f: P* → A) [2, p. 4].
*   **Agent Program:** A concrete implementation of the agent function for a given physical system [2, p. 4].
*   **Rational Agent:** For each possible percept sequence, a rational agent should select an action that maximizes its expected performance measure, given the evidence provided by the percept sequence and the agent’s built-in knowledge [2, p. 9].
*   **Performance Measure:** An objective criterion for success of an agent's behavior (often called utility function or reward function) [2, p. 9].
*   **PEAS (Performance measure, Environment, Actuators, Sensors):** A framework for specifying the task environment of an agent [2, p. 13].
    *   **Performance measure:** Defines utility and what is rational actions [2, p. 13].
    *   **Environment:** Components and rules of how actions affect the environment [2, p. 13].
    *   **Actuators:** What is available to the agent to act [2, p. 13].
    *   **Sensors:** Defines percepts [2, p. 13].
*   **Fully Observable Environment:** The agent's sensors give it access to the complete state of the environment [2, p. 17].
*   **Partially Observable Environment:** The agent cannot see all aspects of the environment [2, p. 17].
*   **Deterministic Environment:** Changes in the environment are completely determined by the current state of the environment and the agent’s action [2, p. 17].
*   **Stochastic Environment:** Changes cannot be determined from the current state and the action (there is some randomness) [2, p. 17].
*   **Strategic Environment:** The environment is stochastic and adversarial. It chooses actions strategically to harm the agent [2, p. 17].
*   **Known Environment:** The agent knows the rules of the environment and can predict the outcome of actions [2, p. 17].
*   **Unknown Environment:** The agent cannot predict the outcome of actions [2, p. 17].
*   **Static Environment:** The environment is not changing while the agent is deliberating [2, p. 18].
*   **Dynamic Environment:** The environment is changing while the agent is deliberating [2, p. 18].
*   **Semi-dynamic Environment:** The environment is static, but the agent's performance score depends on how fast it acts [2, p. 18].
*   **Discrete Environment:** The environment provides a fixed number of distinct percepts, actions, and environment states [2, p. 18].
*   **Continuous Environment:** Percepts, actions, state variables or time are continuous leading to an infinite state, percept or action space [2, p. 18].
*   **Episodic Environment:** Episode (event) = a self-contained sequence of actions. The agent's choice of action in one episode does not affect the next episodes [2, p. 18].
*   **Sequential Environment:** Actions now affect the outcomes later [2, p. 18].
*   **Single Agent Environment:** An agent operating by itself in an environment [2, p. 18].
*   **Multi-agent Environment:** Agent cooperate or compete in the same environment [2, p. 18].
*   **Simple Reflex Agent:** Uses only built-in knowledge in the form of rules that select action only based on the current percept [2, p. 23].
*   **Model-based Reflex Agent:** Maintains a state variable to keep track of aspects of the environment that cannot be currently observed (has memory and knows how the environment reacts to actions) [2, p. 24].
*   **Transition Function:** Describes how the environment changes due to system dynamics and agent actions (S' = T(S, A)) [2, p. 25].
*   **State Space:** The set of all possible states [2, p. 26].
*   **Goal-based Agent:** An agent that has the task to reach a defined goal state and is then finished. Uses search algorithms to plan actions [2, p. 29].
*   **Utility-based Agent:** An agent that uses a utility function to evaluate the desirability of each possible state. Chooses actions to stay in desirable states [2, p. 30].
*   **Learning Element:** Modifies the agent program to improve its performance [2, p. 31].




## Lecture 3: AI Search (AI_searchCh3.pdf)

### Key Definitions from AI_searchCh3.pdf

*   **Search Problem:** The problem of designing goal-based agents in known, fully observable, and deterministic environments [3, p. 2].
*   **Initial State:** The starting state description for the search [3, p. 5].
*   **Actions:** The set of possible actions available from a given state [3, p. 5].
*   **Transition Model:** A function that defines the new state resulting from performing an action in the current state [3, p. 5].
*   **Goal State:** The state description that the agent aims to reach [3, p. 5].
*   **Path Cost:** The sum of step costs to reach a particular state from the initial state [3, p. 5].
*   **Optimal Solution:** The sequence of actions (or equivalently a sequence of states) that gives the lowest path cost for reaching the goal [3, p. 5].
*   **State Space:** The set of all possible states of the environment and some states are marked as goal states [3, p. 4]. It is the number of different states the agent and environment can be in [3, p. 21].
*   **Search Tree:** A "what if" tree of possible actions and outcomes (states) superimposed on the state space graph [3, p. 13].
*   **Root Node:** Represents the initial state in a search tree [3, p. 13].
*   **Uninformed Search Strategies:** Search algorithms where the agent is not provided information about how close a state is to the goal state. It blindly searches following a simple strategy until it finds the goal state by chance [3, p. 28].
*   **Breadth-First Search (BFS):** An uninformed search strategy that expands the shallowest unexpanded node in the frontier (FIFO) [3, p. 29].
*   **Uniform-Cost Search (UCS):** An uninformed search strategy that expands the node in the frontier with the least path cost from the initial state (Dijkstra’s shortest path algorithm) [3, p. 35].
*   **Depth-First Search (DFS):** An uninformed search strategy that expands the deepest unexpanded node in the frontier (LIFO) [3, p. 38].
*   **Iterative Deepening Search (IDS):** A search strategy that combines the benefits of BFS and DFS by performing a series of depth-limited DFS searches with increasing depth limits [3, p. 44].
*   **Completeness (of a search strategy):** Does it always find a solution if one exists? [3, p. 19].
*   **Optimality (of a search strategy):** Does it always find a least-cost solution? [3, p. 19].
*   **Time Complexity (of a search strategy):** How long does it take? [3, p. 19].
*   **Space Complexity (of a search strategy):** How much memory does it need? [3, p. 19].
*   **Branching Factor (b):** Maximum number of successor nodes for a parent in the search tree [3, p. 19].
*   **Depth (d):** Depth of the optimal solution (number of actions needed) [3, p. 19].
*   **Maximum Depth (m):** The number of actions in any path (may be infinite with loops) [3, p. 19].




## References

[1] AI_introCh1.pdf
[2] AI_agentsCh2.pdf
[3] AI_searchCh3.pdf


