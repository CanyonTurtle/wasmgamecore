# wasmgamecore
Use Webassembly Interface Types to revolutionize portable retro consoles &amp; game development


```wit-bindgen.exe c .\packages\wit -w cartridge```

<https://bytecodealliance.github.io/jco/transpiling.html#interface-implementation-example>
<https://bytecodealliance.github.io/jco/example.html>

## Plan
here:
- Use WIT to create a world for a console, and a world for a cartridge
- create a javascript wasm component that implements console (a web runtime for games)
- create a rust wasm component that implements a cartridge (mock game)
- create a different c wasm component that implements a cartridge (a 2nd game)
- Try playing both games