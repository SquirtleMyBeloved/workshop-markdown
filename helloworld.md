# Helloworld Programs

![](helloworld.png "Hello World!")

We list below Helloworld programs for different programming languages, i.e. programs that print "Hello, World!". The
specified compiler or interpreter is required for each programming languages.

The table below summarizes the programs:

| Language | Language (Spec) Site | Section | Build / Run Toolchain | Debian / UBUNTU |
| --- | --- | --- | --- | --- |
| C | [The Standard - C](https://www.iso-9899.info/wiki/The_Standard) | [C](helloworld/helloworld.c) | GCC | build-essential |
| C++ | [The Standard - C++](https://isocpp.org/std/the-standard) | [C++](helloworld/helloworld.cpps) | GCC / G++ | build-essential , g++ |
| Dlang | [D Programming Language: Home](https://dlang.org/) | [Dlang](helloworld/helloworld.d) | GCC / GDC | build-essential , gdc |
| Go | [The Go Programming Language](https://go.dev/) | [Go](helloworld/helloworld.go) | Go | golang |
| Rust | [Rust Programming Language](https://rust-lang.org/) | [Rust](helloworld/helloworld.rs) | Rust(Crate) | rustlang |
| Java | [Java Programming Language](https://docs.oracle.com/javase/8/docs/technotes/guides/language/) | [Java](helloworld/helloworld.java) | JDK | openjdk-17-jdk |
| x86_64 assembly | [x86 and amd64 instruction reference](https://www.felixcloutier.com/x86/) | [x86_64 Assembly](TODO) | GCC / GAS | build-essential |
| ARM64 assembly | [Arm A64 Instruction Set Architecture](https://support.arm.com/documentation/ddi0596/latest/) | [GCC / GAS (AArch64)](TODO) | GCC / GAS (AArch64) | build-essential |
| Bash | [Bash Reference Manual](https://www.gnu.org/s/bash/manual/bash.html) | [Bash](helloworld/helloworld.sh) | Bash | bash |
| Python | [Welcome to Python.org](https://www.python.org/) | [Python](helloworld/helloworld.py) | Python | python |
| Ruby | [Ruby Programming Language](https://www.ruby-lang.org/en/) | [Ruby](helloworld/helloworld.rb) | Ruby | ruby |
| PHP | [PHP: Hypertext Preprocessor](https://www.php.net/) | [PHP](helloworld/helloworld.php) | PHP | php |
| Perl | [The Perl Programming Language](https://www.perl.org/) | [Perl](helloworld/helloworld.pl) | Perl | perl |
| Lua | [The Programming Language Lua](https://www.lua.org/) | [Lua](helloworld/helloworld.lua) | Lua | lua |

# C

```
#include <stdio.h>

int main(void)
{
		puts("Hello, World!");
		return 0;
}
```

Build with:

```
	gcc -Wall -o helloworld helloworld.c
```

Run with:
```
	./helloworld
```

# C++

```
#include <iostream>

int main()
{
		std::cout << "Hello, World!" << std::endl;
		return 0;
}
```

Build with:
```
	g++ -Wall -o helloworld helloworld.cpp
```

Run with:
```
	./helloworld
```

# Dlang

```
import std.stdio;

void main()
{
	writeln("Hello, World!");
}
```

Build with:

```
	gdc -Wall -o helloworld helloworld.cpp
```

Run with:
```
	./helloworld
```

# Go

```
package main

import "fmt"

func main() {
	fmt.Println("Hello, World!")
}
```

Build and run with:
```
	go run helloworld.go
```

# Rust

```
fn main() {
	println!("Hello, World");
}
```

Build with:
```
	rustc hello.rs
```

Run with:
```
	./helloworld
```

# Java

```
public class HelloWorld {
	public static void main(String[] args) {
		System.out.println("Hello, World!");
	}
}
```

Build with:
```
	java HellowWorld.java
```

Run with:
```
	java HelloWorld
```

# X86_64 Assembly



Build with:
```
	TODO
```

Run with:
```
	./helloworld
```

TODO

# ARM64 Assembly



Build with:
```
	TODO
```

Run with:
```
	./helloworld
```

# Bash

```
	echo "Hello, World!"
```

Run with:
```
	bash helloworld.sh
```

# Python

```
	print("Hello, World!")
```

Run with:
```
	python helloworld.py
```

# Ruby

```
	puts "Hello, World!"
```

Run with:
```
	ruby helloworld.rb
```

# PHP

```
	<?php
	echo "Hello, World!"
	?>
```

Run with:
```
	./helloworld
```

# Perl

```
	print("Hello, World!\n")
```

Run with:
```
	perl helloworld.pl
```

# Lua

```
	print("Hello, World!")
```

Run with:
```
	lua helloworld.lua
```