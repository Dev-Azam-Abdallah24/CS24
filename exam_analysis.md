## تحليل العلاقة بين أسئلة الاختبار ومحتوى المحاضرات

### نظرة عامة على ملف الاختبار (ذكاءصناعينصفي2024.pdf)

ملف الاختبار يتكون من 3 أسئلة رئيسية:
1.  **Q1: Fill-in-the-Blank (املأ الفراغ):** يركز على المفاهيم الأساسية والتعاريف من المحاضرات.
2.  **Q2: Performance measure, Environment, Actuators, Sensors (PEAS) for Automated Taxi Driver (قياس الأداء، البيئة، المحركات، الحساسات لسائق التاكسي الآلي):** سؤال تطبيقي يتطلب فهم إطار عمل PEAS وتطبيقه على سيناريو محدد.
3.  **Q3: Choose Two of the following questions and answer them (اختر سؤالين مما يلي وأجب عنهما):** يتضمن أسئلة مفتوحة تتطلب شرحًا تفصيليًا لمفاهيم أو خوارزميات معينة، مع أمثلة وشرح للخصائص أو الكود.

### ربط أسئلة الاختبار بالمحاضرات

#### المحاضرة الأولى: AI_introCh1.pdf (مقدمة في الذكاء الاصطناعي)

*   **Q1: Fill-in-the-Blank:**
    *   **1- The ______________ tries to define what acting like a human means.** (Turing Test - صفحة 6)
    *   **2- An ______________ is anything that can be viewed as perceiving its environment through sensors and acting upon that environment through actuators.** (Agent - صفحة 3 من AI_agentsCh2.pdf، ولكن المفهوم الأساسي للوكيل يتم تقديمه في مقدمة الذكاء الاصطناعي أيضًا).
    *   **3- The ______________ maps from the set of all possible percept sequences P* to the set of actions A formulated as an abstract mathematical function.** (Agent function - صفحة 4 من AI_agentsCh2.pdf، ولكن هذا المفهوم أساسي لوكيل الذكاء الاصطناعي الذي يتم تقديمه في المحاضرة الأولى).
    *   **4- ______________ environment provides a fixed number of distinct percepts, actions, and environment states.** (Discrete - صفحة 18)
    *   **5- An agent operating by itself in an environment is called ______________.** (Single agent - صفحة 18)
    *   **6- Type of Agents:** (Simple reflex, Model-based reflex, Goal-based, Utility-based - صفحة 22 من AI_agentsCh2.pdf، ولكن هذا تصنيف أساسي لوكلاء الذكاء الاصطناعي).

*   **Q2: PEAS for Automated Taxi Driver:**
    *   هذا السؤال يختبر القدرة على تطبيق إطار عمل PEAS، والذي يتم شرحه بالتفصيل في المحاضرة الثانية (AI_agentsCh2.pdf، صفحة 13-14)، ولكنه يعتمد على فهم أساسيات الوكلاء من المحاضرة الأولى.

#### المحاضرة الثانية: AI_agentsCh2.pdf (وكلاء الذكاء الاصطناعي)

*   **Q1: Fill-in-the-Blank:**
    *   **2- An ______________ is anything that can be viewed as perceiving its environment through sensors and acting upon that environment through actuators.** (Agent - صفحة 3)
    *   **3- The ______________ maps from the set of all possible percept sequences P* to the set of actions A formulated as an abstract mathematical function.** (Agent function - صفحة 4)
    *   **6- Type of Agents:** (Simple reflex, Model-based reflex, Goal-based, Utility-based - صفحة 22)
    *   **7- Search problem components are:** (Initial state, Actions, Transition model, Goal state, Path cost - صفحة 5 من AI_searchCh3.pdf، ولكن هذا المفهوم قد يكون مقدمة لمشاكل البحث في سياق الوكلاء).
    *   **8- ______________ is the number of different states the agent and environment can be in. (State Space)** (صفحة 21)
    *   **9- In ______________ the search algorithm/agent is not provided information about how close a state is to the goal state.** (Uninformed Search - صفحة 28 من AI_searchCh3.pdf).
    *   **10- In informed search, the agent uses a ______________ to rank nodes in the frontier and select the most promising state in the frontier for expansion using a best-first search strategy.** (Heuristic function - غير موجودة في المحاضرات المرفقة، ولكنها مفهوم أساسي في البحث الموجه).

