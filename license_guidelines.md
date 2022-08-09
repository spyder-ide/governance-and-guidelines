# Project License Guidelines

## License

The standard license for new and most existing Spyder projects is the [MIT (Expat) License](https://opensource.org/licenses/MIT).
The `<creation_year>` is replaced with the earliest year any substantial contributions were made to any code in the project.
If the repository also contains files under other licenses or from other projects, append `some files under other terms (see NOTICE.txt)`.

The standard text:

```text
MIT License

Copyright (c) <creation_year>- Spyder Project Contributors and others (see AUTHORS.md)

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.
```


## License header

The following header should be included in all MIT-licensed Spyder Project source code files whenever practical, where `<creation_date>` is the date the file was created:

```text
# -----------------------------------------------------------------------------
# Copyright (c) <creation_date>- Spyder Project Contributors
#
# Released under the terms of the MIT License
# (see LICENSE.txt in the project root directory for details)
# -----------------------------------------------------------------------------
```


## Authors file

Repositories should include an `AUTHORS.md` file briefly documenting the authorship of the project.
The specific format and content may vary, but should include:

* The name, repo link, website link and primary author(s) of any projects from which the given repository was derived
* The name, GitHub/etc. username and link (GitHub profile, website or email) of the original creator(s) of the project
* The name, GitHub username and link of the repository's current primary maintainer(s)
* A link to the contributor listing of the project
* The name, description, author and link to any third-party content that requires attribution, or is otherwise a major part of the project
* A reference and link to the `NOTICE.txt` file, if present
* Any other information or links relevant to the authorship of the project.

The following is a standard template including all the above:

```md
# Authors

## Original project(s)

* [PROJECT NAME](https://PROJECT.URL): AUTHOR NAME ([@GITHUBUSERNAME](https://github.com/GITHUBUSERNAME)) and the [PROJECT NAME contributors](https://github.com/ORGNAME/PROJECTNAME/graphs/contributors)


## Original authors

* [AUTHOR NAME](https://AUTHOR.SITE) ([@GITHUBUSERNAME](https://github.com/GITHUBUSERNAME))


## Current maintainers

* [MAINTAINER NAME](https://MAINTINER.SITE) ([@GITHUBUSERNAME](https://github.com/GITHUBUSERNAME))
* The [Spyder Development Team](https://github.com/spyder-ide)
* The [PROJECT NAME Contributors](https://github.com/spyder-ide/PROJECTNAME/graphs/contributors)


## Third-party projects

Some assets and code were originally sourced from third-party authors or projects, including:

* The ASSET DESCRIPTION is derived from [PROJECT NAME](https://PROJECT.SITE), by [AUTHOR NAME](https://AUTHOR.SITE)

For information about the sources and authors of other third-party code and resources used, please see the `NOTICE.txt` file, located in the root of the PROJECT NAME repository](https://github.com/spyder-ide/PROJECTNAME/blob/master/NOTICE.txt).
```


## Notice file for externally-sourced code

If a project's repository also contains files under other licenses or from other projects, their copyright statements, licenses, and any notices must be preserved in a `NOTICE.txt` file in the repo root.
Author and source metadata and links, a modification statement and the files covered must also be listed here.
See the [Spyder `NOTICE.txt`](https://github.com/spyder-ide/governance-and-guidelines/blob/main/PROJECT_LICENSE.md) for more information, instructions, a template and examples.


## Code contributions and copyright policy

Spyder uses a shared copyright model, where each contributor maintains copyright ownership of their contributions.
However, each contributor must affirm the [Developer Certificate of Origin](https://developercertificate.org) with respect to their contributions, to certify that all Spyder users have the right to use, modify and distribute them.
The following PR template is used to achieve this, with each contributing replacing `<NAME>` with their full name or GitHub username:

```md
By submitting this Pull Request or typing my (user)name below,
I affirm the [Developer Certificate of Origin](https://developercertificate.org)
with respect to all commits and content included in this PR,
and understand I am releasing the same under Spyder's MIT (Expat) license.

<!--- TYPE YOUR USER/NAME AFTER THE FOLLOWING: --->
I certify the above statement is true and correct: <NAME>
```
