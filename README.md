# image-build-cilium-image-tools

```
for i in compilers bpftool iproute2 llvm; do
	make image-build-$i image-push-$i image-manifest-$i;
done
``` 
