# Set up the MyPageAudit organization profile

GitHub displays three separate pieces of organization information: the Overview README, a short description, and an avatar. Set up each one below.

## 1. Publish the Overview README

1. Open the organization's `.github` repository.
2. Ensure its visibility is **Public**. If necessary, use **Settings → General → Danger Zone → Change repository visibility**.
3. Commit `profile/README.md` and `profile/avatar.png` on the default branch. The prepared image URL targets `main`; update it if your default branch has another name.
4. Open the [MyPageAudit overview](https://github.com/mypageaudit) and select **View as: Public** to check the visitor view.

The file must be named `profile/README.md`. A README at the repository root explains the repository itself and does not serve as the organization profile. Your other repositories can remain private; visitors without access will not be able to open their links.

If the Overview still shows GitHub's welcome tasks, check the repository visibility, file path, default branch, and whether the latest changes have been pushed.

## 2. Add the short description

Open the organization's **Settings → Profile**, enter a description, and save the profile.

Suggested description:

> Website audits with per-page SEO checks, clear evidence, and practical recommendations.

Use **MyPageAudit** as the display name. Add `https://mypageaudit.com` as the website when the domain points to a working site.

The description is independent of the README. Editing Markdown will not change this field.

## 3. Upload the organization avatar

In the same profile settings, use **Upload new picture** and select [profile/avatar.png](../profile/avatar.png). Save the change when prompted.

The image in the README is a separate display of the same logo. Committing the image does not replace GitHub's generated organization avatar automatically.

## Keep the content up to date

- Update [the public introduction](../profile/README.md) when features ship or repository names change.
- Keep future goals clearly identified as plans.
- Use the [organization repository](https://github.com/mypageaudit/organization) for detailed product planning and release notes.
- Keep deployment instructions in the relevant implementation repositories.

For a members-only Overview README, GitHub requires a separate private `.github-private` repository containing `profile/README.md`. The public `.github` repository can continue serving the visitor profile and shared community files.

[GitHub's organization profile documentation](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile) explains public and member views, profile READMEs, and avatar settings.
