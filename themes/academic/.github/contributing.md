# Contributing to Wowchemy

Thanks for being interested in contributing! We’re so glad you want to help!

We want contributing to Wowchemy to be fun, enjoyable, and educational for anyone and everyone. All contributions are welcome, including new plugins (such as new widgets, shortcodes, theme packs, and language packs), templates, features, documentation as well as updates and tweaks, blog posts, YouTube tutorials, live streaming customizations, meetups, and more.

## Where to Start

Join the **Contributing** channel on the **[community Discord](https://discord.gg/z8wNYzb)**.

### For technical contributions

Repository structure:

- scripts
  - A collection of scripts for helping maintain the repository
- starters
  - The collection of starter templates (aka Hugo themes)
  - To contribute an improvement to a starter template, make your changes to the relevant template within this folder. **Do not submit PRs to the dedicated template repositories as they are read-only.**
- wowchemy
  - The components and layouts which form the Wowchemy page building framework that the templates depend on
- wowchemy-cms
  - The admin panel that enables users to edit their content on the go

#### What are some good issues to contribute to?

If you're a developer looking to contribute, but you're not sure where to begin, check out the [good first issue](https://github.com/wowchemy/wowchemy-hugo-themes/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22) label on Github, which contains small tasks that have been specifically flagged as being friendly to new contributors.

After that, if you're looking for something a little more challenging to sink your teeth into, there's a broader [help wanted](https://github.com/wowchemy/wowchemy-hugo-themes/labels/help%20wanted) label encompassing issues which need some love.

#### How can I propose an improvement?

If you have a straightforward bug fix or improvement, feel free to contribute it in a [Pull Request](https://github.com/wowchemy/wowchemy-hugo-themes/pulls) for the community to review.

If you have an idea for a new feature, please start by [searching the issues](https://github.com/wowchemy/wowchemy-hugo-themes/issues) to check that the feature has not already been suggested and then suggest it by [opening a new issue](https://github.com/wowchemy/wowchemy-hugo-themes/issues/new/choose), as adding new features to Wowchemy first requires some analysis around the design and spec.

Please be mindful of the project [scope](#scope).

#### How can I contribute an improvement?

Learn [how to contribute code on Github](https://codeburst.io/a-step-by-step-guide-to-making-your-first-github-contribution-5302260a2940).

**⚡️ To make quick and easy contributions, you can browse the repository on GitHub and edit your changes in GitHub's online editor. GitHub will then open a Pull Request (PR) for your changes to be reviewed by the community. ⚡️**

Otherwise, for larger changes, you can edit locally on your computer in your favorite editor, such as VSCode:

**Download the repo**

Fork (copy) the repo on GitHub and then clone (download) your fork to your computer:

```sh
git clone https://github.com/<YOUR_USERNAME>/wowchemy-hugo-themes.git
```

**View a template**

[Install Yarn](https://yarnpkg.com/), the project's build system if necessary.

Then choose the starter template you wish to view, such as _minimal_:

```sh
yarn view:local minimal
```

Note that Hugo Server can occasionally stop working after changes are made (sometimes showing unrelated errors). If this happens, stop Hugo (Control-C) and restart it with the `yarn view:local ...` command above.

**Implement your improvements**

Implement you changes and then check for any linting or formatting issues.

Code linting and formatting form part of the Continuous Integration process to help catch bugs and code issues in contributions.

Contributors can also run the flow on their fork of the "Wowchemy Hugo Modules" repo when making contributions (you'll need Node and Yarn to run):

```sh
yarn install
yarn run lint
yarn run format
```

**Open a Pull Request with your changes**

Use git to push (upload) your changes to GitHub and then open a Pull Request (PR) at https://github.com/wowchemy/wowchemy-hugo-themes/pulls

Please be mindful of the project [scope](#scope).

### Contribute a widget

[Create and publish your own widget](https://github.com/wowchemy/wowchemy-widget-starter)

### Contribute a shortcode

[Create and publish your own shortcode](https://github.com/wowchemy/wowchemy-shortcode-starter)

### Contribute a language pack

To contribute a **new language pack** or an improvement to a language pack, refer to the [language pack guide](https://wowchemy.com/docs/language/#create-or-modify-a-language-pack). Once created, [fork Wowchemy Hugo Modules](https://github.com/wowchemy/wowchemy-hugo-themes), place your language pack in `wowchemy/i18n/`, add the name of the language to `wowchemy/data/i18n/language.yaml`, and open a Pull Request on Github with these two files.

### Contribute a theme pack

[View the guide](https://wowchemy.com/docs/customization/#share-your-theme) to contributing a color and font theme pack.

### Contribute a template

Consider duplicating a bare-bones template, such as the [Minimal](https://github.com/wowchemy/wowchemy-hugo-themes/tree/main/starters/minimal) folder, and building up your own template using the Wowchemy Hugo Module. Reach out on the **Contributing** channel in Discord to submit your template.

### Contribute to the Publication importer

To contribute to **Hugo Academic CLI**, the automatic publication importer, refer to [its dedicated Github repository](https://github.com/wowchemy/hugo-academic-cli) and Issue queue.

## Become a backer

To help us develop this free software sustainably under the open source license, we ask all individuals and businesses that use it to help support its ongoing maintenance and development via sponsorship:

- ☕️ [**Donate a coffee**](https://github.com/sponsors/gcushen?frequency=one-time)
- ❤️ [**Become a sponsor and unlock awesome rewards**](https://wowchemy.com/sponsor/)

## Other ways to help

If you're not a developer there are still plenty of ways that you can help. We always need help with:

- Helping the Wowchemy community on the [chat](https://discord.gg/z8wNYzb) and [forum](https://github.com/wowchemy/wowchemy-hugo-themes/discussions)
- Investigating and reviewing open [Issues](https://github.com/wowchemy/wowchemy-hugo-themes/issues) and [Pull Requests](https://github.com/wowchemy/wowchemy-hugo-themes/pulls)
  - Give a thumbs up 👍 to upvote a feature request you would like to use
- Improving the [documentation](https://wowchemy.com/docs/) and writing tutorials
  - Just click the _Edit_ button at the bottom of pages or open an issue with your proposed improvement
- Testing and quality assurance
- Hosting local Wowchemy themed events or meetups
- Promoting Wowchemy to others by blogging, vlogging, code streaming, talking etc.

## Scope

Please be _mindful_ that although we encourage feature requests, we cannot expand the scope of the project in every possible direction. There will be feature requests that don't make the roadmap.

Every feature requires effort not just to analyse the requirements, design it, implement it, test it, document it, merge it, write release notes for it, and release it, but also to continuously support users with it and maintain it (fixing and refactoring the feature as the project and its dependencies evolve).

The more regular active volunteers (rather than one-off contributors) we have supporting users and maintaining the project, the more feasible it becomes to expand the scope of the project.

The project's scope also has to be constrained so that it doesn't get too complex and unwieldy, from an architectural perspective, a testing perspective, and from a usability perspective.

Plugins (widgets, shortcodes, theme packs, language packs, and third-party JavaScript integrations) as well as templates allow the community to add major features without needing to contribute to Wowchemy itself.
