# Flatbuffers Haxe JS Test

## How to run

```bash
  npm install
```

then

```bash
  haxe build.hxml && webpack ./build/main.js ./public/main.js
```

or

```bash
  npm run build
```

## How to install llib

```bash
  haxelib git flatbuffers https://github.com/troyedwardsjr/flatbuffers-haxe.git
```

Current targets: JS, C++/Neko (Coming), Android/Java (Possibly Coming), AS3 (Possibly coming but not likely).