########################
Project Status
########################

TurboGears was first released in 2005. Due to that age, TurboGears has always had two branches of development
for a lot of time. We recommend new projects start on TurboGears2 which is the currently actively under development
branch of TurboGears.

Latest stable release: 2.3.0 - released Aug 25, 2013

Release announcement available at: https://plus.google.com/115723575598932631951/posts/Fw6mGKfBHjM

***************************
Contributing to TurboGears
***************************

All the TurboGears related projects are available on GitHub under the `TurboGears`_ account,
if you want to take a look at TurboGears source code you can start there.
In particular, we have several repositories for public use. The main ones are:

- `TG2.x Core (Git)`_ - The actual framework code lives here
- `TG2.x Devtools (Git)`_ - Useful tools used during development
- `TG2.x Docs (Git)`_ - The documentation repository

For continuous integration work, we use `Travis`_.

Development happens on two core branches: the ``development`` one where major changes for
the upcoming scheduled release happens and ``master`` branch which will point to the
current stable release. Minor bugfix releases are branched from master on demand and merge
back into the master branch when the release happens.

To create your development environment you can perform:

.. code-block:: bash

   virtualenv --no-site-packages ${HOME}/tg2env
   source ${HOME}/tg2env/bin/activate
   git clone git@github.com:TurboGears/tg2.git
   cd tg2
   python setup.py tgdevelop
   python setup.py tgtesting
   python setup.py tgnose

.. _`TG2.x Core (Git)`: https://github.com/TurboGears/tg2
.. _`TG2.x Devtools (Git)`: https://github.com/TurboGears/tg2devtools
.. _`TG2.x Docs (Git)`: https://github.com/TurboGears/tg2docs
.. _`Travis`: https://travis-ci.org/TurboGears/tg2
.. _`TurboGears`: https://github.com/TurboGears
