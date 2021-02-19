# Go-Faiss

[Faiss](https://github.com/facebookresearch/faiss) is a library for efficient similarity search and clustering of dense vectors.

Go-Faiss is go library use Faiss directly

	Faiss Version v1.6.3
## Install
### Build from source
#### Build Faiss
https://github.com/facebookresearch/faiss/blob/v1.6.3/INSTALL.md
#### Build C interface
https://github.com/facebookresearch/faiss/blob/v1.6.3/c_api/INSTALL.md

### Download from github

```
	git clone https://github.com/ruslan-casafari/go-faiss
	mv go-faiss/lib/libfaiss_c.so /usr/local/lib/libfaiss_c.go
```

## Use in go

```
    import "github.com/ruslan-casafari/go-faiss/faiss"
```
### Example

In example directory, you can find example.go

1. Generate some data and create a flat index 

2. Then add vectors to index 

3. Generate a new vectors for search

4. Search the top 10 vector


## Test

```
    go test
```
