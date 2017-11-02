# 20Time-ICS4U - Excel Converter
ICS4U starter page



A new version is available: English 1.0.0

Keep a CHANGELOG
Don’t let your friends dump git logs into CHANGELOGs™

Version 0.3.0

What’s a change log?
A change log is a file which contains a curated, chronologically ordered list of notable changes for each version of a project.

# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.0] - 2017-06-20
### Added
- New visual identity by @tylerfortune8.
- Version navigation.
- Links to latest released version in previous versions.
- "Why keep a changelog?" section.
- "Who needs a changelog?" section.
- "How do I make a changelog?" section.
- "Frequently Asked Questions" section.
- New "Guiding Principles" sub-section to "How do I make a changelog?".
- Simplified and Traditional Chinese translations from @tianshuo.
- German translation from @mpbzh & @Art4.
- Italian translation from @azkidenz.
- Swedish translation from @magol.
- Turkish translation from @karalamalar.
- French translation from @zapashcanon.
- Brazilian Portugese translation from @aisamu.
- Polish translation from @amielucha.
- Russian translation from @aishek.
- Czech translation from @h4vry.
- Slovak translation from @jkostolansky.

### Changed
- Start using "changelog" over "change log" since it's the common usage.
- Start versioning based on the current English version at 0.3.0 to help
translation authors keep things up-to-date.
- Rewrite "What makes unicorns cry?" section.
- Rewrite "Ignoring Deprecations" sub-section to clarify the ideal
  scenario.
- Improve "Commit log diffs" sub-section to further argument against
  them.
- Merge "Why can’t people just use a git log diff?" with "Commit log
  diffs"
- Fix typos in Simplified Chinese and Traditional Chinese translations.
- Fix typos in Brazilian Portugese translation.
- Fix typos in Turkish translation.
- Fix typos in Czech translation.
- Fix typos in Swedish translation.
- Improve phrasing in French translation.
- Fix phrasing and spelling in German translation.

### Removed
- Section about "changelog" vs "CHANGELOG".

## [0.3.0] - 2015-12-03
### Added
- RU translation from @aishek.
- pt-BR translation from @tallesl.
- es-ES translation from @ZeliosAriex.

## [0.2.0] - 2015-10-06
### Changed
- Remove exclusionary mentions of "open source" since this project can
benefit both "open" and "closed" source projects equally.

## [0.1.0] - 2015-10-06
### Added
- Answer "Should you ever rewrite a change log?".

