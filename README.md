# Overview

## Facter 2.x -> 3.x

Facter migrated core functionality to C instead of Ruby.  As a result, many of the utils that were not meant to be public are now gone.  This module preserves the utils that were available in facter v2.4.6 to preserve custom facts that need them.