# Flutter Interview Project

This is a small project for a Flutter interview. Please use the latest Flutter version with .

## Goal

Create an mobile application that can retrieves and displays the user repositories and organisations (and their repositories) in Github.

### UX/UI

Up to you but we suggest the following:

- Main page: Shows a random list of users (use getRandomUsers on github_api.dart) that can be tapped and also has a input box on the topbar for entering your own user id to retrieve data (use getUserData on github_api.dart)
- User page: Show user information retrieved (Personal Info including image). Has a link to navigate to user repositories page (use getUserRepos on github_api.dart). Has a link to navigate to user organisations page.
- Repositories page: List of repositories of the user with basic information displayed (the more graphical the better)
- Organisations page: List of organisations of the user with basic information displayed (the more graphical the better). Has a link to navigate to organisation repositories page ("Repositories page" above) - (use getOrgRepos on github_api.dart)

## Requirements

- Use latest stable flutter version (at this time > 2.2)
- Have [sound null safety](https://dart.dev/null-safety) enabled
- Use standard flutter navigation for screens (See bonus below for using Navigation 2.0)

## Retrieving data

To make things easier we have commited a github_api.dart file with the REST APIs needed to retrieve the information.

## Submitting the solution

Copy this repository to a repository on your name and add the solution there. It should be clear how to build and run the project locally. **Please don't FORK this repo**

## Bonus (don't need to be in the below specific order)

- A nice splash screen
- On using sound null safety properly: support null **only** when it really can be null
- Adding a spinner when information is loading
- Deal with errors coming from the backend (because eventually it will happen!)
- Make sure components/page boundaries are clear
- Some sort of Unit Test
- Some sort of Integration Test
- Use Navigation 2.0
- Add some sort of state management to show how that is done
- Follow Dart [style conventions](https://dart.dev/guides/language/effective-dart/style)
- Create a stream that refreshes the random displayed user list every 15 seconds
- Show common tools used for you daily development environment (linters, code formatter, git workflow and so on)
- Make sure the app works for the web as well
