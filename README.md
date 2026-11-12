# Theory of Computer Science — JFLAP Practice Pack

This folder contains **exactly 30 `.jff` files**, arranged in the same learning sequence as the supplied reference pack. The extra nine introductory DFA/NFA practice files from the earlier draft have been removed so the collection stays at 30 files.

The four requested automata examples are placed directly in topics **04–07**:
- DFA minimization
- DFA to regular grammar conversion
- DFA to regular expression conversion
- Combining automata

## Getting started

1. Install Java if it is not already installed.
2. Download JFLAP from https://www.jflap.org/modules/.
3. Open JFLAP and choose **File → Open**.
4. Select any `.jff` file in this folder.
5. For automata, test strings using **Input → Fast Run** or **Step**. For conversion topics, use the corresponding JFLAP conversion operation.

## File index

| # | Topic | File | What to explore |
|---:|---|---|---|
| 1 | Deterministic Finite Automata | `01_deterministic_string_machine.jff` | DFA accepting strings over {a,b} that end in `ab` |
| 2 | Nondeterministic Finite Automata | `02_nondeterministic_suffix_matcher.jff` | NFA accepting strings that end in `ab` |
| 3 | NFA to DFA Conversion | `03_nfa_subset_conversion_start.jff` | NFA for strings whose second-to-last symbol is `a` |
| 4 | DFA Minimization | `04_equivalent_state_minimizer.jff` | DFA with equivalent accepting states; minimize it to two states |
| 5 | DFA to Regular Grammar Conversion | `05_even_a_regular_grammar_source.jff` | DFA accepting strings with an even number of `a` symbols |
| 6 | DFA to Regular Expression Conversion | `06_starts_with_a_regex_source.jff` | DFA accepting strings that start with `a` |
| 7 | Combining Automata | `07_automata_language_combiner.jff` | DFA for strings containing `aa`; use it with JFLAP's automata-combination operations |
| 8 | Regular Expression | `08_regular_expression_builder.jff` | Expression `(a|b)*abb` |
| 9 | Regular Expression to DFA Conversion | `09_expression_to_dfa_practice.jff` | Expression `(ab|b)*a` |
| 10 | Regular Expression Identities | `10_regular_expression_laws.jff` | Expression `(a|b)*` for exploring identities |
| 11 | Regular Grammar | `11_right_linear_grammar_practice.jff` | Right-linear grammar for `a*ba` |
| 12 | Regular Grammar to DFA Conversion | `12_grammar_to_dfa_conversion.jff` | Convert a regular grammar into a DFA |
| 13 | DFA Relationship to Grep | `13_abb_pattern_recognizer.jff` | DFA for `(a|b)*abb` |
| 14 | Mealy Machine | `14_mealy_01_detector.jff` | Output `1` when `01` is completed |
| 15 | Moore Machine | `15_moore_01_detector.jff` | Output `1` after `01` is detected |
| 16 | Context-free Grammar | `16_anbn_context_free_grammar.jff` | Grammar `S → aSb \| λ`, generating `aⁿbⁿ` |
| 17 | Pushdown Automata | `17_pushdown_anbn_acceptor.jff` | PDA accepting `aⁿbⁿ` by final state |
| 18 | NPDA to CFG Conversion | `18_even_palindrome_npda.jff` | NPDA for even palindromes; use it for CFG conversion |
| 19 | CFG to NPDA Conversion | `19_balanced_parentheses_grammar.jff` | Grammar for balanced parentheses; use it for NPDA conversion |
| 20 | CFG with Single Symbols | `20_single_symbol_cfg_rules.jff` | Grammar with single-symbol right-hand sides |
| 21 | CFG with Multiple Symbols | `21_multi_symbol_cfg_rules.jff` | Grammar with multi-symbol right-hand sides, such as `S → aAb` |
| 22 | User-Controlled Parsing | `22_manual_cfg_derivation.jff` | Step through a grammar derivation manually |
| 23 | LL Parsing | `23_ll_expression_parser.jff` | LL(1) grammar for arithmetic expressions |
| 24 | LR Parsing | `24_lr_expression_parser.jff` | LR grammar `E → E+T \| T`, `T → a` |
| 25 | CYK Parsing | `25_cyk_normal_form_grammar.jff` | Grammar in Chomsky Normal Form |
| 26 | One-Tape Turing Machine | `26_single_tape_symbol_rewriter.jff` | Replace every `a` with `b` |
| 27 | Multi-Tape Turing Machine | `27_two_tape_copy_machine.jff` | Copy input onto a second tape |
| 28 | Turing Machine Building Blocks | `28_turing_machine_scan_block.jff` | Move right to the first blank as a reusable scan operation |
| 29 | Unrestricted Grammar | `29_unrestricted_anbncn_grammar.jff` | Unrestricted grammar generating `aⁿbⁿcⁿ` |
| 30 | L-System | `30_basic_lsystem_rules.jff` | Axiom `A` with rules `A → AB`, `B → A` |

## Notes

- The filenames have been changed from the reference archive while preserving the topic order.
- Topics 04–07 use the four specifically requested automata examples.
- Conversion tasks are performed with JFLAP's built-in conversion tools; the corresponding files are starting examples.
- Some specialized machine/grammar formats can behave differently across JFLAP versions. If a specialized file does not load, recreate it in the matching editor and save it from your installed version.
