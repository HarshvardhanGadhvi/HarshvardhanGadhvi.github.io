# My Resume Site

## Purpose

This README provides instructions on how to host a resume using Jekyll and GitHub Pages, following the principles outlined in Andrew Etter's "Modern Technical Writing." It is intended for individuals with basic knowledge of Markdown and Git.

## Prerequisites

- Basic knowledge of Markdown
- Git installed on your system
- Ruby and Jekyll installed
- A GitHub account

## Instructions

### 1. Principle: Use Lightweight Markup

**Etter's Principle**: Use lightweight markup languages for simplicity and ease of maintenance.

**Step**: Write your resume in Markdown. This format is easy to read and edit, making it ideal for technical documentation.

### 2. Principle: Use a Static Site Generator

**Etter's Principle**: Use static site generators to convert content into a website.

**Step**: Use Jekyll to convert your Markdown resume into a static website. Jekyll is a popular static site generator that integrates seamlessly with GitHub Pages.

- **Install Jekyll**: Run `gem install jekyll bundler`.
- **Create a New Site**: Run `jekyll new my-resume-site`.
- **Add Your Resume**: Place your `resume.md` file in the root directory.

### 3. Principle: Use Version Control

**Etter's Principle**: Use version control systems to track changes and collaborate.

**Step**: Use Git to manage your project. This allows you to track changes, collaborate with others, and revert to previous versions if needed.

- **Initialize Git**: Run `git init` in your project directory.
- **Commit Changes**: Use `git add .` and `git commit -m "Initial commit"` to save your work.

### 4. Principle: Host on a Forge

**Etter's Principle**: Use a forge to host your static site.

**Step**: Use GitHub Pages to host your site for free. This service integrates with GitHub repositories, making it easy to deploy your site.

- **Create a GitHub Repository**: Name it `username.github.io`.
- **Push Your Site**: Use `git push origin main` to upload your site to GitHub.
- **Enable GitHub Pages**: In the repository settings, set the source to the `main` branch.

## Further Resources

- [Markdown Guide](https://www.markdownguide.org/)
- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Modern Technical Writing by Andrew Etter](https://www.amazon.com/Modern-Technical-Writing-Introduction-Documentation/dp/1514780835)

## FAQ

**Q: Why is Markdown better than writing raw HTML?**  
A: Markdown is simpler and more readable, making it easier to write and maintain. It allows you to focus on content rather than formatting.

**Q: I changed the Markdown version of my resume, so why don’t I see the changes when I refresh the website in my browser?**  
A: Ensure you have committed and pushed your changes to the GitHub repository, and that GitHub Pages has had time to rebuild the site.

## Credits

- [Your Name]
- Theme by [Theme Author] (if applicable)