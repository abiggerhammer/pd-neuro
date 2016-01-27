not a lot to see here so far:
* a python script that reads modeeg P2 data off the openeeg and bangs it out over OSC
* a puredata patch that reads from the OSC server, splits out the EEG channels, and emits a signal when (right alpha / left alpha) > 1.1
* Dias, Alvaro, and Van Deusen, Adrian. _A new neurofeedback protocol for depression._ Span J. Psychol 2011 May; 14(1):374-84. http://www.ncbi.nlm.nih.gov/pubmed/21568194
* an excerpt from an email conversation with the second author above

dependencies:
* [Pure Data](http://puredata.info/)
* [Python](https://www.python.org)
* [pyOSC](https://pypi.python.org/pypi/pyOSC) (use --pre if installing with pip)
* the [Mr. Peach](http://puredata.info/downloads/mrpeach) [net](https://svn.code.sf.net/p/pure-data/svn/trunk/externals/mrpeach/net/) and [osc](https://svn.code.sf.net/p/pure-data/svn/trunk/externals/mrpeach/osc/) libraries (pd-mrpeach and pd-mrpeach-net on debian)
