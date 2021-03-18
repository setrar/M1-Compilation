# M1-Compilation

- [ ] Install XCode command line

```
% xcode-select --install
```

- [ ] Install LLVM

```
% brew install llvm     
==> Downloading https://homebrew.bintray.com/bottles/libffi-3.3_3.arm64_big_sur.
######################################################################## 100.0%
==> Downloading https://homebrew.bintray.com/bottles/llvm-11.1.0.arm64_big_sur.b
==> Downloading from https://d29vzk4ow07wi7.cloudfront.net/6024181e8252d3300a44d
######################################################################## 100.0%
==> Installing dependencies for llvm: libffi
==> Installing llvm dependency: libffi
==> Pouring libffi-3.3_3.arm64_big_sur.bottle.tar.gz
==> Caveats
libffi is keg-only, which means it was not symlinked into /opt/homebrew,
because macOS already provides this software and installing another version in
parallel can cause all kinds of trouble.

For compilers to find libffi you may need to set:
  export LDFLAGS="-L/opt/homebrew/opt/libffi/lib"
  export CPPFLAGS="-I/opt/homebrew/opt/libffi/include"

For pkg-config to find libffi you may need to set:
  export PKG_CONFIG_PATH="/opt/homebrew/opt/libffi/lib/pkgconfig"

==> Summary
🍺  /opt/homebrew/Cellar/libffi/3.3_3: 17 files, 617.4KB
==> Installing llvm
==> Pouring llvm-11.1.0.arm64_big_sur.bottle.tar.gz
==> Caveats
To use the bundled libc++ please add the following LDFLAGS:
  LDFLAGS="-L/opt/homebrew/opt/llvm/lib -Wl,-rpath,/opt/homebrew/opt/llvm/lib"

llvm is keg-only, which means it was not symlinked into /opt/homebrew,
because macOS already provides this software and installing another version in
parallel can cause all kinds of trouble.

If you need to have llvm first in your PATH, run:
  echo 'export PATH="/opt/homebrew/opt/llvm/bin:$PATH"' >> ~/.zshrc

For compilers to find llvm you may need to set:
  export LDFLAGS="-L/opt/homebrew/opt/llvm/lib"
  export CPPFLAGS="-I/opt/homebrew/opt/llvm/include"

==> Summary
🍺  /opt/homebrew/Cellar/llvm/11.1.0: 8,924 files, 1.3GB
==> Caveats
==> libffi
libffi is keg-only, which means it was not symlinked into /opt/homebrew,
because macOS already provides this software and installing another version in
parallel can cause all kinds of trouble.

For compilers to find libffi you may need to set:
  export LDFLAGS="-L/opt/homebrew/opt/libffi/lib"
  export CPPFLAGS="-I/opt/homebrew/opt/libffi/include"

For pkg-config to find libffi you may need to set:
  export PKG_CONFIG_PATH="/opt/homebrew/opt/libffi/lib/pkgconfig"

==> llvm
To use the bundled libc++ please add the following LDFLAGS:
  LDFLAGS="-L/opt/homebrew/opt/llvm/lib -Wl,-rpath,/opt/homebrew/opt/llvm/lib"

llvm is keg-only, which means it was not symlinked into /opt/homebrew,
because macOS already provides this software and installing another version in
parallel can cause all kinds of trouble.

If you need to have llvm first in your PATH, run:
  echo 'export PATH="/opt/homebrew/opt/llvm/bin:$PATH"' >> ~/.zshrc

For compilers to find llvm you may need to set:
  export LDFLAGS="-L/opt/homebrew/opt/llvm/lib"
  export CPPFLAGS="-I/opt/homebrew/opt/llvm/include"
  ```
  
https://www.haskell.org/ghc/blog/20200515-ghc-on-arm.html
