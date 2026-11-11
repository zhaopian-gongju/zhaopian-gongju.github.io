本目录是站内页面用到的第三方库，原样取自 npm 发布包，放在本站本地引用（不走外部 CDN）。

pdfjs-3.11.174/
  来源：npm 包 pdfjs-dist@3.11.174（Mozilla pdf.js）
  文件：legacy/build/pdf.min.js、legacy/build/pdf.worker.min.js、cmaps/（全部 169 个 .bcmap）
  许可证：Apache License 2.0，见 pdfjs-3.11.174/LICENSE
  注意：页面里调用 getDocument 时必须带 isEvalSupported:false（3.x 版本在开启 eval 时有字体相关的安全问题）

pdf-lib-1.17.1/
  来源：npm 包 pdf-lib@1.17.1
  文件：dist/pdf-lib.min.js（只删了末尾一行 sourceMappingURL 注释）
  许可证：MIT，见 pdf-lib-1.17.1/LICENSE.md（打包内含 pako、tslib 等依赖，均为宽松许可证）
