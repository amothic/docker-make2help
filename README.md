# docker-make2help
Scratch-based image with just make2help

## Usage
```console
docker run --rm -v `pwd`:/make2help amothic/make2help
```

```Makefile
## Get help on a command
help:
	@docker run --rm -v `pwd`:/make2help amothic/make2help $(MAKEFILE_LIST)
```

## License
[MIT License](LICENSE)
