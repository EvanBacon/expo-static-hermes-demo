# Static Hermes Expo Demo

This is a simple demo of how to use the new Static Hermes with Expo dev clients (tested on iOS). 

This uses the Static Hermes fork from Software Mansion https://github.com/software-mansion-labs/hermes/ 

There's also a couple patches to remove babel plugins that appear to not be needed anymore as Static Hermes supports a number of additional JavaScript language features out of the box. Features such as async/await, destructuring, let/const, and more (but not `class` syntax).