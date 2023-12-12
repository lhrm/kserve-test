```
oras push quay.io/mmortari/mnist:v1.nb20231206162408 v1.nb20231206162408/mnist.onnx
oras push quay.io/mmortari/mnist:v2.nb20231206162618 v2.nb20231206162618/mnist.onnx
oras push quay.io/mmortari/v20231206163028 v20231206163028/mnist.onnx
```

Signatures:
```
cosign sign quay.io/mmortari/mnist:v20231206163028
cosign tree quay.io/mmortari/mnist:v20231206163028
```

```
📦 Supply Chain Security Related artifacts for an image: quay.io/mmortari/mnist:v20231206163028
└── 🔐 Signatures for an image tag: quay.io/mmortari/mnist:sha256-6e0fd6a7375fd66f9e0dfa6470dd58293fdce46594913902cacd50e96c1300c7.sig
   └── 🍒 sha256:088b0127edef73236862fa648ee36df6428b113f559873284697c69045658fb6
```

```
oras manifest fetch quay.io/mmortari/mnist:v1.nb20231206162408
oras manifest push quay.io/mmortari/mnist:v1.nb20231206162408 v1.nb20231206162408/manifest.json
```