*   **Q2: PEAS for Automated Taxi Driver:**
    *   هذا السؤال هو تطبيق مباشر للمفاهيم المشروحة في هذه المحاضرة (صفحة 13-14).

#### المحاضرة الثالثة: AI_searchCh3.pdf (البحث في الذكاء الاصطناعي)

*   **Q1: Fill-in-the-Blank:**
    *   **7- Search problem components are:** (Initial state, Actions, Transition model, Goal state, Path cost - صفحة 5)
    *   **8- ______________ is the number of different states the agent and environment can be in. (State Space)** (صفحة 21)
    *   **9- In ______________ the search algorithm/agent is not provided information about how close a state is to the goal state.** (Uninformed Search - صفحة 28)
    *   **11- ______________ is an optimization technique that simulates the phenomenon of natural evolution.** (Genetic algorithm - غير موجودة في المحاضرات المرفقة، ولكنها خوارزمية بحث).
    *   **12- ______________ candidate solution to a problem often encoded as a bit string, floating-point variables or integers.** (Chromosome/Individual - غير موجودة في المحاضرات المرفقة، مرتبطة بالخوارزميات الجينية).
    *   **13- ______________ is a popular Machine Learning algorithm used mostly for solving classification problems.** (K-Nearest Neighbors - غير موجودة في المحاضرات المرفقة، ولكنها خوارزمية تعلم آلة).
    *   **14- ______________ can be used in the K-Nearest Neighbors Algorithm to calculate the distance from the new entry to other entries in the data set, its formula is ______________.** (Euclidean distance - غير موجودة في المحاضرات المرفقة، مرتبطة بـ KNN).

*   **Q3: Choose Two of the following questions and answer them:**
    *   **a) Explain how Iterative deepening search (IDS) works with an appropriate example, then explain its properties in terms of Completeness, Optimal, Time, Space and then write the algorithm or code for it.** (صفحة 44-47)
    *   **b) Explain how Genetic algorithm works and what is its applications with an appropriate example, then write the algorithm or code for it.** (غير موجودة في المحاضرات المرفقة).
    *   **c) Explain how Apriori algorithm works with an appropriate example, then write the algorithm or code for it.** (غير موجودة في المحاضرات المرفقة).
    *   **d) Explain what is K-Nearest Neighbors algorithm, and how it works and what is its applications with an appropriate example, then write the algorithm or code for it.** (غير موجودة في المحاضرات المرفقة).

### استنتاج حول نمط أسئلة الدكتور

من خلال تحليل ملف الاختبار والمحاضرات، يمكن استنتاج ما يلي حول نمط أسئلة الدكتور:

1.  **التركيز على المفاهيم الأساسية والتعاريف:** سؤال املأ الفراغ يوضح أن الدكتور يركز على فهم الطلاب للمصطلحات والتعاريف الأساسية في مجال الذكاء الاصطناعي، خاصة تلك المتعلقة بالوكلاء ومشاكل البحث.
2.  **القدرة على التطبيق العملي:** سؤال PEAS لسائق التاكسي الآلي يبرز أهمية قدرة الطالب على تطبيق الأطر النظرية على سيناريوهات واقعية.
3.  **الفهم العميق للخوارزميات:** أسئلة الشرح التفصيلي في Q3 تتطلب فهمًا عميقًا لكيفية عمل الخوارزميات (مثل IDS)، وخصائصها (الاكتمال، الأمثلية، التعقيد الزمني والمكاني)، والقدرة على شرحها بأمثلة وربما كتابة الكود.
4.  **تجاوز المحتوى المقدم:** لاحظت أن بعض الأسئلة في Q1 و Q3 (مثل Genetic Algorithm و Apriori و K-Nearest Neighbors) لا تتوافق بشكل مباشر مع المحاضرات الثلاث المرفقة. هذا يشير إلى أن الدكتور قد يعتمد على مصادر أخرى، أو أن هذه المحاضرات هي جزء من منهج أوسع، أو أنه يتوقع من الطلاب البحث عن هذه المفاهيم. هذا مهم جدًا لفهم 


نمط الدكتور. قد يكون هذا يعني أن الدكتور يتوقع من الطلاب البحث عن هذه المواضيع، أو أنها جزء من محاضرات أخرى لم يتم توفيرها، أو أنها معرفة عامة في المجال يتوقع من الطلاب إتقانها.

