# learning_resources
Books, courses and web sites on technical topics like machine learning and software engineering.

### Legend

:blue_book: - Book

:tv: - Video Course

:memo: - Online Course or Exercises

:hammer: - Tool

:file_folder: - Code Repository

## Math

* General
    * :memo: [Math Academy](https://mathacademy.com)
    Amazing online resource for learning math from grade school up through multivariable calculus. Also
    includes a course on Math for Machine Learning. Small lessons and spaced repetition makes learning faster
    and easier than using a textbook.
    * :tv: [3Blue1Brown](https://www.youtube.com/@3blue1brown) Wonderful channel of math explainer videos.
    The series on Calculus and Linear Algebra make some of the most confusing concepts make intuitive sense.

* Game Theory - I got interested in this after listening to the NY Times article
["How A.I. Conquered Poker"](https://www.nytimes.com/2022/01/18/magazine/ai-technology-poker.html) on Audm.
    * :memo: [Game Theory with Python](https://www.coursera.org/projects/game-theory-with-python) - Coursera course teaching the basics of game theory using Python.
    * :blue_book: [Game Theory: A Non-Technical Introduction](https://store.doverpublications.com/0486296725.html) by Morton D. Davis - Seems like the best introductory book on the subject.
* Linear Algebra
    * :blue_book: [Linear Algebra Done Right](https://linear.axler.net/) by Sheldon Axler. Widely recommended text
    for learning linear algebra. Free online PDF is available from the publisher in addition to a print edition.
* Math for Machine Learning
    * :memo: [Introduction to Flow Matching and Diffusion Models](https://diffusion.csail.mit.edu/)
    Short online course from MIT on the math behind diffusion models.
* Tools
    * :hammer: [Desmos Graphing Calculator](https://www.desmos.com/calculator) Helpful tool to visualize formulas.

## Statistics

* Bayesian
    * :blue_book: [Bayesian Modeling and Computation in Python](https://bayesiancomputationbook.com/welcome.html) This online and print book
    focuses on using Python to do Bayesian modeling. It's a welcome change from all of the Bayesian books in R, JAGS and other
    non-general purpose languages. The other Bayesian book in Python,
    * :blue_book: [Bayesian Methods for Hackers](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers)
    didn't impress me so it's nice to have an alternative.
    * :blue_book: [Statistical Rethinking](https://xcelab.net/rm/) by Richard McElreath
    Popular book for learning Bayesian statistics. More technical and requires a strong math background. There
    are [free YouTube lectures](https://github.com/rmcelreath/stat_rethinking_2024?tab=readme-ov-file) from the author that cover the content of the book as well.


* Causal Inference
    * :blue_book: [Causal Inference: The Mixtape](https://mixtape.scunning.com/) by Scott Cunningham
    This online and print book is an intuitive and highly-readable introduction to causal inference. It provides
    examples in R and Stata.
    * :blue_book: [Causal Inference: What If](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/)
    by Miguel Hernan and Jamie Robins. Book on causal inference by two professors at the Harvard School
    of Public Health. Brings together information that was previously scattered across many journals
    and disciplines into a single resource.
    * :blue_book: [The Effect](https://theeffectbook.net/)
    by Nick Huntington-Klein. The Effect is a book intended to introduce students (and non-students)
    to the concepts of research design and causality in the context of observational data. The book
    is written in an intuitive and approachable way and doesn’t overload on technical detail. I heard about this book on the [Practical AI podcast](https://changelog.com/practicalai/220).
    * :blue_book: [Causal Inference and Discovery in Python](https://www.packtpub.com/en-us/product/causal-inference-and-discovery-in-python-9781804612989)
    by Aleksander Molak
        - Examine Pearlian causal concepts such as structural causal models, interventions, counterfactuals, and more
        - Discover modern causal inference techniques for average and heterogenous treatment effect estimation
        - Explore and leverage traditional and modern causal discovery methods
    * :blue_book: [Causal Inference in Python](https://www.oreilly.com/library/view/causal-inference-in/9781098140243/) by Matheus Facure
    In this book, author Matheus Facure, senior data scientist at Nubank, explains the largely untapped potential of causal inference for estimating impacts and effects.

## Systems Thinking

* :blue_book: [Thinking in Systems](https://www.chelseagreen.com/product/thinking-in-systems/) by Donella Meadows
Classic book on how to use systems thinking to understand and improve systems.

## Artificial Intelligence

* Models
    * :blue_book: [State of Open Source AI Book](https://book.premai.io/state-of-open-source-ai/)
    Covers all the most important categories in the Open Source AI space, from model evaluations to deployment.

## Data Science

* Introductory
    * :blue_book: [An Introduction to Statistical Learning](https://www.statlearning.com/)
    The foundational book for machine learning. There is a second edition out that includes deep learning.

* Data Wrangling
    * :hammer: [Pandas Tutor](https://pandastutor.com/)
    Shows a visual representation of Pandas data manipulation code.
    * :file_folder: [Tensor Puzzles](https://github.com/srush/Tensor-Puzzles)
    Set of brain teasers to help learn programming for multidimensional arrays.
    * :blue_book: [Pandas Workout](https://www.manning.com/books/pandas-workout) by Reuven Lerner
    Work out your pandas skills against dozens of real-world challenges, each carefully designed to build an
    intuitive knowledge of essential pandas tasks.
    * [Pandas Illustrated: The Definitive Visual Guide to Pandas](https://medium.com/better-programming/pandas-illustrated-the-definitive-visual-guide-to-pandas-c31fa921a43) by Lev Maximov
    Illustrated article that explains all the most important concepts and operations in Pandas.

* Machine Learning
    * :blue_book: [Machine Learning with Pytorch and Scikit Learn](
        https://sebastianraschka.com/books/#machine-learning-with-pytorch-and-scikit-learn)
    by Sebastian Raschka. I read the first edition of this book back in the day and it was
    a wonderful introduction to using Python for Data Science. Sebastian is on the fourth
    edition as of 2022 and I'm sure the material is better than ever.
    * :blue_book: [Interpretable Machine Learning](https://christophm.github.io/interpretable-ml-book/)
    by Christoph Molnar. We used the SHAP section of this book to discuss interpretable
    methods at work. The rest of the book looks fantastic as well.
    * Machine Learning Design Interview [book](https://www.amazon.com/Machine-Learning-Design-Interview-System/dp/B09YQWX59Z/) and [online course](https://www.educative.io/courses/machine-learning-system-design)
    by [Khang Pham](https://mlengineer.io/) Bridges the gaps between Machine Learning “book” knowledge and Machine Learning in production. It’s very easy to find resources about certain Machine Learning techniques but there is a lack of resources that explain how these techniques are used at big companies at scale.  
    * [Altdeep](https://altdeep.ai/) Online courses in causal machine learning with deep
    neural networks. Created by Robert Osazuma Ness, a researcher at Microsoft Research.
    * :blue_book: [Causal AI](https://www.manning.com/books/causal-ai) A code-first introduction to
    building machine learning and deep learning models that implement causal reasoning. 
    * :memo: [Introduction to Data-Centric AI](https://dcai.csail.mit.edu/)
    Online MIT course that teaches about Data-Centric AI (DCAI). DCAI is an emerging science that studies techniques
    to improve datasets, which is often the best way to improve performance in practical ML applications.

* Recommender Systems
    * :blue_book: [Practical Recommender Systems](https://www.manning.com/books/practical-recommender-systems) by Kim Falk
    This book explains how recommender systems work and shows how to create and apply them for your
    site. After covering the basics, you’ll see how to collect user data and produce personalized recommendations. 
    * :blue_book: [Building Recommendation Systems in Python and JAX](https://www.oreilly.com/library/view/building-recommendation-systems/9781492097983/) by Bryan Bischof and Hector Yee
    In this practical book, the authors illustrate the core concepts and examples to help you create a RecSys for any industry or scale. You'll learn the math, ideas, and implementation details you need to succeed.
    * :memo: [Recommender Systems Specialization](https://www.coursera.org/specializations/recommender-systems#outcomes)
    This five-module Coursera specialization teaches all the main ideas behind recommender systems.
    The courses offer interactive, spreadsheet-based exercises to master different algorithms, along with an honors
    track where you can go into greater depth using the LensKit open source toolkit. 

* Deep Learning
    * [Grokking Deep Learning](https://www.manning.com/books/grokking-deep-learning) by Andrew W. Trask
    Plain English explanations of the fundamentals of how neural networks work.

    * [fast.ai](https://www.fast.ai/) Courses for anyone to learn how to use neural networks. The courses can
    be used even if you haven't done anything with ML before.

    * :memo: [aiquizzes](https://aiquizzes.com/)
    Quizzes and learning modules that support the fast.ai course.

    * [Neural Networks explainer videos](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)
    from 3Brown1Blue. These videos give an intuitive understanding of how neural networks work.

    * [What Are Embeddings?](https://vickiboykis.com/what_are_embeddings/)
    A deep dive into embeddings by the inimitable Vicki Boykis.

* Natural Language Processing
    * [ChatGPT Prompt Engineering for Developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/)
    from DeepLearning.AI and Andrew Ng. Learn how to use a large language model (LLM) to quickly build new and powerful applications.
    * [Natural Langage Processing with Transformers](
        https://www.oreilly.com/library/view/natural-language-processing/9781098103231/)
    by Lewis Tunstall, Leandro von Werra, and Thomas Wolf. NLP book by the Hugging Face crew. Discusses using
    transformers for NLP tasks and more.
    *  [Hugging Face Course](https://huggingface.co/course/chapter1/1)
    Free online course by the team that has done a ton of breakthrough work in NLP. Teaches you to use
    transformers to do text processing.

* Large Language Models
    * :tv: [An Open Course on LLMs, Led by Practitioners](https://hamel.dev/blog/posts/course/)
    A free survey course on LLMs, taught by practitioners. A set of workshops and talks from practitioners on topics
    like evals, retrieval-augmented-generation (RAG), fine-tuning and more.
    * :blue_book: [Build a Large Language Model (From Scratch)](https://www.manning.com/books/build-a-large-language-model-from-scratch) by Sebastian Raschka
    Step-by-step guide to building an GPT-style LLM similar from the ground up using Python and Pytorch.
    * :memo: [DeepLearning.AI](https://www.deeplearning.ai/)
    Andrew Ng's education site with a wide range of courses on deep learning, generative AI and more.

* ML System Design
    * [CS 329S: Machine Learning Systems Design](https://stanford-cs329s.github.io/syllabus.html) Slides and notes from
    Chip Huyen's Stanford course on building production ML systems.
    * [Chip Huyen's Blog](https://huyenchip.com/blog/)
    Blog posts about a variety of practical ML and AI system design topics.
    * [Designing Machine Learning Systems](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/)
    Book on designing ML systems also from Chip Huyen.

* Data Visualization
    * :blue_book: [Storytelling with Data](https://www.storytellingwithdata.com/) Great blog and books about
    data visualization. Cole Nussbaumer Knaflic has created some amazing resources for learning how
    to communicate data visually.
    * :blue_book: [Dashboard Design Patterns](https://dashboarddesignpatterns.github.io/)
    This page lists design patterns for dashboard design collected to support the design and creative exploration of dashboard design.

## Data Systems

* Data Modeling
    * [Data Modeling Made Simple](https://technicspub.com/data-modeling-made-simple/) by Steve Hoberman.
    Get a straight-forward introduction to modeling relational data from one of the OGs in the field.
    * [Object-Role Modeling Fundamentals](https://technicspub.com/object-role-modeling-fundamentals/) by Terry Halpin.
    Gentle introduction to the most powerful data modeling method. ORM is a theoretically-sound way to build
    data models that match relationships in the real world.
    * [Information Modeling and Relational Databases - Second Edition](
        https://www.elsevier.com/books/information-modeling-and-relational-databases/halpin/978-0-12-373568-3
    ) by Terry Halpin and Tony Morgan. This is a large textbook that covers much more about ORM than Terry's
    introductory book. This is the bible of relational data modeling.

* Data Engineering
    * :blue_book: [Fundamentals of Data Engineering](https://www.oreilly.com/library/view/fundamentals-of-data/9781098108298/) by Joe Reis and Matt Housley
    This book walks you through the data engineering lifecycle and show you how to stitch together a variety of cloud
    technologies to serve the needs of downstream data consumers. You'll understand how to apply the concepts of data
    generation, ingestion, orchestration, transformation, storage, and governance that are critical in any data
    environment regardless of the underlying technology.

## Software Engineering

* General
    * :blue_book: [Code: The Hidden Language of Computer Hardware and Software](
        https://www.microsoftpressstore.com/store/code-the-hidden-language-of-computer-hardware-and-software-9780137909100) by Charles Petzold.
    I read the first edition of this clearly written introduction to computer fundamentals years ago
    and loved it. There's now a second edition out that looks even better.

* Software Architecture
    * [Software Architecture: The Hard Parts](https://www.oreilly.com/library/view/software-architecture-the/9781492086888/)
    This looks like a good book. "Architecture veterans and practicing consultants Neal Ford, Mark Richards, Pramod Sadalage,
    and Zhamak Dehghani discuss strategies for choosing an appropriate architecture."
    * [Strategic Monoliths and Microservices: Driving Innovation Using Purposeful Architecture](
        https://www.oreilly.com/library/view/strategic-monoliths-and/9780137355600/)
    Heard a [Software Engineering Radio episode](
        https://www.se-radio.net/2022/01/episode-495-vaughn-vernon-on-strategic-monoliths-and-microservices/
    ) with the author of this book. The book recommends making architectural decisions that correspond to the
    strategic direction of business.
    * [Understanding Distributed Systems](https://understandingdistributed.systems/) by Roberto Vitillo
    Recommended as a great first book to learn about distributed systems by Engineering with Utsav and
    Gergely Orosz.
    * [Microservice Architecture](https://microservices.io/index.html) is a web site from Chris Richardson
    which documents microservice patterns. He also has a [book](https://www.manning.com/books/microservices-patterns)
    on the same topic.
    * [Cloud Design Patterns](https://learn.microsoft.com/en-us/azure/architecture/patterns/) A set of design patterns
    that are useful for building reliable, scalable, secure applications in the cloud. They were compiled by the Microsoft
    Azure team, but the descriptions are platform agnostic.
    * [Event Sourcing in Python](https://leanpub.com/eventsourcinginpython)
    by John Bywater. A book on how to do event sourcing using the Python [`eventsourcing`](
        https://eventsourcing.readthedocs.io/en/stable/
    ) package.
    * :blue_book: [Balancing Coupling in Software Design](https://www.oreilly.com/library/view/balancing-coupling-in/9780137353514/)
    by Vlad Khonopov. I heard the [author talk about this book on the Add Dot podcast](https://adddot.io/podcast/s2e2/). He had some great
    points about how some coupling in necessary in software systems, but unnecessary coupling can make
    systems brittle and unmaintainable.
    * :blue_book: [Designing Data-Intensive Applications](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/) by Martin Kleppmann
    The go-to book for learning how to design robust distributed systems.
    * [Event Modeling](https://eventmodeling.org/)
    Event Modeling is a method of describing systems using an example of how information has changed within them
    over time. Event Modeling specifically omits transient details and looks at what the information flow is and
    what the user sees at any particular point in time.

* Coding
    * :tv: [Destroy All Software](https://www.destroyallsoftware.com/screencasts)
    Screencasts by Gary Bernhardt explaining basic theoretical computer science concepts as well as
    implementing systems like compilers, web servers etc. Also includes Execute Program which is
    a learning environment using code examples to teach engineering skills.
    * :blue_book: [Wizard Zines](https://wizardzines.com/) by Julia Evans
    Easy to digest zines on particular topics like DNS, debugging, etc. Julia makes highly technical material
    both easy to learn and dare I say fun?
    * :blue_book: [Tidy First?](https://www.oreilly.com/library/view/tidy-first/9781098151232/) by Kent Beck
    Recommends first cleaning up any legacy codebase before trying to modernize it. The book is
    [highly recommended](https://newsletter.pragmaticengineer.com/p/dead-code-getting-untangled-and-coupling)
    by Gergely Orosz.
    * :blue_book: [Crafting Interpreters](https://craftinginterpreters.com/) by Robert Nystrom
    Ever wanted to make your own programming language or wondered how they are designed and built? If so, this book is for you.
    * :blue_book: [Refactoring](https://martinfowler.com/books/refactoring.html) by Martin Fowler
    One of the all time classics of software engineering. This book describes the process of refactoring and
    spends most of its time explaining how to do the various refactorings.

* Data Structures and Algorithms
    * See the Career - Interviewing section for more resources
    * :blue_book: [A Common Sense Guide to Data Structures and Algorithms](https://pragprog.com/titles/jwdsal2/a-common-sense-guide-to-data-structures-and-algorithms-second-edition/)
    This is a great book to learn data structures and algorithms. The author has taught a live course on the subject many times
    and has distilled his learning down to this book. The explanations are clear and well illustrated. I highly recommend
    this book.

* Legacy Systems
    * :blue_book: [Kill It with Fire](https://nostarch.com/kill-it-fire) by Marianne Bellotti
    This book is recommended by the hosts of the Staff Eng podcast. It discusses how to smartly refactor legacy systems
    without giving in to the knee-jerk reaction to rebuild from scratch.

* Python
    * :blue_book: [Fluent Python](https://www.oreilly.com/library/view/fluent-python-2nd/9781492056348/) by Luciano Ramalho
    This is one of the most highly rated books for how to take your Python from beginner to advanced. Teaches you how to
    write idiomatic Python. The second edition was released in 2022.
    * :blue_book: [Powerful Python](https://powerfulpython.com/book/) by Aaron Maxwell. This book is the perfect resource
    to take you from beginning to intermediate Python.
    * :tv: [Talk Python Training](https://training.talkpython.fm/) Short video courses on a variety of
    Python related topics. The courses are taught by Michael Kennedy, the host of the Talk Python to
    me podcast, and his associates. Includes courses on mongodb, async programming, FastAPI and more.
    * :blue_book: [Modeling and Simulation in Python](https://greenteapress.com/wp/modsimpy/) by Allen Downey
    I heard about this book on an episode of [Talk Python to Me](https://talkpython.fm/episodes/show/423/solving-10-different-simulation-problems-with-python).
    It covers simulating a variety of real-world processes like population growth, infectious diseases
    and so forth. It's by the same author as Think Bayes, Think Python, etc. There's also a [free ebook](https://allendowney.github.io/ModSimPy/)
    version with Google Colab notebooks.
    * :blue_book: [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/) by Al Sweigart
    If you've ever spent hours renaming files or updating hundreds of spreadsheet cells, you know how tedious tasks like these can be.
    But what if you could have your computer do them for you? In Automate the Boring Stuff with Python, you'll learn how to use Python
    to write programs that do in minutes what would take you hours to do by hand - no prior programming experience required. 
    * :tv: [pyvideo](https://pyvideo.org/?__s=sk9lg7kgoijummpeuqlj)
    Compilation of recorded presentations from PyCon, PyData and many other Python events.

* JavaScript
    * :memo: [Scrimba](https://scrimba.com/) Online courses for learning HTML, CSS, JavaScript and React.
    The courses provide an online development environment and are well constructed. I wrote a
    [review of the HTML and CSS course](https://medium.com/p/d493a8312c3f).
    * :blue_book: [Elequent JavaScript](https://eloquentjavascript.net/) by Marijn Haverbeke. Highly recommended
    book for beginners to learn JavaScript. Book content is published online as well as print.

* Networking
    * [The Bits and Bytes of Computer Networking](https://www.coursera.org/learn/computer-networking)
    This course from Google is a recommended way to learn the basics of networking. It has over 30k
    5 star reviews on Coursera.

* Tools
    * :tv: [Vimcasts](http://vimcasts.org/)
    Videos, courses and books for improving your `vim` skills.

## Infrastructure

* DevOps
    * :blue_book: [The Phoenix Project](https://itrevolution.com/the-phoenix-project/)
    This is a book about the DevOps revolution written in narrative form. It is highly recommended by
    [Josh Sheppard](https://www.linkedin.com/in/joshua-sheppard/), my group manager at C.H. Robinson.
* Cloud 
    * [A Cloud Guru](https://acloudguru.com/)
    Great online courses to study for cloud certifications. I used their course to get my
    AWS Cloud Practitioner certificate and had a good experience.
* Systems
    * :blue_book: [Operating Systems: Three Easy Pieces](https://pages.cs.wisc.edu/~remzi/OSTEP/) by Remzi H. Arpaci-Dusseau and Andrea C. Arpaci-Dusseau
    OSTEP ("oh step"), or the "the comet book", represents the culmination of years of teaching intro to operating systems to both undergraduates and graduates at the University of Wisconsin-Madison Computer Sciences department for nearly 25 years.The book is organized around three concepts fundamental to OS construction: virtualization (of CPU and memory), concurrency (locks and condition variables), and persistence (disks, RAIDS, and file systems).

## Product Management

* :blue_book: [Inspired](https://www.svpg.com/books/inspired-how-to-create-tech-products-customers-love-2nd-edition/)
  by Marty Cagan. This is a great overview of best practices in product management from the founder of
  the Silicon Valley Product Group.

## Technology

* Commentary
    * [Logic](https://logicmag.io/) This magazine does deep dives into how society is affected by
    technology and vice versa. The articles contain insightful takes on a wide variety of
    technology topics.
    * [Technology Review](https://www.technologyreview.com/) This online and print magazine from
    MIT follows the most important technology trends from many fields.

## Writing and Documentation

* From [The Pragmatic Engineer Newsletter](https://newsletter.pragmaticengineer.com/)
    * [The Writing Well Handbook](https://www.julian.com/guide/write/intro) by Julian Shapiro.
    An e-book for writing nonfiction blogs and books.
    * [Technical Writing Courses by Google](https://developers.google.com/tech-writing)
    A collection of courses and learning resources to improve writing technical documentation.
    * [The Craft of Writing Effectively](https://www.youtube.com/watch?v=vtIzMaLkCaM)
    An hour and a half video from Leadership Lab. One of the best talks about technical writing.
    * [On Writing Well](https://www.harpercollins.com/products/on-writing-well-william-zinsser?variant=32118081159202) by Willian Zinsser.
    The classic guide to writing nonfiction. The book that helped me write more concisely.
* [Docs for Developers](https://docsfordevelopers.com/) How to write documentation by a group
    of technical writers from Waymo and Stripe. This [Stack Overflow podcast](
        https://stackoverflow.blog/2022/06/21/an-engineers-field-guide-to-great-technical-writing-ep-455/
    )
    has a great interview with the authors.

## Product Management

* :memo: [AI Product Management Bootcamp](https://maven.com/marily-nika/ai-pm-bootcamp)
    This program offers a comprehensive package comprising 25 hours of live content & 6 practical hands-on exercises encompassing both technical and strategic aspects.

## Leadership

* Technical Leadership
    * [Staff Eng Podcast](https://podcast.staffeng.com/)
    Interviews with Staff-plus engineers from a variety of big tech companies. Sadly, this podcast
    is no longer being produced.
    * :blue_book: [The Staff Engineer's Path](https://www.oreilly.com/library/view/the-staff-engineers/9781098118723/) by Tanya Reilly
    The staff engineer's path allows engineers to contribute at a high level as role models, driving big projects, determining technical strategy, and raising everyone's skills.
    This in-depth book shows you how to understand your role, manage your time, master strategic thinking, and set the standard for technical work. You'll read about how to be a
    leader without direct authority, how to plan ahead to make the right technical decisions, and how to make everyone around you better, while still growing as an expert in your domain.

* Management
    * :blue_book: [High Output Management](https://penguinrandomhousehighereducation.com/book/?isbn=9780679762881)
    This book is recommended by one of the hosts of the Staff Eng podcast. It contains a section
    about "Know How Managers" who are more technical leaders than people managers.
    * :blue_book: [Engineering Management for the Rest of Us](https://www.engmanagement.dev/) by Sarah Drasner.
    Heard an [interview with Sarah about the book](https://changelog.com/podcast/540)
    on the Changelog podcast. She has more than 10 years of experience in Engineering Management at all levels,
    from Lead to VP at Netlify, Microsoft and Trulia/Zillow Group.
    * :blue_book: [The Manager's Path](https://www.oreilly.com/library/view/the-managers-path/9781491973882/) by Camille Fournier.
    Considered the definitive guide on navigating a management career path in tech.

## Career

* Career Development
    * [Timeless Career Advice for Software Engineers](https://lbacaj.gumroad.com/l/career-advice-for-engineers) by Louie Bacaj
    Advice on navigating the career ladder by someone who was the youngest Senior Director ever in Walmart Engineering.
    * :blue_book: [The Software Enginer's Guidebook](https://www.engguidebook.com/) by Gergely Orosz
    An excellent book to help you navigate your career from junior developer up through staff engineer. Talks about
    all aspects of professional engineering and provides practical guidance on how to succeed.

* Job Search
    * [The Standout Developer](https://www.thestandoutdeveloper.com/job-hunting) by Randall Kanna
    Learn how to ace the interview, get companies reaching out to you, build a standout resume and more.

* Interviewing
    * [Cracking the Coding Interview](https://www.crackingthecodinginterview.com/)
    The original book that started the craze of technical interview resources. Has over 150 practice questions as well
    as advice for the interviewing process.
    * [Blind 75](https://www.teamblind.com/post/New-Year-Gift---Curated-List-of-Top-100-LeetCode-Questions-to-Save-Your-Time-OaM1orEU)
    The classic list of LeetCode questions to focus on for coding interviews. Compiled by a Facebook engineer, the list went
    viral and is now referenced everywhere.
    * [Tech Interview Handbook](https://www.techinterviewhandbook.org/)
    Free online book for how to prepare for tech interiews. One of the authors of this book is the
    creator of the famous Blind 75 list of LeetCode problems. Includes a refinement of the Blind 75 down to 50 questions.
    * [Grokking the Coding Interview: Patterns for Coding Questions](https://www.educative.io/courses/grokking-the-coding-interview)
    Online course created by FAANG engineers to help learn the typical patterns that appear in coding questions and how
    to solve them.
    * [14 Patterns to Ace Any Coding Interview Question](https://hackernoon.com/14-patterns-to-ace-any-coding-interview-question-c5bb3357f6ed)
    Blog post written by one of the creators of "Grokking the Coding Interview". Gives a quick overview of the patterns that you'll
    learn in that course.
    * [LeetCode Patterns](https://seanprashad.com/leetcode-patterns/)
    Filterable list of LeetCode problems to practice different data structures and algorithms patterns.
    * [NeetCode](https://www.youtube.com/c/NeetCode)
    YouTube channel that explains the solutions to LeetCode problems. The explanations are clear and include
    both a theory and coding portion.
    * [Interview Query](https://www.interviewquery.com/)
    Practice interview questions for data analysis, business intelligence and machine learning interviews.
    Based on questions from hundreds of tech companies.
    * [Machine Learning Interviews](https://huyenchip.com/ml-interviews-book/) Online book by the one-and-only
    Chip Huyen about how to prepare for ML Engineer interviews.
    * :memo: [Design Gurus](https://www.designgurus.io/)
    Online prep courses for system design and coding interviews.
    * :blue_book: [Data Science Interview Book](https://book.thedatascienceinterviewproject.com/)
    Study material and questions to prepare for data science interviews.
    * [Pragmatic Engineer Interview Resources](https://blog.pragmaticengineer.com/preparing-for-the-systems-design-and-coding-interviews/)
    List of system design and coding interview resources from the author of the Pragmatic Engineer newsletter.
    * :memo: [interviewing.io Guides](https://interviewing.io/learn#interview-guides)
    Guides on for FAANG interviews, how to pass the system design interview and more.
