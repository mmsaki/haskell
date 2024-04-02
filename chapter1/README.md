# Hello World!

1. Create program in `Main.hs`

   ```hs
   module Main where

   main = print "Hello, World!"
   ```

1. Compile the program and run the program

   ```sh
   ghc Main.hs && ./Main
   ```

1. Run program with `runhaskell`

   ```sh
   runhaskell Main.hs
   ```

1. Interact with program inside `ghci`

   ```sh
   ghci
   ```

1. Load program with `:load Main.hs` then run `main`:

   ```sh
   Loaded package environment from /Users/meekmsaki/dev/haskell/.ghc.environment.x86_64-darwin-9.4.8
   GHCi, version 9.4.8: https://www.haskell.org/ghc/  :? for help
   Loaded GHCi configuration from /Users/meekmsaki/.ghci
   λ :load Main.hs
   [1 of 2] Compiling Main             ( Main.hs, interpreted )
   Ok, one module loaded.
   λ main
   "hello, world!"
   λ
   ```
