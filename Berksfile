#
# Author:: Noah Kantrowitz <noah@coderanger.net>
#
# Copyright 2013, Balanced, Inc.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
# http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#

source 'https://api.berkshelf.com'

metadata

# When bootstrapping, we need to reference our cookbooks more manually
cookbook 'poise', github: 'poise/poise'
cookbook 'citadel', github: 'balanced-cookbooks/citadel'
cookbook 'balanced-citadel', github: 'balanced-cookbooks/balanced-citadel'

group :test do
  cookbook 'apt'
  cookbook 'balanced-berkshelf-api_test', path: './test/cookbooks/balanced-berkshelf-api_test'
end
