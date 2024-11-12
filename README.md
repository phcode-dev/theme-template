# Theme Template

Quick start and create a new theme by using this template. Follow the below 4 steps:

Refer this [link](https://docs.phcode.dev/api/creating-themes) for detailed theme documentation after following the below steps:

## step 1

Login with github: https://github.com/login

## step 2

Create a new repository using this template.
![New extension from template](https://user-images.githubusercontent.com/5336369/223931565-2708e516-a422-4e7b-9d89-9ac48c919c3d.gif)

## step 3

* Clone your GitHub Repository created from `step 2`. See [this link](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) to learn how to clone a repository from GitHub.
* Edit `package.json` file in template, make sure to update the following fields accordingly:

| Field       | Description                                                            |
|-------------|------------------------------------------------------------------------|
| `title`     | Replace "Name of the extension" with the actual title of your extension. |
| `name`      | Change `github-<owner>-<repo>` to your specific package name, formatted as `github-yourusername-reponame`. |
| `description` | Update to a brief, relevant description of what your extension does.  |
| `version`   | Start with "0.0.1" or update to reflect your current version following semantic versioning. |
| `license`   | Confirm "MIT" is suitable or specify another license if necessary.     |
| `author`    | Replace with your name and a link to your GitHub profile or another URL. |
| `homepage`  | Set to the URL of your project’s homepage or GitHub repository.        |
| `engines`   | Ensure compatibility with the required Brackets version, e.g., ">=3.0.0". |
| `categories`| Update "demo" with relevant categories that fit your extension.         |
| `keywords`  | Update or append additional keywords that describe your extension.    |
| `files`     | Ensure this includes all necessary files and folders for your extension. |


## step 4

* Go to https://create.phcode.dev .This is a special development centric website of phcode.dev which shows non minified js/css files in the browser developer tools.
* Open the cloned folder and select `Debug > Load Project As Extension`

![image](https://user-images.githubusercontent.com/5336369/224746152-0416a862-891a-4fe1-b9dd-09add25a6cc0.png)


* You can now make code changes to your theme and live preview theme changes as you edit your theme css.

![theme dev](https://user-images.githubusercontent.com/5336369/222974377-e3c04920-dd2b-4eab-be35-57df403ff249.gif)
* You can also select `Debug> Reload With Extensions` to test the new code changes.
* When you are done developing the extension/theme, select `Debug> Unload Project As Extension` to unload the extension/theme.

![image](https://user-images.githubusercontent.com/5336369/224747590-556dff1d-5b29-41c3-88a0-3ce72ab643d0.png)

# Detailed Documentation

Please go to [https://docs.phcode.dev/api/creating-themes](https://docs.phcode.dev/api/creating-themes) for more documentation/community support links.

# Publishing your theme to the repository
Once you have built your theme, you can publish the theme to phcode.dev extension store in a single step directly from this repository.
Please see publish section in this link for more details: [Publishing extension and themes](https://docs.phcode.dev/api/publishing-extensions)