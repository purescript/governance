# PureScript governance

## Purpose

The core PureScript GitHub organization (<https://github.com/purescript>)
exists to maintain and develop:

*   The PureScript language (as defined by the implementation in the compiler
    repository, `purescript/purescript`), and the compiler itself
*   The PureScript core libraries (that is, the libraries under the
    `purescript` org on GitHub)
*   The PureScript website infrastructure (purescript.org, Try PureScript,
    Pursuit)
*   Documentation
*   Package Sets

## Project Values

*   PureScript is industrially focused; it is not a vehicle for programming
    language research. Consequently, stability is a high priority. Feature
    requests which have a large impact on downstream code are unlikely to be
    accepted.
*   Prefer fewer, more powerful features to many special-purpose ones. With a
    smaller feature set, things are easier to document, the implementation is
    easier to understand and work with, and features are less likely to
    interact poorly with one another.
*   Prefer to move slowly and consider decisions carefully, especially if they
    are likely to have a long-term impact.
*   If it is possible to adequately solve a need downstream of the compiler
    and/or core libraries, we are unlikely to add features for solving that
    need inside the compiler and/or core libraries.

## Roles

### Core Team Members

The core organization team members lead the development of the language, compiler,
and core libraries. Since the language is defined by its implementation, the
compiler project and associated responsibilities are what largely shape its
direction and development.

The core organization team members are:

*   Harry Garrood (@hdgarrood)
*   Gary Burgess (@garyb)
*   Liam Goodacre (@LiamGoodacre)
*   Christoph Hegemann (@kritzcreek)
*   Hardy Jones (@joneshf)
*   Nathan Faubion (@natefaubion)

Core team members have demonstrated a long-term commitment to maintaining the
compiler, maintaining the standard library, and engaging with the language
community as a whole.

Core team members are expected to use their privileges responsibly, in order to guide
the development of the language, compiler, and core libraries in a way that
they feel best serves the community as a whole.

Core team membership is not predicated on responding to issues or pull requests in
any given timeframe; core team members may choose to involve themselves in the
development of the language, compiler, and libraries to whatever extent they
wish to. The reasoning for this is that we don't want any given maintainer to
feel pressured to do things that their life and schedules don't permit.

### Core Collaborators

Core team members may extend commit access on a project basis to those that have
expressed interest in maintaining a subset of the organization. Collaborators
include:

*   Alex Berg (@chexxor) - Documentation, Infrastructure
*   Thomas Honeyman (@thomashoneyman) - Infrastructure
*   Justin Woo (@justinwoo) - Package Sets
*   Fabrizio Ferrai (@f-f) - Package Sets

Collaborators are encouraged to help out with maintenance in any of the
following ways (or however else they see fit):

*   Merging PRs if they are ready to be merged (see below)
*   Managing the issue tracker (labelling, closing, or otherwise tidying up
    issues)
*   Discussing proposed features or bug reports
*   Sending PRs
*   Reviewing PRs

### Role Changes

*   Core team members may choose to step down and become core collaborators, or choose to leave the organization entirely, at any time.
*   Core collaborators may be promoted to core team members at the discretion of the rest of the core team members.

## Making Decisions

Most decisions which directly concern the language, compiler, or core libraries
should receive the approval of the core team members. For example, this would apply
to:

*   Feature requests
*   Concerns raised during pull request review
*   Adding new collaborators
*   Promoting collaborators to core team members
*   Changes to governance

For a decision to be made, it should receive the approval of all core team members
who choose to participate in the discussion. In essence, every core owner has a
veto (which they are expected to use responsibly).

Not all core team members are required to participate in every discussion -- it is
expected that most discussions will only involve a subset of the core team members.
Before any particular decision is finalized, sufficient time should be given so
that people have an opportunity to object, especially for decisions which would
be difficult to reverse later. In general, the length of time that is
considered "sufficient" depends on the magnitude of the decision, and core
core team members are expected to use their judgement. If a month has passed since the
first approval by a core owner, and no other core team members have objected in that
time, a decision can always be considered to have been approved.

Core team members have the final say in decisions, although they are expected to be
receptive to the needs of the wider community.

## Pull Requests

Pull requests on the compiler and core library repositories should receive
approving code reviews from at least two core team members before merging. For pull
requests which have been made by core team members, only one other core owner's
approval is required.
