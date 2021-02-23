# ppmix

FreeBSD/OSS per program volume control (or Per Program MIX)

# USAGE

```
ppmix [process name] [[pcm/rec] [+/-]left[:right]] 
```

# EXAMPLES

```
ppmix
ppmix myprog 10
ppmix myprog
ppmix myprog rec 15
ppmix myprog pcm 36
ppmix myprog +17
```

# LICENSE

Copyright 2021 Ivan Kovmir

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
