## Hi, I'm Heorhii

I build desktop apps and the machine-learning parts inside them, and I ship
them end to end — product, backend, payments, delivery.

Based in Austria (EU), working remotely.

### What I would point at first

**[rust-fps-bandit](https://github.com/heorhiisemyshkurr-dot/rust-fps-bandit)**
— a UCB1 multi-armed bandit that works out, per machine, which system tweaks
actually raise frames per second. It tries them and measures, instead of
trusting a list from a forum. Arm statistics survive restarts; in the shipped
product results are pooled by hardware class, which solves the cold start for
new machines.

**[newsbot-research](https://github.com/heorhiisemyshkurr-dot/newsbot-research)**
— do crypto news headlines predict price? I measured it properly and the
answer was **no**: 81% of the move happens before the headline. Price itself
gave a 53.2% direction hit rate, CI [51.9%, 54.5%] — real, but twelve times
smaller than trading costs. Thresholds were fixed before looking at the data,
and the negative result is the headline.

**[figment-ui](https://github.com/heorhiisemyshkurr-dot/figment-ui)**
— design a Minecraft interface in Figma, press Sync, and see it running in
the game a second later — keeping the text you had typed and the focused
field.

### Tools

Rust (Tauri 2, egui + wgpu, WGSL shaders, tokio) · Python (YOLO11, ONNX) ·
TypeScript / React · Cloudflare Workers, Postgres · Kotlin · Docker

### Notes

Most comments in my code are in Ukrainian or Russian. They explain *why* a
decision was made rather than restating the code — that is deliberate.

English: B1 — I read documentation and write in English; speaking is a work
in progress.
