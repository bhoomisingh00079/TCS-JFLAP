# Automata and Formal Languages — JFLAP Practice Pack

This pack contains the nine automata files supplied for this build, renamed with descriptive filenames, plus the complete set of 23 topic examples from the reference learning pack (also renamed). The result contains **32 `.jff` files** and covers all 30 topic areas listed below. The first nine files are additional DFA/NFA practice examples for the finite-automata section.

## Contents and topic coverage

| Topic area | File(s) | What to explore |
|---|---|---|
| Deterministic finite automata | `01_dfa_pattern_recognition.jff`, `03_dfa_language_checker.jff`, `05_dfa_state_transition_practice.jff`, `07_dfa_with_reject_state.jff`, `09_dfa_final_state_exercise.jff` | States, transitions, accepting and rejecting strings |
| Nondeterministic finite automata | `02_nfa_branching_paths.jff`, `04_nfa_string_acceptor.jff`, `06_nfa_multiple_routes.jff`, `08_nfa_sequence_matcher.jff` | Multiple possible paths and acceptance |
| NFA-to-DFA conversion and DFA minimization | Use the NFA/DFA examples above with JFLAP's conversion and minimization tools | Subset construction and equivalent states |
| DFA to regular grammar / regular expression | Use the automata examples above with JFLAP conversion tools | State-to-production and state-elimination conversions |
| Combining automata | Use the DFA/NFA examples above with JFLAP's product/combination operations | Union and combined language recognition |
| Regular expressions | `10_regex_language_definition.jff`, `11_regex_to_automaton_exercise.jff`, `12_regex_equivalence_practice.jff` | Expression syntax, conversion and identities |
| Regular grammars and DFA conversion | `13_right_linear_grammar_examples.jff`, `14_grammar_to_state_machine.jff` | Right-linear productions and equivalent automata |
| DFA pattern search / grep relationship | `15_pattern_search_automaton.jff` | Recognizing a pattern within strings |
| Mealy and Moore machines | `16_mealy_output_machine.jff`, `17_moore_output_machine.jff` | Output on transitions versus output on states |
| Context-free grammar | `18_context_free_language_rules.jff` | A grammar for equal numbers of a's and b's |
| Pushdown automata | `19_stack_based_acceptor.jff`, `20_nondeterministic_stack_palindrome.jff` | Stack operations and nondeterministic stack behavior |
| CFG for balanced parentheses | `21_balanced_bracket_grammar.jff` | Recursive grammar and empty production |
| CFG production forms | `22_single_symbol_productions.jff`, `23_multi_symbol_productions.jff` | Single-symbol and multi-symbol right-hand sides |
| User-controlled parsing | `24_manual_parse_steps.jff` | Step through a derivation manually |
| LL, LR and CYK parsing | `25_top_down_ll_grammar.jff`, `26_bottom_up_lr_grammar.jff`, `27_cyk_normal_form_grammar.jff` | Top-down, bottom-up and CYK parsing grammars |
| Turing machines | `28_single_tape_rewriting_machine.jff`, `29_dual_tape_copy_machine.jff`, `30_turing_scan_subroutine.jff` | One-tape, multi-tape and reusable scan behavior |
| Unrestricted grammar | `31_unrestricted_rewrite_system.jff` | Context-sensitive rewriting patterns |
| L-system | `32_simple_lsystem_rules.jff` | Axiom and recursive production rules |

## Opening the files

1. Install/open JFLAP.
2. Choose **File → Open** and select any `.jff` file.
3. For finite automata, enter sample strings and use **Input → Fast Run** or **Step**.
4. For grammars, use the grammar/derivation tools available for the selected file type.
5. For conversion topics, open an input automaton or grammar and use the relevant JFLAP conversion menu. The conversion exercise is performed in JFLAP; the files are starting examples.

## Notes

- The nine renamed DFA/NFA files are the user's supplied JFLAP files; their automaton definitions have been preserved.
- The other 23 files are based on the supplied reference archive's topic examples, with filenames changed.
- Some specialized formats (Mealy/Moore output tags, multi-tape Turing machines and L-systems) can vary by JFLAP version. If a specialized file does not load as expected, recreate it in the corresponding JFLAP editor and save it from that version.
- Conversion/minimization topics are often demonstrated using JFLAP's built-in operations rather than a separate saved output file.
