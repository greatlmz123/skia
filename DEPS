use_relative_paths = True
 
vars = {
  "checkout_chromium": False,
<<<<<<< Updated upstream

  # Three lines of non-changing comments so that
  # the commit queue can handle CLs rolling different
  # dependencies without interference from each other.
  'sk_tool_revision': 'git_revision:4f4d765e4e513c1867383550fd43d015a354cf66',
=======
>>>>>>> Stashed changes
}
 
deps = {
<<<<<<< Updated upstream
  "buildtools"                            : "https://chromium.googlesource.com/chromium/src/buildtools.git@b138e6ce86ae843c42a1a08f37903207bebcca75",
  "third_party/externals/angle2"          : "https://chromium.googlesource.com/angle/angle.git@b9c0194c4e1ee350323d1b02c87bf0bebdf01538",
  "third_party/externals/brotli"          : "https://skia.googlesource.com/external/github.com/google/brotli.git@e61745a6b7add50d380cfd7d3883dd6c62fc2c71",
  "third_party/externals/d3d12allocator"  : "https://skia.googlesource.com/external/github.com/GPUOpen-LibrariesAndSDKs/D3D12MemoryAllocator.git@169895d529dfce00390a20e69c2f516066fe7a3b",
  # Dawn requires jinja2 and markupsafe for the code generator, tint for SPIRV compilation, and abseil for string formatting.
  # When the Dawn revision is updated these should be updated from the Dawn DEPS as well.
  "third_party/externals/dawn"            : "https://dawn.googlesource.com/dawn.git@67e1e9c199cccd6917f68b34e1db5ac11fcd511e",
  "third_party/externals/jinja2"          : "https://chromium.googlesource.com/chromium/src/third_party/jinja2@ee69aa00ee8536f61db6a451f3858745cf587de6",
  "third_party/externals/markupsafe"      : "https://chromium.googlesource.com/chromium/src/third_party/markupsafe@0944e71f4b2cb9a871bcbe353f95e889b64a611a",
  "third_party/externals/tint"            : "https://dawn.googlesource.com/tint@d018d2e5bca105b391aa9cf99b23c59223da1efe",
  "third_party/externals/abseil-cpp"      : "https://chromium.googlesource.com/chromium/src/third_party/abseil-cpp@789af048b388657987c59d4da406859034fe310f",
  "third_party/externals/dng_sdk"         : "https://android.googlesource.com/platform/external/dng_sdk.git@c8d0c9b1d16bfda56f15165d39e0ffa360a11123",
  "third_party/externals/egl-registry"    : "https://skia.googlesource.com/external/github.com/KhronosGroup/EGL-Registry@a0bca08de07c7d7651047bedc0b653cfaaa4f2ae",
  "third_party/externals/expat"           : "https://chromium.googlesource.com/external/github.com/libexpat/libexpat.git@a28238bdeebc087071777001245df1876a11f5ee",
  "third_party/externals/freetype"        : "https://chromium.googlesource.com/chromium/src/third_party/freetype2.git@e6e6cbf1648d4a776da0857921872f2fbc853205",
  "third_party/externals/harfbuzz"        : "https://chromium.googlesource.com/external/github.com/harfbuzz/harfbuzz.git@a52c6df38a38c4e36ff991dfb4b7d92e48a44553",
  "third_party/externals/icu"             : "https://chromium.googlesource.com/chromium/deps/icu.git@a0718d4f121727e30b8d52c7a189ebf5ab52421f",
  "third_party/externals/imgui"           : "https://skia.googlesource.com/external/github.com/ocornut/imgui.git@9418dcb69355558f70de260483424412c5ca2fce",
  "third_party/externals/libgifcodec"     : "https://skia.googlesource.com/libgifcodec@fd59fa92a0c86788dcdd84d091e1ce81eda06a77",
  "third_party/externals/libjpeg-turbo"   : "https://chromium.googlesource.com/chromium/deps/libjpeg_turbo.git@24e310554f07c0fdb8ee52e3e708e4f3e9eb6e20",
  "third_party/externals/libpng"          : "https://skia.googlesource.com/third_party/libpng.git@386707c6d19b974ca2e3db7f5c61873813c6fe44",
  "third_party/externals/libwebp"         : "https://chromium.googlesource.com/webm/libwebp.git@9ce5843dbabcfd3f7c39ec7ceba9cbeb213cbfdf",
  "third_party/externals/microhttpd"      : "https://android.googlesource.com/platform/external/libmicrohttpd@748945ec6f1c67b7efc934ab0808e1d32f2fb98d",
  "third_party/externals/oboe"            : "https://chromium.googlesource.com/external/github.com/google/oboe.git@b02a12d1dd821118763debec6b83d00a8a0ee419",
  "third_party/externals/opengl-registry" : "https://skia.googlesource.com/external/github.com/KhronosGroup/OpenGL-Registry@14b80ebeab022b2c78f84a573f01028c96075553",
  "third_party/externals/piex"            : "https://android.googlesource.com/platform/external/piex.git@bb217acdca1cc0c16b704669dd6f91a1b509c406",
  "third_party/externals/sfntly"          : "https://chromium.googlesource.com/external/github.com/googlei18n/sfntly.git@b55ff303ea2f9e26702b514cf6a3196a2e3e2974",
  "third_party/externals/spirv-cross"     : "https://chromium.googlesource.com/external/github.com/KhronosGroup/SPIRV-Cross@0e2880ab990e79ce6cc8c79c219feda42d98b1e8",
  "third_party/externals/spirv-headers"   : "https://skia.googlesource.com/external/github.com/KhronosGroup/SPIRV-Headers.git@cf653e4ca4858583802b0d1656bc934edff6bd7f",
  "third_party/externals/spirv-tools"     : "https://skia.googlesource.com/external/github.com/KhronosGroup/SPIRV-Tools.git@11cd875ed88484f93943071083b4821b4c3d2193",
  "third_party/externals/swiftshader"     : "https://swiftshader.googlesource.com/SwiftShader@4c687cc2f8ea9d096a66ad43c08805d36a559ede",
=======
  "buildtools"                            : "https://github.com/GoogleDepends/buildtools.git@505de88083136eefd056e5ee4ca0f01fe9b33de8",
  "common"                                : "https://github.com/GoogleDepends/common.git@9737551d7a52c3db3262db5856e6bcd62c462b92",
  "third_party/externals/angle2"          : "https://github.com/GoogleDepends/angle2.git@1cc49bb2e230555fb3dc33d3400a5f7a0cefe943",
  # Dawn requires jinja2 and markupsafe for the code generator, and glslang and shaderc for SPIRV compilation.
  # When the Dawn revision is updated these should be updated from the Dawn DEPS as well.
  "third_party/externals/dawn"            : "https://github.com/GoogleDepends/dawn.git@11652ff8f8b3c3104eb2627717fa652d432d5b84",
  "third_party/externals/glslang"         : "https://github.com/GoogleDepends/glslang@1f0fcbe5a30fdc9632a8bff36277103fabf0797c",
  "third_party/externals/jinja2"          : "https://github.com/GoogleDepends/jinja2@b41863e42637544c2941b574c7877d3e1f663e25",
  "third_party/externals/markupsafe"      : "https://github.com/GoogleDepends/markupsafe@8f45f5cfa0009d2a70589bcda0349b8cb2b72783",
  "third_party/externals/shaderc"         : "https://github.com/GoogleDepends/shaderc@362becca1ff2a841c21fd675ac3a9c1ee9bb5612",
  "third_party/externals/dng_sdk"         : "https://github.com/GoogleDepends/dng_sdk.git@c8d0c9b1d16bfda56f15165d39e0ffa360a11123",
  "third_party/externals/egl-registry"    : "https://github.com/GoogleDepends/EGL-Registry@a0bca08de07c7d7651047bedc0b653cfaaa4f2ae",
  "third_party/externals/expat"           : "https://github.com/GoogleDepends/expat.git@e5aa0a2cb0a5f759ef31c0819dc67d9b14246a4a",
  "third_party/externals/freetype"        : "https://github.com/GoogleDepends/freetype2.git@0a3d2bb99b45b72e1d45185ab054efa993d97210",
  "third_party/externals/harfbuzz"        : "https://github.com/GoogleDepends/harfbuzz.git@3a74ee528255cc027d84b204a87b5c25e47bff79",
  "third_party/externals/icu"             : "https://github.com/GoogleDepends/icu.git@dbd3825b31041d782c5b504c59dcfb5ac7dda08c",
  "third_party/externals/imgui"           : "https://github.com/GoogleDepends/imgui.git@d38d7c6628bebd02692cfdd6fa76b4d992a35b75",
  "third_party/externals/libgifcodec"     : "https://github.com/GoogleDepends/libgifcodec@d06d2a6d42baf6c0c91cacc28df2542a911d05fe",
  "third_party/externals/libjpeg-turbo"   : "https://github.com/GoogleDepends/libjpeg-turbo.git@574f3a772c96dc9db2c98ef24706feb3f6dbda9a",
  "third_party/externals/libpng"          : "https://github.com/GoogleDepends/libpng.git@386707c6d19b974ca2e3db7f5c61873813c6fe44",
  "third_party/externals/libwebp"         : "https://github.com/GoogleDepends/libwebp.git@0fe1a89dbf1930fc2554dbe76adad5d962054ead",
  "third_party/externals/lua"             : "https://github.com/GoogleDepends/lua.git@e354c6355e7f48e087678ec49e340ca0696725b1",
  "third_party/externals/microhttpd"      : "https://github.com/GoogleDepends/libmicrohttpd@748945ec6f1c67b7efc934ab0808e1d32f2fb98d",
  "third_party/externals/opencl-lib"      : "https://github.com/GoogleDepends/common-lib-amd-APPSDK-3.0@4e6d30e406d2e5a65e1d65e404fe6df5f772a32b",
  "third_party/externals/opencl-registry" : "https://github.com/GoogleDepends/OpenCL-Registry@932ed55c85f887041291cef8019e54280c033c35",
  "third_party/externals/opengl-registry" : "https://github.com/GoogleDepends/OpenGL-Registry@14b80ebeab022b2c78f84a573f01028c96075553",
  "third_party/externals/piex"            : "https://github.com/GoogleDepends/piex.git@bb217acdca1cc0c16b704669dd6f91a1b509c406",
  "third_party/externals/sdl"             : "https://github.com/GoogleDepends/sdl@5d7cfcca344034aff9327f77fc181ae3754e7a90",
  "third_party/externals/sfntly"          : "https://github.com/GoogleDepends/sfntly.git@b55ff303ea2f9e26702b514cf6a3196a2e3e2974",
  "third_party/externals/spirv-cross"     : "https://github.com/GoogleDepends/SPIRV-Cross@871c85d7f0edc6b613e3959bc51d13bfbc2fe2df",
  "third_party/externals/spirv-headers"   : "https://github.com/GoogleDepends/SPIRV-Headers.git@f8bf11a0253a32375c32cad92c841237b96696c0",
  "third_party/externals/spirv-tools"     : "https://github.com/GoogleDepends/SPIRV-Tools.git@1c8bda3721e6b9302f694b58c26d32eff341b126",
  "third_party/externals/swiftshader"     : "https://github.com/GoogleDepends/swiftshader@f99302c4efe6f32297a619d407b4410ec3ee6412",
>>>>>>> Stashed changes
  #"third_party/externals/v8"              : "https://chromium.googlesource.com/v8/v8.git@5f1ae66d5634e43563b2d25ea652dfb94c31a3b4",
  "third_party/externals/wuffs"           : "https://github.com/GoogleDepends/wuffs.git@4080840928c0b05a80cda0d14ac2e2615f679f1a",
  "third_party/externals/zlib"            : "https://github.com/GoogleDepends/zlib@47af7c547f8551bd25424e56354a2ae1e9062859",
 
  "../src": {
<<<<<<< Updated upstream
    "url": "https://chromium.googlesource.com/chromium/src.git@ca9862fcfe55fca87894ecfd82fe53ab5da4365b",
=======
    "url": "https://chromium.googlesource.com/chromium/src.git@d086f1bdb67d4d54ba424d42d01eb256c9a3765f",
>>>>>>> Stashed changes
    "condition": "checkout_chromium",
  },
}
 
recursedeps = [
  "common",
  "../src",
]
 
gclient_gn_args_from = 'src'