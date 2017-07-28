# brainfuck et al. for [Try It Online]

This is a collection of simple transpilers for the [Try It Online] family of online interpreters.

Currently available:

* **[brainfuck]**

	Implemented with a wrapping tape of 65,536 8-bit cells.

* **[Alphuck]**

	Transpiles to brainfuck.

* **[brainbool]**

	Implemented with a wrapping tape of 65,536 8-bit cells. Input characters unequal to **1** are treated as **0**. Use `-b` for raw byte input, `-B` for raw byte output.

* **[Random Brainfuck]**

	Implemented with a wrapping tape of 65,536 8-bit cells. Uses a cryptographically secure PRNG.
	
[Try It Online]: https://tryitonline.net/
[brainfuck]: https://esolangs.org/wiki/brainfuck
[Alphuck]: https://esolangs.org/wiki/Alphuck
[brainbool]: https://esolangs.org/wiki/brainbool
[Random Brainfuck]: https://esolangs.org/wiki/Random_Brainfuck
