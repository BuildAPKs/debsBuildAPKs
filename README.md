# debBuildAPKs

	Downgrading the version of \`ecj\` is a potential solution if a signal was generated while ecj was compiling.  Version ecj/stable,now 4.7.2-2 does not run very well; This might be solved through sharing here https://github.com/termux/termux-packages/pulls and https://github.com/termux/termux-packages/issues here.
	
	More information about keeping a system as stable as possible by downgrading a package when the need arrises is https://sdrausty.github.io/au here.
	
	`ecj_4.7.2-1` is far superior than the version currently in use.  It is included for convience in `buildAPKs/debs`.  Use `dpkg --purge ecj` followed by `dpkg --install ecj_4.7.2-1_all.deb` to downgrade to a more stable version.
