# Signify (OpenBSD) Python Wrapper
Simple Python wrapper for OpenBSD's signify tool.

## Usage
Start by adding this repository as a submodule in your own:
```
$ git submodule add -b main git@github.com:deni/python-signify-wrapper.git signify_wrapper
```

Imports into directory signify_wrapper pga. python

Make sure environment variable is set. export SINGNIFY_BINARY:blahblah

Can be found with:
which signify

Then it can be imported in Python using:
```
import signify_wrapper
```

Remember to add install signify-openbsd
```
git clone --recurse-submodules git@github.com:deni/python-signify-wrapper.git signify_wrapper
```
```
git submodule -b abranch -- /url/of/submodule/repo
```
```
git submodule update --remote --recursive
```

## Example
