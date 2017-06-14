Backup v4.xa
===========

[![Code Climate](https://codeclimate.com/github/backup/backup.png)](https://codeclimate.com/github/backup/backup)
[![Build Status](https://travis-ci.org/backup/backup.svg?branch=master)](https://travis-ci.org/backup/backup)
[![Join the chat at https://gitter.im/backup/backup](https://badges.gitter.im/Join%20Chat.svg)][Gitter]

This is a variation (clone) of [the backup gem](https://github.com/backup/backup) _without **Qiniu** storage._  The [qiniu gem ](https://github.com/qiniu/ruby-sdk) has a dependency on an old version of json, and this blocks the backup gem from being updated to more current versions of ruby.
This variation removes the use of the qimiu gem and so removes Qiniu as a storage option.  

Thus this variation of the backup gem can be used with more current versions of ruby.
The version number has _"a"_ appended as a clue that this is a variation of the orginal.

---


_What follows is from the original Readme:_

Backup is a system utility for Linux and Mac OS X, distributed as a RubyGem, that allows you to easily perform backup
operations. It provides an elegant DSL in Ruby for _modeling_ your backups. Backup has built-in support for various
databases, storage protocols/services, syncers, compressors, encryptors and notifiers which you can mix and match. It
was built with modularity, extensibility and simplicity in mind.

[Installation][] &middot; [Release Notes][] &middot; [Documentation][] &middot; [Issues][] &middot; [Features][] &middot; [Chat][Gitter]

Please use the Backup features [issue tracker][Features] to suggest new features.
Only use the Backup gem [issue tracker][Issues] for bugs and other issues.
We're also available on [Gitter] for questions and problems.

**Copyright (c) 2009-2016 [Michael van Rooijen][] ( [@mrrooijen] )**  
Released under the **MIT** [LICENSE](LICENSE).

[Installation]:  http://backup.github.io/backup/v4/installation
[Release Notes]: http://backup.github.io/backup/v4/release-notes
[Documentation]: http://backup.github.io/backup/v4
[Issues]: https://github.com/backup/backup/issues
[Features]: https://github.com/backup/backup-features/issues
[Gitter]: https://gitter.im/backup/backup?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge
[Michael van Rooijen]: http://github.com/mrrooijen
[@mrrooijen]: http://twitter.com/mrrooijen
