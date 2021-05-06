# Assessment of Caffe #
Written assessment of the deep learning framework "made with expression, speed,
and modularity." Caffe was developed by Berkeley AI Research (BAIR) in
association with The Berkeley Vision and Learning Center (BVLC) alongside
community contributors.

## Licensing ##
License is the BSD 2-Clause license.

The official [BSD 2-Clause license](LICENSE)

- The BSD 2-Clause license is a Permissive License which allows the author to
retain copyright for the purpose of disclaiming warranty and requiring
attribution of their software. The Permissive License allows for any form
redistribution and modification.
- The license prevents me from relying on a software warranty to ensure the
software is working as intended, and without fault.

## Documentation ##
The documentation contains descriptive information about the entire application
from making and building the application on various platforms to developing and
contributing to the software to outlining the multitude of applications for the
software.

Caffe is equipped with a well-written tutorial describing everything from
installing and building the software to using and integrating the software with
my application.

Contribution to Caffe is also well-outlined in the documentation. Contribution
is laid out nicely for all developers by all requirements to contribute to the
software. The requirements for contribution even specify versioning, feature
branching, rebasing practices, and **testing**. This emphasizes that Caffe has
utilized good software development practices, and as a result has produced a
reliable product which is highly reputable because of versioning, branching
techniques, and required testing. Coding style and technique are also emphasized
in contribution. For example Caffe follows
[Google C++ style](https://google.github.io/styleguide/cppguide.html) and
[Google python style](https://google.github.io/styleguide/pyguide.html) with
[PEP 8](https://legacy.python.org/dev/peps/pep-0008/). Evidently the coding
standard, software development practices, and requirements for contribution are
satisfactory for considering Caffe to be included in the project.

Caffe even emphasizes their care for code which reads like well-written prose,
in saying, "Remember that “a foolish consistency is the hobgoblin of little
minds,” so use your best judgement to write the clearest code for your
particular case." The Caffe developers clearly made the decision to prioritize
understandable and clean code.

Caffe's emphasis on good software development practices is well reflected in
the commit and issue logs. All pull-requests are 'verified' and all commits
point to a specific change in the application. Issues resemble the commit log in
their reliability because they are very specific with detailed solutions
which are documented in their entirety. Everything is accounted for in the
issue and commit logs which accentuates software reliability.

The official documentation is supported by Jekyll and can be made with

```
scripts/build_docs.sh
```

and the documentation can be viewed with

```
http://0.0.0.0:4000
```

Although the instructions for building the documentation are clear, I was unable
to actually view the documentation.

Tutorials and examples are documented close to where they live allowing for
the documentation to be very accessible. The examples provide a step by step
process for using the software among a variety of applications. The tutorial
gives the same level of attention and detail to using Caffe. The software was
developed with an eye for detail which is a strong indicator of high quality
software.

While the Caffe team claims to keep tutorials and examples documented close to
where they live there is little to no internal documentation found in the Caffe
source code. The code appears to have lots of tests written for it in the
source, but there is no documentation describing what any of the tests are
actually testing. At the surface the project appears to be well documented and
satisfactory of coding standard, but seeing the actual source code the Caffe
project does not appear to be well-documented. The claims made by the Caffe team
about their standards for contribution, coding style, and testing give the
appearance of a great software product; however, the source code yeilds a
different appearance. The code in the source is not well-documented, descirbed,
or human readable. All of the code is difficult to understand and not "self-
describing."

- The code appears to be littered with typos as many of the commit messages
indicate that simple typing errors are being corrected with code spell checking
software

- The last actual update to the software which was not a pull request to fix a
typo was the addition of a "clip layer" to the software on Aug. 17, 2018.

## Ease of use ##
1. 1 hour clone and use the application
- A detailed write-up about the install and build process of the application is
linked in the
[install documentation](http://caffe.berkeleyvision.org/installation.html)
- Building on Windows appears to be impossible as the CUDNN8 software is no
longer supported.

2. 1 day to make and run test suite
- Tests can not be made because the Docker version used by the application and
the CUDNN8 software is no longer supported by Caffe

```
make runtest
```

3. 1 week to integrate with my application
- I do not think Caffe could be integrated successfully with any software
application as the software is no longer supported by it's dependencies or
platforms. I found a blog post on the Caffe community page describing how the
software can be built with external packages, but also could not get the
external packages to work.

## Support ##

## Testing ##

## Dependencies ##
- Docker integration is Version 6 while the latest Docker release is version 8

Dependencies defined in the python/requirements.txt
- cython / cython
- h5py / h5py
- ipython / ipython
- matplotlib / matplotlib
- networkx / networkx
- nose-devs / nose
- numpy / numpy
- pandas-dev / pandas
- python-pillow / Pillow
- protocolbuggers / protobuf
- paxan / python-dateutil
- google / python-gflags
- yaml / pyyaml
- scikit-image / scikit-image
- scipy / scipy
- benjaminp / six

Dependencies defined in the web_demo/requirements.txt
- pallets / flask
- numpy / numpy
- pandas-dev / pandas
- python-pillow / Pillow
- yaml / pyyaml
- tornadowed / tornado
- pallets / werkzeug

## Conclusion ##
I would not include Caffe in my senior design project because the software has
practically been discontinued. On the surface the software appears to have a
strong community with supporting documentation and good software development
standards, but realistically the software is not-well maintained, has no
internal documentation, and is full of unreadable code. Using the software to
integrate into a senior design project would be a poor design desicion and
result in a lot of unecessary headache for the project as indicated by a few of
the recent chats in the community channel.
