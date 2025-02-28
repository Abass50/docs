---
title: About Codespaces
intro: '{% data variables.product.prodname_codespaces %} is a configurable online development environment, hosted by {% data variables.product.prodname_dotcom %} and powered by {% data variables.product.prodname_vscode %}, that allows you to develop entirely in the cloud.'
product: '{% data reusables.gated-features.codespaces %}'
redirect_from:
  - /github/developing-online-with-github-codespaces/about-github-codespaces
  - /github/developing-online-with-codespaces/about-codespaces
  - /codespaces/getting-started-with-codespaces/about-codespaces
versions:
  free-pro-team: '*'
topics:
  - Codespaces
---

{% note %}

**Note:** {% data variables.product.prodname_codespaces %} is currently in limited public beta and subject to change. During the beta period, {% data variables.product.prodname_dotcom %} does not make any guarantees about the availability of {% data variables.product.prodname_codespaces %}.

{% endnote %}

### About {% data variables.product.prodname_codespaces %}

{% data variables.product.prodname_codespaces %} is a configurable cloud development environment available in your browser on {% data variables.product.prodname_dotcom %} or through {% data variables.product.prodname_vscode %}. 

![An open codespace](/assets/images/help/codespaces/codespace-overview.png)

A codespace includes everything developers need to develop for a specific repository, including the {% data variables.product.prodname_vscode %} editing experience and common languages, tools, and utilities. {% data variables.product.prodname_codespaces %} is completely configurable, allowing you to create a customized development environment for your project, and allowing developers to personalize their experience with extensions and dotfile settings. 

Codespaces offers many benefits to all teams by allowing for a consistent environment across your entire team, fast onboarding, and creating a secure space for development.


### A consistent environment

You can create a single codespace configuration that defines the environment of every new codespace that anyone creates for your repository. Once you've made a configuration, developers don’t have to worry about installing the right tools to comment, review, or contribute. The standard environment is already available for them as soon as they create a codespace from the repository. For more information, see "[Configuring {% data variables.product.prodname_codespaces %} for your project](/github/developing-online-with-codespaces/configuring-codespaces-for-your-project)."

For help getting started with configurations for specific languages, see the [Getting Started](/codespaces/getting-started-with-codespaces) tutorials.

While every codespace created from your repository has a consistent development environment, developers can use {% data variables.product.prodname_codespaces %} wherever they need it – on {% data variables.product.prodname_dotcom %} or through {% data variables.product.prodname_vscode %}.

### Fast and personal onboarding

With a [dev container](/codespaces/setting-up-your-codespace/configuring-codespaces-for-your-project#about-dev-containers) already configured in your repository, any new developer can quickly onboard with the correct development environment for your project by using the {% octicon "download" aria-label="The download icon" %} **Code** drop-down menu, and selecting **Open with Codespaces**.

![Open with Codespaces button](/assets/images/help/codespaces/open-with-codespaces-button.png)

Developers can start coding faster by reducing time spent configuring their environment.

Developers can also personalize aspects of their codespace environment by using a [dotfiles](https://dotfiles.github.io/tutorials/) repository. Personalization can include shell preferences, additional tools, editor settings, and extensions, such as Live Share. Personal customizations are stored on a per-user basis, so every codespace a developer opens has their environment ready to go. For more information, see "[Personalizing {% data variables.product.prodname_codespaces %} for your account](/github/developing-online-with-codespaces/personalizing-codespaces-for-your-account)."

Because {% data variables.product.prodname_codespaces %} can be accessed in the browser, developers can work on multiple projects by switching between tabs.

### A secure environment

{% data variables.product.prodname_codespaces %} allows developers to develop in the cloud instead of locally. This creates one single, trackable, source of truth. Developers can contribute from anywhere, on any machine, including tablets or Chromebooks, and there is no need to maintain local copies of intellectual property. Developers always have to be logged in and provided with access to both {% data variables.product.prodname_codespaces %} and specific repositories. These permissions can be revoked at any time. As soon as you revoke access, those developers will lose all access to protected resources. In addition, authenticated developers create audit trails so you know who is doing what. For more information on access and security, see "[Managing access and security for {% data variables.product.prodname_codespaces %}](/github/developing-online-with-codespaces/managing-access-and-security-for-codespaces)."

Using {% data variables.product.prodname_codespaces %} is the most secure when all members of your team are using it. It means that there is no need to clone the repository onto a local machine and that developers don't need to install locally as `root`.

Developers and organization administrators can also configure settings to add encrypted secrets and enable GPG verification. For more information, see "[Managing encrypted secrets for {% data variables.product.prodname_codespaces %}](/github/developing-online-with-codespaces/managing-encrypted-secrets-for-codespaces)", "[Managing GPG verification for {% data variables.product.prodname_codespaces %}](/github/developing-online-with-codespaces/managing-gpg-verification-for-codespaces)".

### About billing for {% data variables.product.prodname_codespaces %}

{% data reusables.codespaces.about-billing-for-codespaces %} For more information, see "[About billing for {% data variables.product.prodname_codespaces %}](/github/developing-online-with-codespaces/about-billing-for-codespaces)."

### Joining the beta

A limited number of people will be invited to join the beta. To join the waitlist, see [Sign up for Codespaces beta](https://github.com/features/codespaces/signup).

### Contacting us about {% data variables.product.prodname_codespaces %}

If you encounter problems using {% data variables.product.prodname_codespaces %}, see "[Troubleshooting your codespace](/github/developing-online-with-codespaces/troubleshooting-your-codespace)."

If you still need help or have feedback about {% data variables.product.prodname_codespaces %}, use the [Codespaces Feedback](https://github.com/github/feedback/discussions/categories/codespaces-feedback) discussion.
