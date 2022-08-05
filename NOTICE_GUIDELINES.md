# Third Party Code (NOTICE) Guideline

If a project's repository also contains files under other licenses or from other projects, their copyright statements, licenses, and any notices must be preserved in a `NOTICE.txt` file in the repo root.
Author and source metadata and links, a modification statement and the files covered must also be listed here.
See the [Spyder `NOTICE.txt`](https://github.com/spyder-ide/governance-and-guidelines/blob/main/PROJECT_LICENSE.md) for an example, and read on for more information, instructions and a template.

All files or groups of files, including source code, images, icons, and other assets, that originate from projects outside of the Spyder organization (regardless of the license), must be approved by the Spyder core developers and documented here.
Always check with the core team before attempting to add content from an external project, and only do so when necessary.


## Permissible Licenses

Code considered for inclusion must be under a permissive (i.e. non-copyleft) license, particularly as the following (in order of preference, with SPDX identifiers):

* [MIT (Expat)](https://spdx.org/licenses/MIT.html) - `MIT`
* Public domain, preferably, [CC0](https://spdx.org/licenses/CC0-1.0.html) - `CC0-1.0`
* [BSD 2-clause ("Simplified BSD")](https://spdx.org/licenses/BSD-2-Clause.html) - `BSD-2-Clause`
* [BSD 3-clause ("New" or "Modified BSD")](https://spdx.org/licenses/BSD-3-Clause.html) - `BSD-3-Clause`
* [Apache License 2.0](https://spdx.org/licenses/Apache-2.0.html) - `Apache-2.0`
* [ISC license](https://spdx.org/licenses/ISC.html) - `ISC`

Additionally, external assets (fonts, icons, images, sounds, animations) can generally be under one of the following weak-copyleft and content licenses:

* [Creative Commons Attribution 3.0](https://spdx.org/licenses/CC-BY-3.0.html) [or 4.0](https://spdx.org/licenses/CC-BY-4.0.html) - `CC-BY-3.0` or `CC-BY-4.0`
* [SIL Open Font License 1.1](https://spdx.org/licenses/OFL-1.1.html) - `OFL-1.1`
* [GNU LGPL 2.1](https://spdx.org/licenses/LGPL-2.1-or-later.html) [or 3.0](https://spdx.org/licenses/LGPL-3.0-or-later.html) - `LGPL-2.1-or-later` or `LGPL-3.0-only` or `LGPL-3.0-or-later`

Additional licenses *may* qualify for these lists from time to time, but every effort should be made to avoid it.
Regardless, all such licenses must be OSI, FSF, and DSFG approved, GPLv3-compatible and [listed on the main SPDX license list](https://spdx.org/licenses/) to ensure maximum free distribution and use of Spyder with minimum ambiguity or fragmentation.


## Steps to take

1. Contact the Spyder team to ensure the usage is justified and compatible.

2. Add the files, preserving any original copyright/legal/attribution headers.

3. If making non-trivial modifications, copy the standard Spyder copyright header from the [License Policy](https://github.com/spyder-ide/governance-and-guidelines/blob/main/LICENSE_POLICY.md) to just below the original headers; if the original headers are unformatted and just consist of a copyright statement and perhaps mention of the license, incorporate them verbatim within the Spyder header where appropriate. Always ensure copyright statements are in ascending chronological order, and replace the year in the Spyder copyright statement with the current one. Modify the license location to be the current directory, or `NOTICE.txt`.

4. Include the following line at the end of each module's docstring, separated by blank lines:

   ```rst
   Adapted from ``path/to/file/in/original/repo.py`` of the
   `Project Name <url-to-original-github-repo>`_.
   ```

   For example,

   ```rst
   Adapted from ``qcrash/_dialogs/gh_login.py`` of the
   `QCrash Project <https://github.com/ColinDuquesnoy/QCrash>`_.
   ```

5. Convert the files to project standards where needed.

6. If the copied file(s) reside in a directory dedicated to them, place the source project's `LICENSE.txt` file there, and any other legal files. Also, mention the same in the `__init__.py` file in that directory.

7. Add an entry in `NOTICE.txt` with the instructions and template there.

8. If a non-code visible asset (icons, fonts, animations, etc) or otherwise under a license that requires attribution, such as most Creative Commons licenses (except for CC0), include a mention in the appropriate section of the Readme and the `AUTHORS.txt`.


## Adding a new entry

Add one entry per code repo, icon set or font face, or other cohesive unit within which the source material is organized and distributed as.
New entries for icons should be in order of the number of icons used; other entries should be in order of inclusion.

Pay careful attention to the number of blank lines before and after headings, horizontal rules, sections, and other elements.
This helps keep the document machine-readable and helps avoid conflicts.
Break the file at 79 characters, and at periods (sentences) unless the text is copied directly from an external file (license, header, etc).
Follow the project standards for added files.

If the project's license is not already listed at the end of the `NOTICE.txt` file, you'll need to add it (but double-check it with us first).
Copy the plain text (broken at <= 80 characters) in the final section at the end of the `NOTICE.txt`, at the end of the list.


## New Entry Template


Fields that should be replaced are marked with `<this-is-a-field>`.
Some fields are optional, indicated with `[<option-one> OR <two>]`.
Comments, indicated with # are only for reference and should not be included in the final product.

```text
[<Project-Name> OR <Named-Subcomponent> from <Project-Name>] <version-used>
-------------------------------------------------------------------------


Copyright <year(s)> <author-name> [(<email-or-website>) IF provided]
# Use the author-provided form, if given, correcting obvious syntax errors
# (e.g. remove commas, false "All rights reserved" statements, etc)
# List additional copyright lines here, if provided
# If modified by project contributors after adding, additionally list:
[Copyright (c) <current-year>- <PROJECT-NAME> Contributors (see AUTHORS.txt)]


Author: <author-name> | <author-email> | <author-website>
Site: <main-project-website-other-than-github>  # Unless no site exists
[Source: <main-page-of-github-etc-repository>]
[Download: <page-to-download-icons-or-assets>]  # If not the same as above
License: <full-name-of-license-including-version>
<canonical-url-to-authoritative-license-text>

[No modifications made. OR Modifications made to [each file] to <purpose>.]


<license-summary-text-and-notices-from-original-project>
# If the project includes a NOTICE.txt file, copy its contents verbatim here.
# Additionally, include any non-canonical text in the project's license file
# (i.e. that not part of the actual license itself, as reproduced below)
# Any text from an AUTHORS file, any file header text aside from the copyright,
# Any legal-related text in the readme (credits, acknowledgments, license, etc)
# and any other legal text, disclaimer, notice, attribution etc. present.
# Trim all line breaks to no more than one consecutive blank line


[<project-name> is used under the terms of the <specific-licensed>.
See below for the full text of the <specific-license>.]  # If dual-licensed
# Pick the license closest to Spyder's, or otherwise the most permissive

# Include any additional custom explanatory text describing usage of the
# project/component/asset with the project here

See below for the full text of the <full-name-of-license-including-version>.

The current <project-name> license can be viewed at:
<direct-link-to-license-file-on-github-etc>

[Later versions of the <full-name-of-license] can be viewed at:
<link-to-license-creator-site>]  # For "any later version" licenses, like LGPL

[The current license summary can be viewed at:
<link-to-license-summary-on-project-or-license-creator-page>]  # If present

[The current version of the original file[s] can be viewed at:
<link-to-github-etc-of-original-file>]  # If only specific file(s) used
<links-to-further-files-if-applicable]


Files covered:

<path/to/file/in/spyder/repo.py>  # Should always be relative to the repo root


-------------------------------------------------------------------------------
```


## File preamble

The following is a standard preamble for this file.
Replace `<PROJECT_NAME>` with the name of the Spyder sub-project.

```text
Included Software, Images and Icons
###################################


General Information
===================


`<PROJECT_NAME>` incorporates code and image assets from various external sources,
each of which is covered by its own license and copyright notice.
These files are listed here with their corresponding authors,
permission notices, disclaimers, and copyright statements; these are also
included in the files' directory and/or their headers, as appropriate.

Any file not listed here is covered by `<PROJECT_NAME>`'s MIT (Expat) license,
described in the LICENSE.txt file in this repository.

Images, icons and font gyphs that include trademarked elements are used for
informational purposes only, and do not necessarily constitute any endorsement,
association or ownership by or of the marks or their respective owners.

All trademarks are the property of their respective owners.


-------------------------------------------------------------------------------
```
