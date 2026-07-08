```mermaid
graph TD
    Python[Python Roadmap]

    %% Learn the Basics
    Python --> Basics[Learn the Basics]
    Basics --> B1[Basic Syntax]
    Basics --> B2[Variables & Data Types]
    Basics --> B3[Conditionals & Loops]
    Basics --> B4[Type Casting & Exceptions]
    Basics --> B5[Functions & Built-ins]
    Basics --> B6[Data Structures: Lists, Tuples, Sets, Dicts]

    %% Data Structures & Algorithms
    Python --> DSA[Data Structures & Algorithms]
    DSA --> DSA1[Arrays & Linked Lists]
    DSA --> DSA2[Hash Tables]
    DSA --> DSA3[Heaps, Stacks, & Queues]
    DSA --> DSA4[Binary Search Trees]
    DSA --> DSA5[Recursion & Sorting Algorithms]

    %% Modules & Advanced Concepts
    Python --> Modules[Modules & Advanced Concepts]
    Modules --> M1[Built-in & Custom Modules]
    Modules --> M2[Lambdas & Decorators]
    Modules --> M3[Iterators & Regular Expressions]
    Modules --> M4[List & Generator Expressions]
    Modules --> M5[Context Managers]

    %% Object Oriented Programming
    Python --> OOP[Object Oriented Programming]
    OOP --> O1[Classes & Inheritance]
    OOP --> O2[Dunder / Magic Methods]

    %% Package Managers & Environments
    Python --> PKG[Package Management & Environments]
    PKG --> P1[Managers: Pip, PyPI, Conda, Poetry, uv]
    PKG --> P2[Environments: Virtualenv, Pipenv, Pyenv]
    PKG --> P3[Configuration: pyproject.toml]

    %% Concurrency
    Python --> Concurrency[Concurrency]
    Concurrency --> C1[Multiprocessing & Threading]
    Concurrency --> C2[Asynchrony & GIL]

    %% Advanced Typing & Code Quality
    Python --> Quality[Type System & Code Quality]
    Quality --> Q1[Static Typing: typing, mypy, pyright, pyre, Pydantic]
    Quality --> Q2[Formatting: black, ruff, yapf]

    %% Frameworks
    Python --> Frameworks[Web Frameworks]
    Frameworks --> F1[Synchronous: Pyramid, Plotly Dash]
    Frameworks --> F2[Asynchronous: Tornado, Sanic, gevent, aiohttp]
    Frameworks --> F3[Hybrid: FastAPI, Django, Flask]

    %% Testing & Documentation
    Python --> Tooling[Testing & Documentation]
    Tooling --> T1[Testing: unittest, pytest, doctest, tox, nose]
    Tooling --> T2[Documentation: Sphinx]

    %% Styling Definitions
    classDef main fill:#ffd43b,stroke:#333,stroke-width:2px,color:#000;
    classDef sub fill:#ffe873,stroke:#333,stroke-width:1px,color:#000;
    classDef leaf fill:#fff,stroke:#646464,stroke-width:1px,color:#000;

    %% Apply Styles
    class Python,Basics,DSA,Modules,OOP,PKG,Concurrency,Quality,Frameworks,Tooling main;
    class B1,B2,B3,B4,B5,B6,DSA1,DSA2,DSA3,DSA4,DSA5,M1,M2,M3,M4,M5,O1,O2,P1,P2,P3,C1,C2,Q1,Q2,F1,F2,F3,T1,T2 leaf;
