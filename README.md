# JPowerFlow
a steady state electric power system power flow solver.

SCR# 917

https://jpowerflow.sourceforge.net/

The jpowerflow project's CVS data is in read-only mode. CVS is an old system for managing code. In order to access a CVS repository, you must install a CVS client.

The CVS data can be accessed as follows. You can run a per-module CVS checkout via pserver protocol:

cvs -z3 -d:pserver:anonymous@a.cvs.sourceforge.net:/cvsroot/jpowerflow co -P JPowerFlow
cvs -z3 -d:pserver:anonymous@a.cvs.sourceforge.net:/cvsroot/jpowerflow co -P JPowerFlow-Framework
cvs -z3 -d:pserver:anonymous@a.cvs.sourceforge.net:/cvsroot/jpowerflow co -P JPowerSim

You can view a list of files or copy all the CVS repository data via rsync (the 1st command lists the files, the 2nd copies):

rsync -a a.cvs.sourceforge.net::cvsroot/jpowerflow/
rsync -ai a.cvs.sourceforge.net::cvsroot/jpowerflow/ /my/local/dest/dir/

