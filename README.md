# Unit Tested C Template
Make the LSP less angry
```
cmake -DCMAKE_EXPORT_COMPILE_COMMANDS=YES .
```
To run the unit tests:
```
make run_tests
```
To pull this template with git do a shallow clone and then detach the remote
```sh
git clone --depth 1
git remote rm origin
```
You can now use your own remote
