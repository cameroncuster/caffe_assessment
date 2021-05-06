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
- Outline the issues/commit-log
- REVIEW THE JEKYLL DOCUMENTATION

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
issue and commit logs which accentuates software reliability. The documentation
of the software alone is a reason to use the Caffe software in the project.

The official documentation is supported by Jekyll and can be made with

---
scripts/build_docs.sh
---

and the documentation can be viewed with

---
http://0.0.0.0:4000
---

Tutorials and examples are documented close to where they live allowing for
the documentation to be very accessible. The examples provide a step by step
process for using the software among a variety of applications. The tutorial
gives the same level of attention and detail to using Caffe. The software was
developed with an eye for detail which is a strong indicator of high quality
software.

## Ease of use ##
1. 1 hour clone and use the application
- A detailed write-up about the install and build process of the application is
linked in the
[install documentation](http://caffe.berkeleyvision.org/installation.html)

2. 1 day to make and run test suite
- cloning the application and making the tests passes is a well-documented
process which can be completed in under an hour on most of the platforms because
the installing and build process is documented making the tests is as simple as

---
% make runtest
---

3. 1 week to integrate with my application
- I would estimate with accuracy and precision that (depending on the project)
Caffe could be easily integrated with most projects

## Support ##
Community support is widely available for the Caffe software with a Gitter
online chat service available for users of the Caffe software. The chat service
is well monitored and easily accessible in the documentation (README) of the
Caffe project repository. A Caffe users group is also available for Gmail users,
which details changes and updates to the Caffe software along with an abundance
of questions about the software with developer and contributor answers.

In addition to the variety of community support available for the software users
is a running document of Issues. Which are each meticulously documented with
navigable commit logs and updated information about the software and recent
changes.

The quality of the documentation along with the support allows users to easily
identify how the product can be used and what platforms the product is available
for, and what extensions can be used to make the product compatible with your
platform. Platforms Caffe advertises to be compatible with include: Intel
(optimized for CPU and multi-node computing), OpenCL for AMD or Intel devices,
and Windows Caffe.

A tutorial detailing the build and deployment of the product allows users to
quickly and easily get Caffe up and running with their support for a variety of
platforms. The Caffe tutorial also includes a tour of the product which
accelerates the time and training required for integrating the product with your
application. The link to the second Caffe tutorial returns a 404 (Not Found).
This is a result of lack of attention to detail which may or may not indicate
the same attention and care in the source code. The incorrect link on the GitHub
tutorial page may also be result of the Google API incorrectly handling the
browsers queries as the tutorials are Google Slides presentations. The first
tutorial is well-formatted, easy to follow, and accessible from the README.

The tutorial addresses reasons to use the Caffe product, the technology utilized
by Caffe, the companies who use Caffe (known as "Caffinated Companies"), the
fine-tuning the software for specific application, the transferability of Caffe
features across various software applications, the Caffe support and community,
and the design and development practices for the software product.

Caffe is maintained frequently by both contributors and software developers,
making the source code well-supported and reliable.

The Caffe software is well-supported and offers multiple platforms to connect
with the community and ask questions. The software also leverages a well-written
tutorial allowing users to build and install the application quickly. One of the
two tutorial URLs in the Caffe tutorial README was not working properly, but
this does not appear to be a reflection of Caffe's support or software
development practices. Caffe is a well-supported application which is a reason
to integrate the software into your own product.

## Testing ##

## Dependencies ##
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
