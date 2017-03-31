# Simpla Elements Catalogue
[![Published][webcomponents-badge]][webcomponents-collection] [![Simpla slack group][slack-badge]][slack-url]

This is an open catalogue of elements built on the [Simpla](https://www.simpla.io) content system. The catalogue is hosted on [simpla.io/elements][elements-catalogue] and [webcomponents.org][webcomponents-collection].

## Creating a Simpla element

It's easy to build your own custom Simpla elements, read the [element authoring guide](https://www.simpla.io/docs/creating-simpla-elements) to learn more.

## Publishing your element

To publish your element to the Simpla catalogue:

1. Ensure your element has a README and follows the `simpla-` naming convention

2. Fork this repository

2. Add your element as a dependency to `bower.json`, pointing to its GitHub repository. Eg: `"element": "user/element"`

3. [Submit a Pull Request](https://github.com/simplaio/simpla-elements/compare) against this repository

4. [Publish](https://www.webcomponents.org/publish) your element to webcomponents.org, which simpla.io will link to automatically

Once the PR is merged your element will be available in the catalogues on both [simpla.io/elements][elements-catalogue] and [webcomponents.org][webcomponents-collection].

## Getting involved

We love getting the community involved, and welcome any kind of input: issues and PRs on repos, feature suggestions, discussions with the team, and anything that you build and share using Simpla!

### Get in touch with the team

We live on Slack and actively monitor Twitter and other channels:

- [Slack chat](https://slack.simpla.io)
- [Twitter](https://twitter.com/simplaio)
- [Simpla.io](https://www.simpla.io)
- [Email](mailto:friends@simpla.io)

### Ways to help

Here are a few ways you can help push the Simpla project forward:

- **Feedback:** Try Simpla and its elements and let us know what works and what could be better - new features, API design, new use-cases, breaking bugs, every piece of feedback you provide is hugely valuable.

- **Report bugs:** If you find a bug in Simpla or any of the elements, please report it! The Simpla core library lives at [simplaio/simpla](https://github.com/simplaio/simpla) and the elements live in the [SimplaElements](https://github.com/SimplaElements) organization.

- **Submit Pull Requests:** If you'd like to contribute directly to Simpla's development you can submit pull requests against any repository. Your PR should address an existing issue or have been discussed previously to ensure it gets merged.

---

MIT © Simpla <friends@simpla.io>

[elements-catalogue]: https://www.simpla.io/elements
[webcomponents-collection]: https://www.webcomponents.org/collections/simplaio/simpla-elements

[webcomponents-badge]: https://img.shields.io/badge/webcomponents.org-published-blue.svg
[slack-badge]: https://slack.simpla.io/badge.svg
[slack-url]: https://slack.simpla.io