```mermaid
graph TD
    %% Styling
    classDef main fill:#ffd43b,stroke:#333,stroke-width:2px,color:#000;
    classDef sub fill:#ffe873,stroke:#333,stroke-width:1px,color:#000;
    classDef leaf fill:#fff,stroke:#646464,stroke-width:1px,color:#000;

    Python[Python Roadmap] ::: main

    %% Learn the Basics
    Python --> Basics[Learn the Basics] ::: main
    Basics --> B1[Basic Syntax] ::: leaf
    Basics --> B2[Variables & Data Types] ::: leaf
    Basics --> B3[Conditionals & Loops] ::: leaf
    Basics --> B4[Type Casting & Exceptions] ::: leaf
    Basics --> B5[Functions & Built-ins] ::: leaf
    Basics --> B6[Data Structures: Lists, Tuples, Sets, Dicts] ::: leaf

    %% Data Structures & Algorithms
    Python --> DSA[Data Structures & Algorithms] ::: main
    DSA --> DSA1[Arrays & Linked Lists] ::: leaf
    DSA --> DSA2[Hash Tables] ::: leaf
    DSA --> DSA3[Heaps, Stacks, & Queues] ::: leaf
    DSA --> DSA4[Binary Search Trees] ::: leaf
    DSA --> DSA5[Recursion & Sorting Algorithms] ::: leaf

    %% Modules & Advanced Concepts
    Python --> Modules[Modules & Advanced Concepts] ::: main
    Modules --> M1[Built-in & Custom Modules] ::: leaf
    Modules --> M2[Lambdas & Decorators] ::: leaf
    Modules --> M3[Iterators & Regular Expressions] ::: leaf
    Modules --> M4[List & Generator Expressions] ::: leaf
    Modules --> M5[Context Managers] ::: leaf

    %% Object Oriented Programming
    Python --> OOP[Object Oriented Programming] ::: main
    OOP --> O1[Classes & Inheritance] ::: leaf
    OOP --> O2[Dunder / Magic Methods] ::: leaf

    %% Package Managers & Environments
    Python --> PKG[Package Management & Environments] ::: main
    PKG --> P1[Managers: Pip, PyPI, Conda, Poetry, uv] ::: leaf
    PKG --> P2[Environments: Virtualenv, Pipenv, Pyenv] ::: leaf
    PKG --> P3[Configuration: pyproject.toml] ::: leaf

    %% Concurrency
    Python --> Concurrency[Concurrency] ::: main
    Concurrency --> C1[Multiprocessing & Threading] ::: leaf
    Concurrency --> C2[Asynchrony & GIL] ::: leaf

    %% Advanced Typing & Code Quality
    Python --> Quality[Type System & Code Quality] ::: main
    Quality --> Q1[Static Typing: typing, mypy, pyright, pyre, Pydantic] ::: leaf
    Quality --> Q2[Formatting: black, ruff, yapf] ::: leaf

    %% Frameworks
    Python --> Frameworks[Web Frameworks] ::: main
    Frameworks --> F1[Synchronous: Pyramid, Plotly Dash] ::: leaf
    Frameworks --> F2[Asynchronous: Tornado, Sanic, gevent, aiohttp] ::: leaf
    Frameworks --> F3[Hybrid: FastAPI, Django, Flask] ::: leaf

    %% Testing & Documentation
    Python --> Tooling[Testing & Documentation] ::: main
    Tooling --> T1[Testing: unittest, pytest, doctest, tox, nose] ::: leaf
    Tooling --> T2[Documentation: Sphinx] ::: leaf
