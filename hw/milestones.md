# Basic milestones for the capstone project

When working with a large-scale open source project, there are five
basic milestones that should be achieved before making meaningful
contributions to the project:

1. User install
2. Developer install
3. Deploy changes
4. Run the tests
5. Fail some tests

Each of these is described in a separate section below.

## User install

A *user install* of a project is an installation for using the
product. For some projects, the user install is minimal or
nonexistent. For example, an H/FOSS project that is available to users
as a public website does not have any meaningful user install process.

## Developer install

A *developer install* of a project is an installation for altering or
improving the product. This will typically involve: downloading source
code, software frameworks and libraries; compiling the source;
deploying and executing the compiled product. The difficulty of
developer installs varies enormously between projects. Some developer
installs can be completed within a few minutes. For certain projects,
however, it has required days or weeks to complete a developer
install.

## Deploy changes

The *deploy changes* milestone consists of making one or more small
but non-trivial changes to the project code, then deploying the
changes and observing them in the new version of the product. The
objective is to verify that you have the skills needed to recompile
and deploy altered versions of the product. It may be wise to make
several different kinds of changes in various parts of the code base.

## Run the tests

Most H/FOSS projects have a suite of tests that can be run to verify
the correctness of the code. Some projects have a workflow that
automatically runs these tests on any submitted code. Some projects
require that the tests pass before a pull request can be
submitted. The *run the tests* milestone consists of running the test
suite on the current code base without any changes. It is worthwhile
to note any difficulties or problems in running the tests: it is not
unusual for some tests to fail even on the stable main upstream branch
of the code. If that is the case, it can be useful to verify with the
project community that this is the expected behavior. It will be much
easier to submit contributions if the testing infrastructure is well
understood, and if any already-failing tests have been identified.

## Fail some tests

Once the testing infrastructure is understood and the test suite can
be run on the upstream version of the code, the next milestone is to
*fail some tests*. This means you deliberately make one or more small
changes to the code, which will cause one or more tests to fail. Then,
run the test suite and verify that the expected tests have
failed. Then, change the code back to its original state and verify
that the tests are now succeeding. The objective is to gain high
confidence that you understand the testing infrastructure and that you
will be able to use it for discovering problems with your future
contributions. It may be worthwhile to fail several different kinds of
tests in different areas of the code base.
