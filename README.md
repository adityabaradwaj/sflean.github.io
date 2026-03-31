# sflean.github.io

Hello! We're a friendly Lean study group that meets at Mox SF on Mondays at 19:00 in late 2025 and early 2026. Our goal is to formalize the first five chapters of Terence Tao's Analysis textbook together in Lean.

If you have time before you arrive, try installing the [Natual Number Game](https://github.com/leanprover-community/NNG4) locally. You'll want to open the repo in a VSCode devcontainer and open http://localhost:3000 in your browser.

If you'd like to skip straight to the math, clone Terrence Tao's repo:
1. `git clone https://github.com/teorth/analysis`
2. `cd analysis/analysis`
3. `lake exe cache get`
4. Start poking around `Section_2_2.lean` and filling out the `sorry`s.

Good luck! You can ask for help / check the next meeting in the Discord
server, which you can join by concatenating `https://discord.gg/` and
`bXNPh` and `Qyjfe` and pasting into your browser.

## Past Session Conversation Topics

- **30 Mar 2026:**
  - Rado: [Zorn's lemma formalization][1] - took a Lean statement from
	Tao's Analysis and prodded models until they got it to proofcheck
  - Sudoku solvers and verso (lean docs tool)
  - Pablo: von neumann game theory & nash equilib - constructively prove
	that a nash equilib always exists
  - Will: Property-based testing library
- **23 Mar 2026:**
  - New format: let's demo / present!
  - MathInc did an autonomous lean formalization of dimension-24
	(following-up 2022 Fields Medal Maryna Viazovska), which raises
	interesting questions about the future of mathlib
  - New tools: Gauss, Aristotle, Leanstral
  - LLM chatter: Gemini seems smartest but has a confidence issue, codex is
	the practically smartest at the moment
  - lean-libclang - goal of creating a lean bindgen
  - [Equational Theories distillation
	challenge](https://terrytao.wordpress.com/2026/03/13/mathematics-distillation-challenge-equational-theories/)
	from Terry Tao
  - [Interview of Tao on Lean](https://www.youtube.com/watch?v=Q8Fkpi18QXU)
  - [Gower's
	Puzzles](https://gowers.wordpress.com/2026/03/20/group-and-semigroup-puzzles-and-a-possible-polymath-project/)
	are some turing machine word games from a mathematician
- **09 Feb 2026:**
  - Lean metaprogramming from Perry
  - Number theory part 3 from Gerhard
- **02 Feb 2026:**
  - Number theory part 2 from Gerhard
- **26 Jan 2026:**
  - Number theory part 1 from Gerhard

[1]: https://en.wikipedia.org/wiki/Zorn%27s_lemma
