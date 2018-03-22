# sslyze provided through a docker container

## Usage

```bash
docker run -it --rm mikeyyuen/sslyze --regular ss1.slipstreamproject.com:443
```

## Building & helper script

Check out https://github.com/mikeyyuen/sslyze-docker

To build the container

```bash
./build.sh
```

Helper script to wrap sslyze

```bash
./sslyze --regular ss1.slipstreamproject.com:443
```

