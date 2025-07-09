# Everything
An object oriented hierarchy representing everything.

## Goal
The goal is to make a beautiful, but as simple as possible hierarchy of packages, modules and classes that represents everything that exists.

## Implemeentation
1. The code must be runnable.
2. Any canon class must use a bare `@dataclass` decorator for simplicity's sake.
3. Anything non-canon must be inside a package called `_` inside the package it best fits into. If anything is globally needed, it should be put into `_` in the root directory. The only exception to this rule is this `README.md` file.
4. There are many ways to group items into packages, but only one way can actually be implemented. See how other parts of the codebase do this and use a fitting approach.
5. No external dependencies.
