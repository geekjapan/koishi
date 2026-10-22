# Graph Report - koishi  (2026-10-23)

## Corpus Check
- 65 semantic source files; AST status: extracted. Exclusions and reuse evidence: build-audit.json.

## Summary
- 460 nodes · 716 edges · 101 communities (28 shown, 73 thin omitted)
- Extraction: 91% EXTRACTED · 9% INFERRED · 0% AMBIGUOUS · INFERRED: 68 edges (avg confidence: 0.85)
- Token usage: per-project usage unavailable (native Codex semantic extraction).

## Graph Freshness
- Built from commit: `57f84059`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- jquery.js
- stack_alloc.c
- fiber.h
- SearchBox
- navtree.js
- showTip
- koishi.h
- emscripten.c
- win32fiber.c
- initResizable
- dynsections.js
- koishi.h source
- libkoishi C11 coroutine library data structure index
- libkoishi include directory reference
- Doxygen search results shell
- Doxygen search results shell
- Doxygen search results shell
- Doxygen search results shell
- Doxygen search results shell
- Doxygen search results shell
- Doxygen defines_0.html search page
- Doxygen enums_0.html search page
- Doxygen enumvalues_0.html search page
- Doxygen files_0.html search page
- Doxygen functions_0.html search page
- Doxygen groups_0.html search page
- Doxygen groups_1.html search page
- koishi_coroutine_t coroutine instance
- koishi_coroutine_t coroutine instance
- Doxygen wordmark
- Doxygen 1.9.1 generated file index
- search.css and search.js
- Doxygen search results UI
- Doxygen search results UI
- Doxygen search results UI
- Narrow blue gradient chevron texture
- Down arrow
- Closed disclosure indicator
- Small blue-and-white document page icon
- Doxygen logo
- Small blue folder icon
- Open folder icon
- Data fields
- Data field variables
- Global symbols
- Global macros
- Global enumerations
- State enumerators
- Global functions
- Global typedefs
- libkoishi documentation
- Narrow pale gradient navigation strip
- Tiny gray gradient UI strip
- White navigation strip
- Small downward triangle icon
- Close icon
- Close icon
- Gray magnifying glass with drop-down arrow search icon
- Small magnifying-glass search icon
- Small rounded gray left-edge search input graphic
- One-pixel-wide light gray UI separator asset
- Search field right cap
- Vertical splitbar with dotted grip
- Sync off icon
- Bidirectional white arrow on blue sync icon
- Tab edge texture
- Tab border texture
- Tab separator texture
- Narrow gray blue interface texture
- Koishi coroutine implementation choice, thread safety and Valgrind options
- Boost Software License 1.0

## God Nodes (most connected - your core abstractions)
1. `SearchBox()` - 20 edges
2. `initNavTree()` - 13 edges
3. `koishi_resume()` - 12 edges
4. `showTip()` - 11 edges
5. `se()` - 10 edges
6. `showNode()` - 10 edges
7. `koishi_entry()` - 10 edges
8. `koishi_coroutine` - 9 edges
9. `Ee()` - 9 edges
10. `t()` - 9 edges

## Surprising Connections (you probably didn't know these)
- `cofunc1()` --calls--> `koishi_yield()`  [INFERRED]
  koishi_benchmark.c → src/fiber.h
- `cofunc2()` --calls--> `koishi_resume()`  [INFERRED]
  koishi_benchmark.c → src/fiber.h
- `cancelled_caller_test_outer()` --calls--> `koishi_resume()`  [INFERRED]
  koishi_test.c → src/fiber.h
- `main()` --calls--> `koishi_deinit()`  [INFERRED]
  koishi_benchmark.c → src/fiber.h
- `main()` --calls--> `koishi_init()`  [INFERRED]
  koishi_benchmark.c → src/fiber.h

## Import Cycles
- None detected.

## Communities (101 total, 73 thin omitted)

### Community 0 - "jquery.js"
Cohesion: 0.06
Nodes (50): A(), Ae(), b(), be(), ce(), ct(), d(), de() (+42 more)

### Community 1 - "stack_alloc.c"
Cohesion: 0.06
Nodes (27): alloc_stack(), alloc_stack_mem(), free_stack(), free_stack_mem(), get_page_size(), koishi_util_page_size(), koishi_util_real_stack_size(), co_entry() (+19 more)

### Community 2 - "fiber.h"
Cohesion: 0.10
Nodes (30): cofunc1(), cofunc2(), main(), cancelled_caller_test(), cancelled_caller_test_inner(), cancelled_caller_test_outer(), cofunc1(), cofunc2() (+22 more)

### Community 3 - "SearchBox"
Cohesion: 0.12
Nodes (9): convertToId(), createResults(), getXPos(), getYPos(), init_search(), SearchBox(), SearchResults(), setClassAttr() (+1 more)

### Community 4 - "navtree.js"
Cohesion: 0.20
Nodes (28): cachedLink(), createIndent(), deleteLink(), expandNode(), getData(), getNode(), getScript(), glowEffect() (+20 more)

### Community 5 - "showTip"
Cohesion: 0.14
Nodes (25): countFlags(), CSSCoordinates(), DisplayController(), cancelClose(), cancelTimer(), checkForIntent(), closeAnyDelayed(), closeTooltip() (+17 more)

