# SocialDomainRedirect

## Project Idea

SocialDomainRedirect is a simple project designed to help you create a personal landing page that redirects visitors to your various social media profiles. By configuring a single HTML file, you can provide a centralized location for all your social media links.

## Example

To illustrate how SocialDomainRedirect works, let's consider an example. Suppose you want to redirect visitors from `ig.your-domain.com` to your Instagram profile at `instagram.com/@your-username`. You would configure your `index.html` file as follows:

```js
const subdomainRedirects = {
                "yt": "https://youtube.com/@channel",
                "youtube": "https://youtube.com/@channel",
                "fb": "https://facebook.com/@page",
                "facebook": "https://facebook.com/@page",
                "ig": "https://instagram.com/@profile",
                "instagram": "https://instagram.com/@profile",
                "tt": "https://tiktok.com/@profile",
                "tiktok": "https://tiktok.com/@profile",
                "x": "https://twitter.com/@profile",
                "twitter": "https://twitter.com/@profile",
                "discord": "https://discord.gg/@server",
                "github": "https://github.com/profile",
                "linkedin": "https://linkedin.com/in/profile",
                "tw": "https://twitch.tv/profile",
                "twitch": "https://twitch.tv/profile",
                "spotify": "https://open.spotify.com/user/profile",
                "steam": "https://steamcommunity.com/id/profile"
            };
```

By setting up your DNS records to point `ig.your-domain.com` to your GitHub Pages site, visitors will be automatically redirected to your Instagram profile when they visit `ig.your-domain.com`.

## Requirements

To use this project, you will need:
- A GitHub account
- Basic knowledge of HTML
- A text editor (such as VS Code, Sublime Text, or Notepad++)

## Configuration

To configure the `index.html` file, follow these steps:
1. Fork the repository to your GitHub account.
2. Open the `index.html` file in your preferred text editor.
3. Locate the section where you need to add your social media links.
4. Replace the placeholder URLs with your actual social media URLs.
5. Save the changes to the `index.html` file.

## Hosting with GitHub Pages

You can easily host your site using GitHub Pages by following these steps:

1. Push your project to a GitHub repository.
2. Go to the repository settings.
3. Scroll down to the "GitHub Pages" section.
4. Select the branch you want to use for GitHub Pages (usually `main` or `master`).
5. Click "Save" to enable GitHub Pages for your repository.

Your site will be available at `https://<your-username>.github.io/<repository-name>/`.

## License

This project is licensed under the Apache-2.0 license. See the [LICENSE](LICENSE) file for more details.