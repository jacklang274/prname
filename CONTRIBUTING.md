Contributing to psutil project
==============================

Issues
------

* The issue tracker is for reporting problems related to the program code.
* Please do not open issues asking for support. For questions use the forum
  at https://groups.google.com/g/psutil.
* Before submitting a new issue, search if there are existing issues for the
  same topic.
* Make sure that you are testing against latest psutil version.
* If your report is not attended in a while, be please patient.
* To report a security vulnerability, use the
  [Tidelift security contact](https://tidelift.com/security).
  Tidelift will coordinate the fix and disclosure of reported problems will be
  published after a bugfix release is published.

Pull Requests
-------------

* The PR system is for fixing bugs or make enhancements related to the program
  code.
* If you whish to implement a new feature or add support for a new platform,
  discuss it first (on the issue tracker, the forum or via private email).
* Please do not submit incomplete PRs. If you're looking for direction or want
  to explore a new idea, discuss it first (on the issue tracker, the forum
  or via private email).
* Write a test which shows that the bug was fixed or that the feature works as
  expected.
* Take a look at the [DEVGUIDE](https://github.com/giampaolo/psutil/blob/master/docs/DEVGUIDE.rst)
  which provides more detailed info on how to hack on psutil.
* Sign your work.

Sign your work
--------------

* The [DCO](https://github.com/giampaolo/psutil/blob/master/docs/DCO)
  (Developer Certificate of Origin) is a lightweight way for contributors to
  certify that they wrote or otherwise have the right to submit the code they
  are contributing to the project.
* Contributors sign-off that they adhere to these requirements by adding a
  ``Signed-off-by:`` line to commit messages, e.g.:

    ```
    This is my commit message

    Signed-off-by: Random J Developer <random@developer.example.org>
    ```
* Git has a ``-s`` command line option to append this automatically to your
  commit message:

    ```
    $ git commit -s -am 'This is my commit message'
    ```
* You must use your real name (sorry, no pseudonyms or anonymous contributions).
* There is a [Github Action](https://probot.github.io/apps/dco/) check,
  integrated in the PR system, which will help you with this when a PR is
  opened or updated.
