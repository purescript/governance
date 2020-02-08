# Purpose

The core PureScript GitHub organization exists to maintain and develop:

*   The PureScript language (as defined by the implementation in the `purescript` compiler project).
*   The PureScript standard library (`purescript-*` projects).
*   The PureScript website infrastructure (purescript.org, Try PureScript, Pursuit)
*   Documentation
*   Package Sets

# Project Values

- PureScript is industrially focused; it is not a vehicle for programming language research. Consequently, stability is a high priority. Feature requests which have a large impact on downstream code are unlikely to be accepted.
- Prefer fewer, more powerful features to many special-purpose ones. With a smaller feature set, things are easier to document, the implementation is easier to understand and work with, and features are less likely to interact poorly with one another.
- Prefer to move slowly and consider decisions carefully, especially if they are likely to have a long-term impact.
- If it is possible to adequately solve a need downstream of the compiler and/or core libraries, we are unlikely to add features for solving that need inside the compiler and/or core libraries.

# Core Owners

Organization ownership is primarily predicated on having commit access to the
core compiler. Since the language is defined by its implementation, this
project and associated responsibilities are what largely shape its direction
and development.

The core organization owners are:

*   Harry Garrood (@hdgarrood)
*   Gary Burgess (@garyb)
*   Liam Goodacre (@LiamGoodacre)
*   Christoph Hegemann (@kritzcreek)
*   Hardy Jones (@joneshf)
*   Nathan Faubion (@natefaubion)

Owners have demonstrated a long-term commitment to maintaining the compiler,
maintaining the standard library, and engaging with the language community as
a whole.

# Core Collaborators

Core owners may extend commit access on a project basis to those that have
expressed interest in maintaining a subset of the organization. Collaborators
include:

*   Alex Berg (@chexxor) - Documentation, Infrastructure
*   Thomas Honeyman (@thomashoneyman) - Infrastructure
*   Justin Woo (@justinwoo) - Package Sets
*   Fabrizio Ferrai (@f-f) - Package Sets
