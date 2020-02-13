<meta charset="utf-8"/>

# shellspiel

Ever played [Pocket Tanks](https://en.wikipedia.org/wiki/Pocket_Tanks)?

An artillery game inspired by https://github.com/MaxBittker/sandspiel
and frustration with mobile apps.

![](Screenshot.png)

This is a [artillery](https://en.wikipedia.org/wiki/Artillery_game) game built in rust (via wasm), webgl, and some JS glueing things together.

You can't [play online](https://shellspiel.lunar.town) or read [a longer post on the project](https://shellspiel.lunar.town/writing)

The goal is to produce a game I can play on the couch with my friends that doesn't frustrate me and features playful combat.

Thank you, Max, for sandspiel, I enjoy it a lot :)

### 🛠️ Build:

```
# build the wasm once:
cd crate && wasm-pack build && cd ..;
npm install;
npm run start;

# then in a seperate terminal:
cargo watch -s 'wasm-pack build'
```