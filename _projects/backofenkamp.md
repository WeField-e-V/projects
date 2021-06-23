---
collaborating_projects:
  - about-code
desc: "Our first Microfarm, Social-Hub and architectial creation room. From here we started our mission to enable regenerative Microfarming for everybody."
difficulty: low
status: in_progress
initiatives:
  - NABU 
  - ECOSIA 
  - Wir.bwegen.sh
  - ClimateFarmer
  - GutHaidehof
  - UXMA
issues:
  - "https://github.com/coala/meta/issues/58"
  - "https://github.com/coala/meta/issues/81"
markdown: backofenkamp.md
mentors:
  - Finn-1
name: "WeField - Backofenkamp"
requirements:
  - "Level 2 WeField Mitglied"
tags:
  - marketgarden
  - agroforestry
  - hedges
  - social hub
  - architectual 
---

## description

We are maintaining right now a 200m2 marketgarden, a 5000m2 Walnut Orchard and a 2000m2 fruit and berry Orchard. All Managed from our Social-Hub, the two refurbished Sea-Containers by (Lasse)

## requirements

Everyone who is interested can come and learn.

## participate

Every Sunday we have our FarmShop open. Come by and get some fresh harvested veggies. 
Open Sunday´s from 12am-4pm.
If you want to participate at other Events, get a Membership and you will be informed by our Newsletter.

If you have a field, wherever you live, contact us.

----

## Step 1

Start by looking through
[GitHub repositories without a recognised license](https://github.com/search?o=desc&q=-license%3Amit+-license%3Aapache-2.0+-license%3Absd-3-clause+-license%3Agpl+-license%3Acc+-license%3Algpl&s=stars&type=Repositories&utf8=%E2%9C%93)
sorted by "most stars" or "most forks".

Check that GitHub does not show a recognised license at the top of the repository.
See [Adding a license](https://help.github.com/articles/adding-a-license-to-a-repository/)
for a picture of a recognised MIT license.

Check that the repository does not have a `LICENSE` or `LICENSE.md` file.
Maybe GitHub does not recognise the contents of the file.

Also look in the repository for a license file with a different file extension,
such as `license.txt`, or a directory with multiple licenses,
such as https://github.com/xl1/armiku .
If you find a repository like this, the following steps are not appropriate.
Instead, it may be appropriate to move the existing file.
If you like to explore this type of problem,
[here](https://github.com/search?utf8=%E2%9C%93&q=-license%3Amit+-license%3Aapache-2.0+-license%3Absd-3-clause+-license%3Agpl+-license%3Acc+-license%3Algpl+path%3ALICENSE+license&type=Code)
is a GitHub search which finds thousands of these repositories, and
[here](https://github.com/search?utf8=%E2%9C%93&q=-license%3Amit+%22Permission+is+hereby+granted%2C+free+of+charge%2C+to+any+person+obtaining%22&type=Repositories)
is a GitHub search which shows repositories with a slightly different yet
similarly difficult problem to be solved.
However, it is recommended that you return to Step 1 and select a new repository
which doesnt have any license files.

Check the pull requests for the repository.
Maybe someone has already proposed a license file.
Do not send another pull request to add a license file.

Also avoid small repositories which are personal learning projects,
or repositories without any code, or abandoned projects.

Avoid 'mirror' repositories, where pull requests are not wanted on GitHub.
Many projects host their coding activities in another git system, and mirror
the commits to GitHub.  These projects may appear in search results, and
should be skipped.

## Step 2

### Does the repository already have a license selected?

It is quite common for a repository to not have a LICENSE or LICENSE.md
file, but still have already selected a license which is recorded
in a different way.

If the repository has already chosen a license, it is not appropriate
to suggest a different license.  Therefore it is very important to
try to find the existing license.

Maybe the repository has a README.md file which mentions the license.

The chosen license may exist in other files, such:
- `package.json`

Check the issues in the repository.
Maybe an issue already contains a discussion about licensing choices.

A good approach is to search the repository for the words `license`
and `licence`, and read each search result for hints of existing
licenses.

If there is no license mentioned anywhere in the repository,
there are still other ways to find the most appropriate license.

Check the other repositories created by the main contributors.
Maybe they consistently use a license, and simply forgot to add
it to the repository that you have found in Step 1.

If you are confident that you have found the license that is implicitly chosen
by the project team members, skip to Step 3.

### Or, choose a suitable license for a repository without any licenses

Determining which license to propose for a respository is not easy.

That decision is usually best left to the existing team of contributors,
who may have a strong preference that they have not disclosed publicly.

It is recommended that beginners go back to step 1 and find a different
repository that already mentions a specific license.

## Step 3

The text for many licenses can be obtained from https://choosealicense.com/

1. Copy it to the clipboard.
2. Fork the repository
3. Add a LICENSE file to the repository, committing the new file to a branch.
   1. Be aware that many licenses provide template values that must be substituted with the correct values
4. Submit your branch to the main repository as a pull request.

A quick way to create a license file is to create a fork and then create a URL
using the following template.

`https://github.com/<your_username>/<repository_name>/community/license/new?branch=license&template=mit`

Replace `mit` with the short license identifier that GitHub has allocated to the selected license.

## Examples

Examples of this task being done by Indonesian University students can be found at
[this blog post](https://github.com/BesutKode/BesutKode.github.io/blob/master/_posts/2016-11-01-31-october-elimination-results.md).

## Stackoverflow tags

[licensing](https://stackoverflow.com/questions/tagged/licensing) |
[github](https://stackoverflow.com/questions/tagged/github) |
[gpl](https://stackoverflow.com/questions/tagged/gpl) |
[lgpl](https://stackoverflow.com/questions/tagged/lgpl)
