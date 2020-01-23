# git-subtree-hash

A fork of git-subtree using associative arrays as internal cache. Besides being slightly faster than the default filesystem based implementation it solves an issue where cache files are not removed properly.

## Requirements

Associative arrays are available starting with Bash version 4.x and later.

## Changes

- Added global CACHE
- Removed all subshell invocations which require access to CACHE
- Added force push option


# Authors

[Tomas Camin](https://github.com/tcamin) ([@tomascamin](https://twitter.com/tomascamin))


# License

This fork is distributed under the terms of the GNU General Public License version 2. See the LICENSE file for more info.