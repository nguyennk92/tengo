# Go La Tengo

Golang library for MySQL and MariaDB database automation

## Repo now archived

Skeema is a bootstrapped (self-funded) product, primarily built by an independent developer. The continued viability of Skeema's open source development is dependent on consulting services and commercial products; without these revenue sources, ongoing development is not possible.

Go La Tengo was designed as a reusable package in a separate repo, with the hope of building development momentum for use-cases *outside* of schema management. However, maintaining it as a separate repo is time-consuming: the codebase must be separately maintained, tested, versioned, and released; and then vendored inside of the Skeema CLI's repo.

Recently, one of the external users of the Tengo package -- a startup that has raised over $55 million USD -- has been building commercial schema management functionality that directly competes with Skeema as a whole. That company is now also building functionality that is specifically only offered in Skeema's commercial edition. This company's behavior **willfully and directly endangers the continued existence of Skeema**, and as a result of this, it is simply no longer viable to offer Go La Tengo as an independent repository. All functionality here has now been merged directly into the Skeema CLI's primary repo as an internal sub-package. As of 4 November 2021, this separate Tengo repo is now archived, and may be deleted entirely in the coming months.

The open source Community edition of the Skeema CLI remains available and maintained at this time, but in light of such blatant bad actors in the open source space, it is entirely possible its license may change to either BSL or AGPL in the future. In any case, most new feature development is focused on the closed-source commercially-licensed Premium edition at this time. 

## External Dependencies

* https://github.com/go-sql-driver/mysql (Mozilla Public License 2.0)
* https://github.com/jmoiron/sqlx (MIT License)
* https://github.com/VividCortex/mysqlerr (MIT License)
* https://github.com/fsouza/go-dockerclient (BSD License)
* https://github.com/pmezard/go-difflib/difflib (BSD License)
* https://github.com/nozzle/throttler (Apache License 2.0)
* https://golang.org/x/sync/errgroup (BSD License)

## Credits

Created and maintained by [@evanelias](https://github.com/evanelias).

Additional [contributions](https://github.com/skeema/tengo/graphs/contributors) by:

* [@tomkrouper](https://github.com/tomkrouper)
* [@efixler](https://github.com/efixler)
* [@chrisjpalmer](https://github.com/chrisjpalmer)
* [@alexandre-vaniachine](https://github.com/alexandre-vaniachine)
* [@mhemmings](https://github.com/mhemmings)

Support for stored procedures and functions generously sponsored by [Psyonix](https://psyonix.com).

Support for partitioned tables generously sponsored by [Etsy](https://www.etsy.com).

## License

**Copyright 2021 Skeema LLC**

```text
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```


