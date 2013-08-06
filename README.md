Chef Connectivity Tester
========================
This repo contains a small Ruby script that can be used to test your connection to Opscode's Chef Server. This is very useful for training courses, to ensure you have met all the pre-requisite steps.


Assumptions
-----------
- You are using Opscode's omnibus installer at the default location
- You have successfully registered for Hosted Chef and downloaded your Starter Kit
- **You are running these commands from inside your Starter Kit chef-repo**


Usage
-----
1. Download the `check` script inside the `bin` directory of this repo
1. Move the `check` script into your `chef-repo`
1. Execute the script from a terminal from within your chef-repo:

        $ /opt/chef/embedded/bin/ruby check

    If you are using Windows, your path is slightly different:

        $ C:/opscode/chef/embedded/bin/ruby.exe check

This will test some common endpoints when working with Chef, such as:

- Connecting to GitHub
- Connecting to a Chef Server
- Downloading a Cookbook
- Establishing an SSH connection


Development
-----------
1. Fork/clone the repository on GitHub
2. Submit patches as Pull Requests


License & Author
----------------
- Author:: Seth Vargo <sethvargo@gmail.com>

```text
Copyright: 2013, Opscode, Inc

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0
Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
```
