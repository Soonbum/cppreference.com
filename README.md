# C/C++ 표준 연혁

* 참조 링크는 다음과 같습니다.
  1) [ISO C와 ISO C++의 차이](https://cinsk.github.io//iso-c-diff-iso-c++/index.html)
  2) [C/C++ Reference](https://en.cppreference.com/w/)

* C 표준: C89, C95, C99, C11, C17, C23
* C++ 표준: C++11, C++14, C++17, C++20, C++23, C++26

## C 표준

* Language
  - Basic concepts
    * Comments
    * ASCII chart
    * Character sets and encodings
    * Translation phases
    * Punctuation
    * Identifier - Scope - Lifetime
    * Lookup and Name Spaces
    * Type - Arithmetic types
    * Objects and Alignment
    * The main function
    * As-if rule
    * Undefined behavior
    * Memory model and Data races
  - Keywords
  - Preprocessor
    * #if - #ifdef - #ifndef - #elif
    * #elifdef - #elifndef(C23)
    * #define - # - ##
    * #include - #pragma
    * #line - #error
    * #warning(C23) - #embed(C23)
  - Expressions
    * Value categories
    * Evaluation order and sequencing
    * Constants and literals
      - Integer constants
      - Floating constants
      - Character constants
      - true/false(C23)
      - nullptr(C23)
      - String literals
      - Compound literals(C99)
    * Constant expressions
    * Implicit conversions
    * Operators
      - Member access and indirection
      - Logical - Comparison
      - Arithmetic - Assignment
      - Increment and Decrement
      - Call, Comma, Ternary
      - sizeof - _Alignof(C11)
      - Cast operators
    * Operator precedence
    * Generic selection(C11)
  - Declaration
    * Pointers - Arrays
    * Enumerations
    * Storage duration and Linkage
    * const - volatile - restrict(C99)
    * struct - union - Bit-fields
    * _Alignas(C11) - typedef
    * _Static_assert(C11)
    * Atomic types(C11)
    * External and tentative definitions
    * Attributes(C23)
  - Initialization
    * Scalar
    * Array
    * Structure/Union
  - Functions
    * Function declaration
    * Function definition
    * inline(C99)
    * _Noreturn(C11)(deprecated in C23)
    * Variadic arguments
  - Statements
    * if - switch
    * for
    * while - do-while
    * continue - break
    * goto - return

* Headers

* Type support

* Program utilities

* Variadic functions

* Diagnostics library

* Dynamic memory management

* Strings library
  - Null-terminated strings:
    * byte − multibyte − wide

* Algorithms library

* Numerics library
  - Common mathematical functions
  - Floating-point environment (C99)
  - Pseudo-random number generation
  - Complex number arithmetic (C99)
  - Type-generic math (C99)

* Date and time library

* Localization library

* Input/output library

* Concurrency support library (C11)

* Technical specifications
  - Dynamic memory extensions (dynamic memory TR)
  - Floating-point extensions, Part 1 (FP Ext 1 TS)
  - Floating-point extensions, Part 4 (FP Ext 4 TS)

## C++ 표준

* Language
  - Keywords − Preprocessor
  - ASCII chart
  - Basic concepts
    * Comments
    * Names (lookup)
    * Types (fundamental types)
    * The main function
  - Expressions
    * Value categories
    * Evaluation order
    * Operators (precedence)
    * Conversions − Literals
  - Statements
    * if − switch
    * for − range-for (C++11)
    * while − do-while
  - Declarations − Initialization
  - Functions − Overloading
  - Classes (unions)
  - Templates − Exceptions
  - Freestanding implementations

* Standard library (headers)

* Named requirements

* Feature test macros (C++20)

* Language support library
  - Program utilities
  - source_location (C++20)
  - Coroutine support (C++20)
  - Three-way comparison (C++20)
  - Type support
  - numeric_limits − type_info
  - initializer_list (C++11)
  - Concepts library (C++20)

* Diagnostics library
  - exception − System error
  - basic_stacktrace (C++23)

* Memory management library
  - unique_ptr (C++11)
  - shared_ptr (C++11)
  - weak_ptr (C++11)
  - Memory resources (C++17)
  - Allocators − Low level management

* Metaprogramming library (C++11)
  - Type traits − ratio
  - integer_sequence (C++14)

* General utilities library
  - Function objects − hash (C++11)
  - Swap − Type operations (C++11)
  - Integer comparison (C++20)
  - pair − tuple (C++11)
  - optional (C++17)
  - expected (C++23)
  - variant (C++17) − any (C++17)
  - String conversions (C++17)
  - Formatting (C++20)
  - bitset − Bit manipulation (C++20)
  - Debugging support (C++26)

* Strings library
  - basic_string − char_traits
  - basic_string_view (C++17)
  - Null-terminated strings:
    * byte − multibyte − wide

* Containers library
  - vector − deque − array (C++11)
  - list − forward_list (C++11)
  - map − multimap − set − multiset
  - unordered_map (C++11)
  - unordered_multimap (C++11)
  - unordered_set (C++11)
  - unordered_multiset (C++11)
  - Container adaptors
  - span (C++20) − mdspan (C++23)

* Iterators library

* Ranges library (C++20)

* Algorithms library
  - Execution policies (C++17)
  - Constrained algorithms (C++20)

* Numerics library
  - Common math functions
  - Mathematical special functions (C++17)
  - Mathematical constants (C++20)
  - Basic linear algebra algorithms (C++26)
  - Numeric algorithms
  - Pseudo-random number generation
  - Floating-point environment (C++11)
  - complex − valarray

* Date and time library
  - Calendar (C++20) − Time zone (C++20)

* Localization library
  - locale − Character classification
  - text_encoding (C++26)

* Input/output library
  - Print functions (C++23)
  - Stream-based I/O − I/O manipulators
  - basic_istream − basic_ostream
  - Synchronized output (C++20)
  - File systems (C++17)

* Regular expressions library (C++11)
  - basic_regex − Algorithms
  - Default regular expression grammar

* Concurrency support library (C++11)
  - thread − jthread (C++20)
  - atomic − atomic_flag
  - atomic_ref (C++20) − memory_order
  - Mutual exclusion − Semaphores (C++20)
  - Condition variables − Futures
  - latch (C++20) − barrier (C++20)
  - Safe Reclamation (C++26)

* Technical specifications
  - Standard library extensions (library fundamentals TS)
    * resource_adaptor − invocation_type
  - Standard library extensions v2 (library fundamentals TS v2)
    * propagate_const − ostream_joiner − randint
    * observer_ptr − Detection idiom
  - Standard library extensions v3 (library fundamentals TS v3)
    * scope_exit − scope_fail − scope_success − unique_resource
  - Parallelism library extensions v2 (parallelism TS v2)
    * simd
  - Concurrency library extensions (concurrency TS)
  - Transactional Memory (TM TS)
  - Reflection (reflection TS)
