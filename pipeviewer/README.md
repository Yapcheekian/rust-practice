```bash
dd if=/dev/urandom bs=1024 count=128 of=myfile

cargo build

cat myfile | target/debug/pipeviewer > myfile2
```
