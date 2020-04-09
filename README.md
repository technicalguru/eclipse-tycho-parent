# Tycho Maven OSS Parent

## Overview
This is a simple Maven POM parent for OSS projects with Eclipse/Tycho. It defines the Tycho version, Eclipse and OSS repositories and basic build steps. Please notice that Eclipse RCP projects itself are not published via Maven but P2 repositories.

## License
_Tycho Maven OSS Parent_ is licensed under [GNU LGPL 3.0](LICENSE.md).

## Usage#

```
	<parent>
		<groupId>eu.ralph-schuster</groupId>
		<artifactId>rs.rcpplugins.tycho-parent</artifactId>
		<version>1.4.0</version>
	</parent>
```

## Contribution

Report a bug or request an enhancement at the [GitHub Issue Tracker](https://github.com/technicalguru/eclipse-tycho-parent/issues).
