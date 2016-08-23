Quasselcore in Docker
=====================

[Quassel Core](http://www.quassel-irc.org) is a bouncer like IRC client daemon, you can access with an GUI application. While the core stays connected all the time.

## Running

```shell
docker run --name quasselcore \
    -v /data/docker/quasselcore:/var/lib/quassel \
    -p 4242:4242 \
    lazyfrosch/quasselcore
```

## Contributing

You are welcome to contribute, please open a issue or PR to input your suggestions.

## License

   Copyright (c) 2016 Markus Frosch <markus@lazyfrosch.de>

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
