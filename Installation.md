After the SOLANA CLI installation has completed.
You can run "Solana-test-validator".
However, if you encounter issues like the ones below:

Problem -> io Error, error checking to upack genesis archive: Archive error: Extra entry round: "__.genesis.bin" Reguler.

You can solve the issues with these steps:

  1. brew install gnu-tar
  2. put path in ~/.zshrc
  3. find path -> 'Which tar'
  4. cp gtar tar

Try to run "solana-test-validator".



