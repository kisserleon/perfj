# Perfj

This project is based on Johannes Rudolph's work at [here](https://github.com/jrudolph/perf-map-agent)
I just make it more convenient to use.

## Build

    gradle releaseTarGz
or just run once

    gradle createWrapper
afterwards run

    ./gradlew releaseTarGz

## Usage

`PerfJ` is only work on jdk version with frame pointer enabled.

    bin/perfj record -e cycles -F 99 -g -p $pid sleep 5
    bin/perfj report --stdio

## License

This library is licensed under GPLv2. See the LICENSE file.
