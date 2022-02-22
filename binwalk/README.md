# Firmware Analysis Tool

Binwalk with selected dependencies.

## Supported tags and respective `Dockerfile` links

* `latest` 
([*binwalk/Dockerfile*](https://gitlab.com/riverloopsecurity/dockerfiles/blob/master/binwalk/Dockerfile))

## Input

Instead of being used directly at the command line like other good versions such as [circan/binwalk](https://gitlab.com/CinCan/tools/-/tree/master/stable/binwalk), this Dockerfile is intended to drop the user into a shell where they can use it and explore/tweak further.

## Output


## Usage

```
docker build . -t riverloopsec/binwalk-standalone
docker run -it --rm -v$(PWD):/workdir riverloopsec/binwalk-standalone
```

## Project homepage

https://github.com/ReFirmLabs/binwalk

## License

MIT License


