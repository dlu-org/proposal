# dlu RFCs

## Introduction

Please read the dlu-org organization's [governance rules](#TODO) and [contribution guidelines](#TODO) before proceeding.

This repo contains the design proposals for substantial feature changes for
dlu-org that need to be designed upfront. The goal of the upfront design process
is to:
- Provide increased visibility to the community on upcoming changes and the design considerations around them.
- Provide ability to reason about larger “sets” of changes that are too big to be covered either in an Issue or in a PR.
- Establish a consistent process for structured participation by the community on large changes, especially those that impact multiple runtimes and implementations.

## Prerequisites

This process needs to be followed for any significant change to dlu that
needs design.
Changes that are considered significant can be:

- [README_TODO more details.](#TODO)   

## Process

1. Fork the repo and copy the template [DLU-TEMPLATE.md](DLU-TEMPLATE.md).  

2. Rename it to ``$CategoryName-$Summary``, eg.: ``A6-client-retries.md`` (see
  category definitions below)
   - For language-specific proposals, include the name of the language:
     ``L##-$Language-$Summary``.  Canonical names: `core`, `cpp`, `csharp`, `go`,
     `java`, `node`, `objc`, `php`, `python`, `ruby`.

3. Write up the RFC.

4. Submit a Pull Request.

5. Someone from dlu team will be assigned as an APPROVER as part of this
review. [README_TODO more details.](#TODO)   

6. For at least a period of 10 business days (the minimum comment period),
it is expected that the OWNER will respond to the comments and make updates
to the RFC as new commits to the PR. [README_TODO more details.](#TODO)

7. If there is consensus as deemed by the APPROVER during the comment period,
the APPROVER will mark the proposal as final and assign it a dRFC number. [README_TODO more details.](#TODO)


## APPROVER

- By default ``README_TODO`` is the approver unless another approver is assigned
on a per-proposal basis.
- If the assigned APPROVER and the OWNER cannot satisfactorily settle an issue,
the final APPROVER is still ``README_TODO``.

## Proposal Categories
The proposals shall be numbered in increasing order.

- [README_TODO more details.](#TODO)  

## Proposal Status

1. Every uncommitted proposal candidate starts off in the ``Draft`` state.

2. After it accepted for review and posted to the group, it enters the
``In Review`` state.

3. Once it is approved for submission by the arbiter, it goes into the
``Final`` state. Only minor changes are allowed (what qualifies as minor is
left to the APPROVER).

4. If a proposal needs to be revisited, it can be moved back to the ``Draft``
or ``In Review`` state. This can happen if issues are discovered during
implementation. At which point, the review process as described above must be
followed.

5. Once a proposal is ``Final`` and if it has been implemented by a language,
it can be updated to a status of ``Implemented`` with the implementing
languages listed. (Listing versions is not required.)

## TODO 

- Thank you for your attention, we will finish it as soon as possible.


