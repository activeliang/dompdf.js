# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [2.0.1](https://github.com/lmn1919/dompdf.js/compare/v2.0.0...v2.0.1) (2026-08-27)


### Features

* 新增 Chrome 扩展 ([424576a](https://github.com/lmn1919/dompdf.js/commit/424576a0124b1ebdafa68752cf53edc86bb23d02))
* add blank PDF detection to comparison demo ([a4a04b2](https://github.com/lmn1919/dompdf.js/commit/a4a04b28dcc3837d5a5fcc84b874d2bc0cfbd7b3))
* add export progress callback onProgress support ([2b9873c](https://github.com/lmn1919/dompdf.js/commit/2b9873c7d7ed61dfad5b4671b7c4f0ecd7e58a59))
* add HTML form support with static and interactive PDF fields ([afa8979](https://github.com/lmn1919/dompdf.js/commit/afa8979f153f0e69ee0853af215b6d0cdb7fc457))
* add HTML form support with static and interactive PDF fields ([cf9cb19](https://github.com/lmn1919/dompdf.js/commit/cf9cb1932b210abb197ca7cad21a28ede3a6c8ea))
* add legacy API compat layer for langFontConfig and excludePage/excludePages ([6f6be65](https://github.com/lmn1919/dompdf.js/commit/6f6be652c784118e15e1bd5f6fa60fa86a7f1789))
* add Markdown editor example with multi-theme preview and PDF export ([3a3dc83](https://github.com/lmn1919/dompdf.js/commit/3a3dc8318e8570ebfc55c7a123d973b0339635e2))
* add oklch color parsing with test samples ([802be0c](https://github.com/lmn1919/dompdf.js/commit/802be0c81d23e76830ce6ea425799379d4ed9c29))
* add oklch color parsing with test samples ([086d13a](https://github.com/lmn1919/dompdf.js/commit/086d13a8cf121422f63387d0f31b5f2d54f261aa))
* add PDF encryption with user/owner password and permissions ([fe975f1](https://github.com/lmn1919/dompdf.js/commit/fe975f17433a7f66502e8ae202440c3a34147c35))
* add PDF hyperlink annotations ([1899a7e](https://github.com/lmn1919/dompdf.js/commit/1899a7e517debcf3879fc009319da872454204f9))
* add PR verification examples with i18n support ([20547b1](https://github.com/lmn1919/dompdf.js/commit/20547b1d6486a9ce27800554fd0a1b645460b933))
* add watermark support with snapshot v10 format ([4845cd2](https://github.com/lmn1919/dompdf.js/commit/4845cd20bc2c5ebf520e70e5aaa437e3a294b570))
* **examples:** add OKLCH color space and pseudo-element demo sections ([d4078ca](https://github.com/lmn1919/dompdf.js/commit/d4078ca18ed9194d1ef5fd16c1950970640ae9df))
* **examples:** add OKLCH color space and pseudo-element demo sections ([b10ca16](https://github.com/lmn1919/dompdf.js/commit/b10ca1667cdbf69d36bdbb0c371cc4300d4e1132))
* **examples:** vendor editor dependencies and improve studio UX ([78174a8](https://github.com/lmn1919/dompdf.js/commit/78174a8e5730a10856c5ad134ca9938ac0dcbca7))
* **examples:** vendor editor dependencies and improve studio UX ([fc9533b](https://github.com/lmn1919/dompdf.js/commit/fc9533b055fc9186d6a0160f159a67cb228bc710))
* expand example page with tables, forms and code sections ([09f0440](https://github.com/lmn1919/dompdf.js/commit/09f044032c58eaf5f079f3f3c83981863334131c))
* expand example page with tables, forms and code sections ([704931a](https://github.com/lmn1919/dompdf.js/commit/704931ac4e0205580e87b48e92c07104e018440a))
* guard export and page switch until example resources ready ([f0d1779](https://github.com/lmn1919/dompdf.js/commit/f0d17795771eebc9e2341e60a6885cec7e499d2d))
* **pdf-diff:** generate Markdown reports alongside JSON ([706f3d6](https://github.com/lmn1919/dompdf.js/commit/706f3d6c80484c9ce3cd99bb46bf4e2edd5a4f73))
* **pdf-diff:** generate Markdown reports alongside JSON ([fc2eb6c](https://github.com/lmn1919/dompdf.js/commit/fc2eb6c65ab0ae0b839ba9176f926a733f167c31))
* Polish comparison page with invoice template and optimized flow ([03bd96a](https://github.com/lmn1919/dompdf.js/commit/03bd96acb31b7ffd62d67594137de6af1ff7925f))
* Re-add PDF encryption support to wasm paginate module ([020e307](https://github.com/lmn1919/dompdf.js/commit/020e307f6bad3326d995340d2ca5799275629d36))
* redesign example trend chart and clean up demo sections ([cc47e6b](https://github.com/lmn1919/dompdf.js/commit/cc47e6b15c0b6b4ff70c5089dcdbce7edc1ce972))
* redesign example trend chart and clean up demo sections ([b63093d](https://github.com/lmn1919/dompdf.js/commit/b63093d59351ba9457342e75103fa97f998c6069))
* Replace markdown editor with Vditor IR mode and sidebar folding ([a594082](https://github.com/lmn1919/dompdf.js/commit/a59408218fec8371debc3cf31d6c74fc9554fe48))
* **snapshot:** synthesize CSS ::marker boxes for list items ([888ee5a](https://github.com/lmn1919/dompdf.js/commit/888ee5a38cd73213763d346cff4af1fe515b5692))
* **snapshot:** synthesize CSS ::marker boxes for list items ([fb7c1e7](https://github.com/lmn1919/dompdf.js/commit/fb7c1e758ff3f2cada379788686124cd958982e5))


### Bug Fixes

* align subset glyph mapping with HashSet used_gids ([70400c5](https://github.com/lmn1919/dompdf.js/commit/70400c59ca6e34f42ea09ed47e2ed1152edc32cb))
* reject pending requests on worker crash to prevent Promise leak ([9ba8573](https://github.com/lmn1919/dompdf.js/commit/9ba85732c2b251b843e49adbee7aca8332b68bde))
* reject pending requests on worker crash to prevent Promise leak ([7924293](https://github.com/lmn1919/dompdf.js/commit/7924293dd5df56e452274278fcfc43ace7dc67f2))
* repair broken syntax in examples/index.js ([42c14ad](https://github.com/lmn1919/dompdf.js/commit/42c14ad166f222e0f7bae307a997f03008b3ffb4))
* repair broken syntax in examples/index.js ([8c95566](https://github.com/lmn1919/dompdf.js/commit/8c95566c69ae0fd8cb74a9760c743de5822f2e5d))
* skip CID font fallback for pure Latin text to eliminate text-x-drift ([be1c034](https://github.com/lmn1919/dompdf.js/commit/be1c034d399d5b55af99448173b2f59aa53ed10a))
* Skip display:none elements to prevent incorrect node ID assignment ([25b2efe](https://github.com/lmn1919/dompdf.js/commit/25b2efee9b548417790e38d58f9e6befa3f5734d))
* **wasm:** render solid borders with filled rectangles ([d7955cb](https://github.com/lmn1919/dompdf.js/commit/d7955cbfe12d85ab815ee1cc5d91efb0d3a71eae))
* **wasm:** render solid borders with filled rectangles ([c35e677](https://github.com/lmn1919/dompdf.js/commit/c35e6770ae1ca89033565551ca68c29083d33d0f))

## [0.1.0]

- feat: rewrite the PDF pipeline around Rust + WebAssembly + Web Worker
- feat: support vector PDF output, pagination, and Unicode font embedding
- feat: add watermark support in the snapshot v10 rendering pipeline
- feat: add PDF encryption with user and owner permissions
- feat: add Markdown editor and comparison demos
- docs: add migration and pdf-diff system documentation
