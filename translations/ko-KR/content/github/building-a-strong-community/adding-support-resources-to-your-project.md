---
title: Adding support resources to your project
intro: You can create a SUPPORT file to let people know about ways to get help with your project.
redirect_from:
  - /articles/adding-support-resources-to-your-project
versions:
  free-pro-team: '*'
  enterprise-server: '*'
---

To direct people to specific support resources, you can add a SUPPORT file to your repository's root, `docs`, or `.github` folder. When someone creates an issue in your repository, they will see a link to your project's SUPPORT file.

![Support guidelines](/assets/images/help/issues/support_guidelines_in_issue.png)

You can create default support resources for your organization{% if currentVersion == "free-pro-team@latest" or currentVersion ver_gt "enterprise-server@2.19" %} or user account{% endif %}. For more information, see "[Creating a default community health file](/github/building-a-strong-community/creating-a-default-community-health-file)."

{% tip %}

**Tip:** To help people find your support guidelines, you can link to your SUPPORT file from other places in your repository, such as your [README file](/articles/about-readmes/).

{% endtip %}

### Adding support resources to your project

{{ site.data.reusables.repositories.navigate-to-repo }}
{{ site.data.reusables.files.add-file }}
3. In the file name field, type *SUPPORT.md* (with all caps).
4. On the **Edit new file** tab, add information about how people can get support for your project.
5. To review your SUPPORT file, click **Preview**.
{{ site.data.reusables.files.write_commit_message }}
{{ site.data.reusables.files.choose-commit-email }}
{{ site.data.reusables.files.choose_commit_branch }}
{{ site.data.reusables.files.propose_new_file }}