### Community 6 - "koishi.h"
Cohesion: 0.12
Nodes (15): koishi_coroutine, koishi_state, KOISHI_DEAD, KOISHI_IDLE, KOISHI_RUNNING, KOISHI_SUSPENDED, co_entry(), finish_fiber_swap() (+7 more)

### Community 7 - "emscripten.c"
Cohesion: 0.21
Nodes (7): co_entry(), koishi_fiber_deinit(), koishi_fiber_init(), koishi_fiber_init_main(), koishi_fiber_recycle(), koishi_fiber_swap(), koishi_get_stack()

### Community 8 - "win32fiber.c"
Cohesion: 0.23
Nodes (7): fiber_entry(), koishi_fiber_deinit(), koishi_fiber_init(), koishi_fiber_init_main(), koishi_fiber_recycle(), koishi_fiber_swap(), koishi_get_stack()

### Community 9 - "initResizable"
Cohesion: 0.39
Nodes (7): initResizable(), collapseExpand(), readCookie(), resizeHeight(), resizeWidth(), restoreWidth(), writeCookie()

### Community 10 - "dynsections.js"
Cohesion: 0.47
Nodes (3): toggleFolder(), toggleLevel(), updateStripes()

### Community 11 - "koishi.h source"
Cohesion: 0.47
Nodes (6): Advanced stack API, Coroutine API, Stack utilities, koishi.h reference, koishi.h source, Modules

### Community 12 - "libkoishi C11 coroutine library data structure index"
Cohesion: 0.67
Nodes (3): Doxygen 1.9.1, koishi_coroutine_t, libkoishi C11 coroutine library data structure index

### Community 13 - "libkoishi include directory reference"
Cohesion: 0.67
Nodes (3): Doxygen 1.9.1, libkoishi include directory reference, koishi.h public header

### Community 14 - "Doxygen search results shell"
Cohesion: 0.67
Nodes (3): Doxygen, Doxygen search results shell, SearchResults

### Community 15 - "Doxygen search results shell"
Cohesion: 0.67
Nodes (3): Doxygen, Doxygen search results shell, SearchResults

### Community 16 - "Doxygen search results shell"
Cohesion: 0.67
Nodes (3): Doxygen, Doxygen search results shell, SearchResults

### Community 17 - "Doxygen search results shell"
Cohesion: 0.67
Nodes (3): Doxygen, Doxygen search results shell, SearchResults

### Community 18 - "Doxygen search results shell"
Cohesion: 0.67
Nodes (3): Doxygen, Doxygen search results shell, SearchResults

### Community 19 - "Doxygen search results shell"
Cohesion: 0.67
Nodes (3): Doxygen, Doxygen search results shell, SearchResults

### Community 20 - "Doxygen defines_0.html search page"
Cohesion: 0.67
Nodes (3): createResults, Doxygen defines_0.html search page, SearchResults

### Community 21 - "Doxygen enums_0.html search page"
Cohesion: 0.67
Nodes (3): createResults, Doxygen enums_0.html search page, SearchResults

### Community 22 - "Doxygen enumvalues_0.html search page"
Cohesion: 0.67
Nodes (3): createResults, Doxygen enumvalues_0.html search page, SearchResults

### Community 23 - "Doxygen files_0.html search page"
Cohesion: 0.67
Nodes (3): createResults, Doxygen files_0.html search page, SearchResults

### Community 24 - "Doxygen functions_0.html search page"
Cohesion: 0.67
Nodes (3): createResults, Doxygen functions_0.html search page, SearchResults

### Community 25 - "Doxygen groups_0.html search page"
Cohesion: 0.67
Nodes (3): createResults, Doxygen groups_0.html search page, SearchResults

### Community 26 - "Doxygen groups_1.html search page"
Cohesion: 0.67
Nodes (3): createResults, Doxygen groups_1.html search page, SearchResults

### Community 27 - "koishi_coroutine_t coroutine instance"
Cohesion: 0.67
Nodes (3): koishi_coroutine_t coroutine instance, koishi_init required before use, Eight private implementation pointer slots

## Knowledge Gaps
- **91 isolated node(s):** `KOISHI_DEAD`, `KOISHI_IDLE`, `KOISHI_RUNNING`, `KOISHI_SUSPENDED`, `caller` (+86 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 177 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **73 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `koishi_entry()` connect `fiber.h` to `win32fiber.c`, `stack_alloc.c`, `koishi.h`, `emscripten.c`?**
  _High betweenness centrality (0.006) - this node is a cross-community bridge._
- **Are the 8 inferred relationships involving `koishi_resume()` (e.g. with `cofunc2()` and `main()`) actually correct?**
  _`koishi_resume()` has 8 INFERRED edges - model-reasoned connections that need verification._
- **What connects `KOISHI_DEAD`, `KOISHI_IDLE`, `KOISHI_RUNNING` to the rest of the system?**
  _91 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `jquery.js` be split into smaller, more focused modules?**
  _Cohesion score 0.05794556628621598 - nodes in this community are weakly interconnected._
- **Are the 3 inferred relationships involving `se()` (e.g. with `n()` and `r()`) actually correct?**
  _`se()` has 3 INFERRED edges - model-reasoned connections that need verification._
- **Should `stack_alloc.c` be split into smaller, more focused modules?**
  _Cohesion score 0.0602322206095791 - nodes in this community are weakly interconnected._
- **Should `fiber.h` be split into smaller, more focused modules?**
  _Cohesion score 0.0966183574879227 - nodes in this community are weakly interconnected._