### Changed
- Improve argument against commit logs.
- Start following [SemVer](http://semver.org) properly.

## [0.0.8] - 2015-02-17
### Changed
- Update year to match in every README example.
- Reluctantly stop making fun of Brits only, since most of the world
  writes dates in a strange way.

### Fixed
- Fix typos in recent README changes.
- Update outdated unreleased diff link.

## [0.0.7] - 2015-02-16
### Added
- Link, and make it obvious that date format is ISO 8601.

### Changed
- Clarified the section on "Is there a standard change log format?".

### Fixed
- Fix Markdown links to tag comparison URL with footnote-style links.

## [0.0.6] - 2014-12-12
### Added
- README section on "yanked" releases.

## [0.0.5] - 2014-08-09
### Added
- Markdown links to version tags on release headings.
- Unreleased section to gather unreleased changes and encourage note
keeping prior to releases.

## [0.0.4] - 2014-08-09
### Added
- Better explanation of the difference between the file ("CHANGELOG")
and its function "the change log".

### Changed
- Refer to a "change log" instead of a "CHANGELOG" throughout the site
to differentiate between the file and the purpose of the file — the
logging of changes.

### Removed
- Remove empty sections from CHANGELOG, they occupy too much space and
create too much noise in the file. People will have to assume that the
missing sections were intentionally left out because they contained no
notable changes.

## [0.0.3] - 2014-08-09
### Added
- "Why should I care?" section mentioning The Changelog podcast.

## [0.0.2] - 2014-07-10
### Added
- Explanation of the recommended reverse chronological release ordering.

## 0.0.1 - 2014-05-31
### Added
- This CHANGELOG file to hopefully serve as an evolving example of a
  standardized open source project CHANGELOG.
- CNAME file to enable GitHub Pages custom domain
- README now contains answers to common questions about CHANGELOGs
- Good examples and basic guidelines, including proper date formatting.
- Counter-examples: "What makes unicorns cry?"












What’s the point of a change log?
To make it easier for users and contributors to see precisely what notable changes have been made between each release (or version) of the project.

Why should I care?
Because software tools are for people. If you don’t care, why are you contributing to open source? Surely, there must be a kernel (ha!) of care somewhere in that lovely little brain of yours.

I talked with Adam Stacoviak and Jerod Santo on The Changelog (fitting, right?) podcast about why maintainers and contributors should care, and the motivations behind this project. If you can spare the time (1:06), it’s a good listen.

What makes a good change log?
I’m glad you asked.

A good change log sticks to these principles:

It’s made for humans, not machines, so legibility is crucial.
Easy to link to any section (hence Markdown over plain text).
One sub-section per version.
List releases in reverse-chronological order (newest on top).
Write all dates in YYYY-MM-DD format. (Example: 2012-06-02 for June 2nd, 2012.) It’s international, sensible, and language-independent.
Explicitly mention whether the project follows Semantic Versioning.
Each version should:
List its release date in the above format.
Group changes to describe their impact on the project, as follows:
Added for new features.
Changed for changes in existing functionality.
Deprecated for once-stable features removed in upcoming releases.
Removed for deprecated features removed in this release.
Fixed for any bug fixes.
Security to invite users to upgrade in case of vulnerabilities.
How can I minimize the effort required?
Always have an "Unreleased" section at the top for keeping track of any changes.

This serves two purposes:

People can see what changes they might expect in upcoming releases
At release time, you just have to change "Unreleased" to the version number and add a new "Unreleased" header at the top.
What makes unicorns cry?
Alright…let’s get into it.

Dumping a diff of commit logs. Just don’t do that, you’re helping nobody.
Not emphasizing deprecations. When people upgrade from one version to another, it should be painfully clear when something will break.
Dates in region-specific formats. In the U.S., people put the month first ("06-02-2012" for June 2nd, 2012, which makes no sense), while many people in the rest of the world write a robotic-looking "2 June 2012", yet pronounce it differently. "2012-06-02" works logically from largest to smallest, doesn't overlap in ambiguous ways with other date formats, and is an ISO standard. Thus, it is the recommended date format for change logs.
There’s more. Help me collect those unicorn tears by opening an issue or a pull request.

Is there a standard change log format?
Sadly, no. Calm down. I know you're furiously rushing to find that link to the GNU change log style guide, or the two-paragraph GNU NEWS file "guideline". The GNU style guide is a nice start but it is sadly naive. There's nothing wrong with being naive but when people need guidance it's rarely very helpful. Especially when there are many situations and edge cases to deal with.

This project contains what I hope will become a better CHANGELOG file convention. I don't think the status quo is good enough, and I think that as a community we can come up with better conventions if we try to extract good practices from real software projects. Please take a look around and remember that discussions and suggestions for improvements are welcome!

What should the change log file be named?
Well, if you can’t tell from the example above, CHANGELOG.md is the best convention so far.

Some projects also use HISTORY.txt, HISTORY.md, History.md, NEWS.txt, NEWS.md, News.txt, RELEASES.txt, RELEASE.md, releases.md, etc.

It’s a mess. All these names only makes it harder for people to find it.

Why can’t people just use a git log diff?
Because log diffs are full of noise — by nature. They could not make a suitable change log even in a hypothetical project run by perfect humans who never make typos, never forget to commit new files, never miss any part of a refactoring. The purpose of a commit is to document one atomic step in the process by which the code evolves from one state to another. The purpose of a change log is to document the noteworthy differences between these states.

As is the difference between good comments and the code itself, so is the difference between a change log and the commit log: one describes the why, the other the how.

Can change logs be automatically parsed?
It’s difficult, because people follow wildly different formats and file names.

Vandamme is a Ruby gem created by the Gemnasium team and which parses many (but not all) open source project change logs.

Why do you alternate between spelling it "CHANGELOG" and "change log"?
"CHANGELOG" is the name of the file itself. It's a bit shouty but it's a historical convention followed by many open source projects. Other examples of similar files include README, LICENSE, and CONTRIBUTING.

The uppercase naming (which in old operating systems made these files stick to the top) is used to draw attention to them. Since they're important metadata about the project, they could be useful to anyone intending to use or contribute to it, much like open source project badges.

When I refer to a "change log", I'm talking about the function of this file: to log changes.

What about yanked releases?
Yanked releases are versions that had to be pulled because of a serious bug or security issue. Often these versions don't even appear in change logs. They should. This is how you should display them:

## 0.0.5 - 2014-12-13 [YANKED]

The [YANKED] tag is loud for a reason. It's important for people to notice it. Since it's surrounded by brackets it's also easier to parse programmatically.

Should you ever rewrite a change log?
Sure. There are always good reasons to improve a change log. I regularly open pull requests to add missing releases to open source projects with unmaintained change logs.

It's also possible you may discover that you forgot to address a breaking change in the notes for a version. It's obviously important for you to update your change log in this case.

How can I contribute?
This document is not the truth; it’s my carefully considered opinion, along with information and examples I gathered. Although I provide an actual CHANGELOG on the GitHub repo, I have purposefully not created a proper release or clear list of rules to follow (as SemVer.org does, for instance).

This is because I want our community to reach a consensus. I believe the discussion is as important as the end result.

So please pitch in.

Keep a changelog mark This project is MIT Licensed // Created & maintained by Olivier Lacan // Designed by Tyler Fortune
