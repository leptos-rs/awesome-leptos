# Awesome Leptos

A collection of awesome libraries in the Leptos ecosystem.

[Leptos](https://github.com/leptos-rs/leptos) is a framework for creating
full-stack web applications using Rust.

## Resources

- [Leptos Book](https://github.com/leptos-rs/leptos/tree/main/docs/book) (WIP)
- [Discord Community](https://discord.gg/YdRAhS7eQB)

## Tools

- [cargo-leptos](https://github.com/leptos-rs/cargo-leptos) coordinates
  rebuilding the server and client side of your app
- [leptosfmt](https://github.com/bram209/leptosfmt) provides formatting for the
  `view` macro
- [leptos-fmt vscode plugin](https://github.com/codeitlikemiley/leptos-fmt) - autoformat your code with leptosfmt
- [leptosfmt-action](https://github.com/LesnyRumcajs/leptosfmt-action) - Github Action for the [leptosfmt](https://github.com/bram209/leptosfmt) to facilitate embedding it in CI
- [cargo-runner vscode plugin](https://github.com/codeitlikemiley/cargo-runner) - Yet Another Command Runner but specifically for your Rust Project, Just press <kbd>CMD + R</kbd> and it would run the correct command depending on your cursor context it can do cargo run, cargo test and doctest , cargo build and even debug. If you need to override command to add other options you can press <kbd>CMD+SHIFT+R</kbd> ,for more info check [readme](https://github.com/codeitlikemiley/cargo-runner).
- [vscode-leptos-snippets](https://github.com/mondeja/vscode-leptos-snippets) - Useful code snippets for Leptos development in VSCode.


## Starter Templates

### Official

- [leptos-rs/start-trunk](https://github.com/leptos-rs/start-trunk) - Starter
  template for Client-Side Rendered Leptos web framework apps using the
  [Trunk](https://trunkrs.dev/) build tool. Server agnostic.

- [leptos-rs/start](https://github.com/leptos-rs/start) - Starter template for
  use with the Leptos web framework and Actix.

- [leptos-rs/start-axum](https://github.com/leptos-rs/start-axum) - Starter
  template for use with the Leptos web framework and Axum.
- [leptos-rs/start-axum-workspace](https://github.com/leptos-rs/start-axum-workspace) -
  Same as above but using Cargo workspace to split crates

- [leptos-rs/start-aws](https://github.com/leptos-rs/start-aws) - Starter
  template for use with Leptos, Axum, and Amazon Web Services.

- [leptos-rs/start-spin](https://github.com/leptos-rs/start-spin) - Starter
  template for use with the Leptos web framework and the
  [Spin](https://www.fermyon.com/spin) serverless [WASI](https://wasi.dev/)
  platform.

### Unofficial

- [leptos-fullstack](https://github.com/srid/leptos-fullstack) - A
  [Nix](https://nixos.org/) template for full-stack web apps in Rust using
  Leptos + Tailwind

- [leptos-workers](https://github.com/BrandonDyer64/leptos-workers) - Starter
  template for use with Leptos in
  [Cloudflare Workers](https://developers.cloudflare.com/workers/)

- [tauri-leptos-ssr](https://github.com/codeitlikemiley/tauri-leptos-ssr) - ⚡ Tauri + Leptos SSR starter template , Build native desktop apps with server-side rendering, all in Rust.

## Styling and Design

- [Stylers](https://github.com/abishekatp/stylers) Compile-time scoped CSS
  extracted from Leptos components
- [Styled](https://github.com/eboody/styled) Scoped CSS styles
- [turf](https://github.com/myFavShrimp/turf) - Macro based compile-time SCSS
  transpilation, CSS minification, and class name uniquification toolchain
  inspired by CSS modules
- [phosphor-leptos](https://github.com/SorenHolstHansen/phosphor-leptos) The
  [phosphor icon family](https://phosphoricons.com/)
- [Stylance](https://github.com/basro/stylance-rs) Scoped CSS modules.
- [Tailwind Fuse](https://github.com/gaucho-labs/tailwind-fuse) Fuse Tailwind
  CSS class together handling conflicts, and create variant based component
  styles. Inspired by [shadcn/ui](https://ui.shadcn.com/)
- [Leptos Remix Icon](https://crates.io/crates/leptos-remix-icon) A wrapper
  around [Remix Icon](https://remixicon.com/)

## Quality of Life

- [`tracing-subscriber-wasm`](https://crates.io/crates/tracing-subscriber-wasm)
  A `MakeWriter` implementation to allow directly using `tracing_subscriber` in
  the browser or with NodeJS to allow for beautiful `tracing` integration into
  Leptos apps.
- [`wasm-bindgen-struct`](https://crates.io/crates/wasm-bindgen-struct) A crate
  making it easier to declare `wasm_bindgen` types and implement getters/setter
  as if they were normal Rust structs.

## Alternate Macros

- [`leptos-mview`](https://github.com/blorbb/leptos-mview) A concise `view!`
  macro inspired by [maud](https://maud.lambda.xyz/).

## Components

- [Thaw](https://github.com/thaw-ui/thaw) An easy to use leptos component
  library.
- [leptos-struct-table](https://github.com/Synphonyte/leptos-struct-table)
  Easily create powerful tables from structs.
- [leptix](https://github.com/leptix/leptix) Accessible and unstyled components
  for Leptos.
- [leptos-material](https://github.com/jordi-star/leptos-material) A leptos component wrapper for [Material Web Components](https://material-web.dev/), along with some extra components to fill in the gaps.
- [Rust Radix](https://radix.rustforweb.org) Leptos port of Radix,
  a library of components, icons, colors, and templates for building high-quality, accessible UI.
- [Rust shadcn/ui](https://shadcn-ui.rustforweb.org) Leptos port of shadcn/ui,
  a library of beautifully designed components that you can copy and paste into your apps.
- [leptos-shadcn-ui](https://github.com/cloud-shuttle/leptos-shadcn-ui) Production-ready
  ShadCN UI components for Leptos with 38+ components, comprehensive testing, and WCAG 2.1 AA accessibility.

## Libraries

- [leptos-use](https://leptos-use.rs/) Reactive primitives to make app
  development easier. (Like react-use, vue-use, etc.)
- [leptos-fetch](https://github.com/zakstucke/leptos-fetch) Async cache for
  data fetching and state management
- [lepticons](https://lepticons.9bits.cc/) An icon library for Leptos with live demo
- [leptos-icons](https://github.com/Carlosted/leptos-icons) An icon library for
  Leptos
- [leptos_image](https://github.com/gaucho-labs/leptos-image) Image optimizer
  that converts images to .webp format, and generates Low Quality Image
  Placeholders to include in your initial SSR render
- [leptos-declarative](https://github.com/jquesada2016/leptos-declarative)
  Declarative control-flow components
- [leptos-tracked](https://docs.rs/leptos-tracked/latest/leptos_tracked/)
  Utility traits for composing Leptos signals with fewer nested closures
- [leptos-signals](https://github.com/akesson/leptos-signals) Additional
  primitives for working with signals
- [leptos-tea](https://github.com/jquesada2016/leptos-tea) A library for state
  management using The Elm Architecture (TEA) in Leptos
- [leptos-leaflet](https://github.com/headless-studio/leptos-leaflet) Leaflet
  components for Leptos
- [Papelito](https://github.com/msmaiaa/papelito) A simple WYSIWYG editor for
  leptos.
- [leptos-server-signal](https://github.com/tqwewe/leptos_server_signal) Leptos
  signals kept in sync with the server through websockets.
- [leptos_sse](https://github.com/messense/leptos_sse) Leptos server signals
  synced through Server-Sent-Events (SSE).
- [leptos_ws](https://github.com/TimTom2016/leptos_ws) Leptos WS is a Websocket Library to support updates coordinated
  from the Server
- [leptos_i18n](https://github.com/Baptistemontan/leptos_i18n) A translation
  library for Leptos.
- [leptos-fluent](https://github.com/mondeja/leptos-fluent) Internationalization
  framework for Leptos using fluent-templates.
- [leptos_darkmode](https://gitlab.com/kerkmann/leptos_darkmode) A Darkmode
  Helper which adds the `dark` class for Tailwind CSS, based on the local
  storage or media profile.
- [leptos_oidc](https://gitlab.com/kerkmann/leptos_oidc) A Leptos utility
  library for simplified OpenID Connect (OIDC) authentication integration.
- [leptos_meilisearch](https://gitlab.com/kerkmann/leptos_meilisearch) A Leptos
  integration for [meilisearch](https://www.meilisearch.com/), wrapping them in
  a `Resource` and helps with useful helper functions und utils.
- [leptos-captcha](https://github.com/sebadob/leptos-captcha) Simple, fully
  self-hosted Captcha / PoW component for Leptos without any user interaction.
- [leptos-obfuscate](https://github.com/sebadob/leptos-obfuscate) Tiny crate
  with a Leptos component for obfuscating email addresses for bot and spam
  protection
- [cinnog](https://github.com/NiklasEi/cinnog) Experimental static site
  generator using Bevy ECS as a data layer
- [leptoaster](https://github.com/KiaShakiba/leptoaster) A minimal toast library
  for Leptos.
- [leptos_toaster](https://github.com/SorenHolstHansen/leptos_toaster) A Toaster
  component for Leptos heavily inspired by
  [Sonner](https://github.com/emilkowalski/sonner)
- [leptos-hotkeys](https://github.com/gaucho-labs/leptos-hotkeys) Declaratively
  create and pair keybindings with callbacks for Leptos applications.
- [leptos-chartistry](https://github.com/feral-dot-io/leptos-chartistry)
  Chartistry is an extensible charting library for Leptos with many
  [examples](https://feral-dot-io.github.io/leptos-chartistry/examples.html). It
  provides a simple and easy to use `<Chart>` component.
- [leptos_drag_reorder](https://github.com/tqwewe/leptos_drag_reorder) Leptos hook for draggable panels which can be rearranged.
- [Rust Floating UI](https://floating-ui.rustforweb.org/) Leptos port of Floating UI,
  a library that helps you create “floating” elements such as tooltips, popovers, dropdowns, and more.
- [Rust Lucide](https://lucide.rustforweb.org/) Leptos port of Lucide,
  a beautiful & consistent icon toolkit made by the community.
- [leptos_async_signal](https://github.com/demiurg-dev/leptos_async_signal)
  Async signal for SSR generation (generalization of `leptos_meta`).
- [leptos_animate](https://github.com/brofrain/leptos-animate) A bunch of utilities for animating elements with ease. FLIP and CSS in/out transitions included.
- [leptos-unique-ids](https://github.com/mondeja/leptos-unique-ids) Ensure globally unique DOM identifiers across a Leptos application.
- [leptos-pdf](https://github.com/dmanuel64/leptos-pdf) Leptos components for rendering and viewing PDFs in the browser.

## Blogs / Websites

- [Axons Talent](https://axonstalent.com) The official website of Axons Talent, a global technology recruitment company.
- [leptos.dev](https://leptos.dev) The official Leptos website, built with
  Leptos (of course.)
- [benw.is](http://benw.is) benwis's personal blog, built with Leptos SSR,
  storage in Sqlite, and compiled to Spin!
- [Itehax's blog](https://itehax.com) Markdown blog written using Leptos(with
  server side rendering) and styled using Preline (component library for
  tailwindcss) ([source](https://github.com/itehax/rust-blog))
- [LeVuMinhHuy's blog](https://github.com/LeVuMinhHuy/blog) A simple markdown to
  html blog
- [viz.rs](https://viz.rs/) The documentation site for Viz web framework
- [khuedoan.com](https://khuedoan.com) Markdown blog built with Leptos and Axum,
  styled with Tailwind CSS ([source](https://github.com/khuedoan/blog))
- [nicoburniske.com](https://nicoburniske.com) Blog + Photo gallery (using
  leptos_image and leptos_query). Styled with Tailwind CSS.
- [quanticbox.app](https://quanticbox.app) Basic financial dashboard built with
  Leptos, Axum, and Diesel. Styled with Tailwind CSS and DaisyUI.
- [rustytube.rs](https://rustytube.rs) Youtube client for desktop & web. Built
  with Leptos and Tauri; designed with Tailwind and DaisyUI.
  ([repo & binaries](https://github.com/opensourcecheemsburgers/RustyTube))
- [jlewis.sh](https://jlewis.sh/) Personal blog
- [joeymckenzie.tech](https://joeymckenzie.tech/) Markdown blog using Leptos,
  DaisyUI, and Shiki for code highlighting
  ([source](https://github.com/JoeyMckenzie/joeymckenzie.tech))
- [moturbo.com](https://moturbo.com/) Shop for motorcycle parts, built with
  Leptos.
- [utils.surge.sh](https://utils.surge.sh) Utils Homepage and dashboard, Utils(utilities) is a set of CLI tools to Transform developer experience, boost productivity, and elevate the quality of your projects. Built with Leptos CSR + Tailwind + [Remix Icon](https://remixicon.com) and [Animate On Scroll Library](https://michalsnik.github.io/aos/)
- [s1n7ax.com](https://s1n7ax.com/) Portfolio using Leptos SSR + Tailwind ([github](https://github.com/s1n7ax/my-website))
- [atpage](https://atpage.one/) linktree-like application on atproto, [built with Leptos](https://github.com/danloh/atpage).
- [TryRust](https://tryrust.org/) Little Rust playground like TryHaskell or TryClojure. Built with Leptos + Tailwind + Tokio/Axum. ([github](https://github.com/rust-dd/tryrust.org))
- [Rust-DD Blog Engine](https://rust-dd.com) A Blog engine written in Rust, using Leptos SSR + Tailwind, SurrealDB, Dufs and Tokio/Axum. ([github](https://github.com/rust-dd/blog))
- [Ever blog](https://www.everdev.it/) Blog, built with Leptos SSR (Axum) + TailwindCSS, storage in RedisDB, email sender with SMTP to feedback feature.
- [Ibis](https://ibis.wiki) Federated encyclopedia based on ActivityPub protocol, uses Leptos, Axum, Diesel and Tailwind. Open source under AGPL and available for selfhosting
- [Owdle](https://owdle.guessing.day/) Daily guessing game with Overwatch heroes. Built with Leptos CSR.
- [simpleicons.org](https://simpleicons.org) The website for [Simple Icons](https://github.com/simple-icons/simple-icons). Built with Leptos CSR + TailwindCSS ([github](https://github.com/simple-icons/simple-icons-website-rs))
- [osynic-osuapi.deno.dev](https://osynic-osuapi.deno.dev/) Beautiful, modern [OsynicOsuapi](https://github.com/osynicite/osynic_osuapi) demo website. Deployed on Deno Deploy. Built with Leptos CSR + TailwindCSS + Lucide Leptos + Leptos Fluent + Osynic Osuapi ([github](https://github.com/islatri/leptos_osuapi_playground))
- [SQLite Playground](https://sqlight.dev) A SQLite Playground that runs completely locally. Built with Leptos CSR. ([github](https://github.com/Spxg/sqlight))
- [ccf-deadlines](https://ccfddl.com) Collaboratively track worldwide conference deadlines. Built with Leptos CSR and thaw-ui. ([github](https://github.com/ccfddl/ccf-deadlines))

