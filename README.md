Install a set of tools to use in for the Osteporosis use case in INDIGO-DC.
===========================================================================

Install the BVLC Caffe application [1] and Octave [2].


Role Variables
--------------

The variables that can be passed to this role and a brief description about them are as follows:

	# Git Branch/Tag to download
	EUBIOSTEO_CAFFE_TAG: master
	# Directory to install the app
	EUBIOSTEO_CAFFE_ROOT: /opt/caffe


Example Playbook
----------------

This an example of how to install the application:

In the "Worker Nodes"
```yml
  roles:
    - { role: 'indigo-dc.eubiosteo' }
```

License
-------

Apache Licence v2 [3]

[1] https://github.com/BVLC/caffe

[2] https://www.gnu.org/software/octave/

[3] http://www.apache.org/licenses/LICENSE-2.0

