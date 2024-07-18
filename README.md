# HPC Managed Software

The research computing systems built and maintained by the University of Delaware Information Technologies' Research CyberInfrastructure group (UD IT-RCI) have a sizeable complement of software that are critical to a wide cross-section of applications.  Compilers, MPI libraries, and commonly-used components like Python or HDF5 are all examples of software that are part of the ongoing maintenance performed by IT RCI staff.

Changes to software — whether as new versions added, existing versions removed or modified — can have a butterfly effect on workflows and software that depend upon these packages.  If the default version of HDF5 is altered, for example, any existing software previously built by users against `hdf5/default` will now have its runtime environment altered (possibly with incompatibilities).  Notifying users of changes is thus an important step in preventing lost time and effort due to such issues and the inevitable confusion and debugging that they often yield.

This repository is designed to allow IT RCI staff to document software changes; users can either check the repository from time to time or *watch* the repository on Github and receive notifications.  A separate branch is present for each of the HPC systems to keep all per-system content uniquely-separated.
