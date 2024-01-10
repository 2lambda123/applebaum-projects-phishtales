# Troubleshooting
## Common Issues with GitHub Actions

If you encounter issues with the GitHub Actions run, follow the steps below to troubleshoot and resolve the problem:

1. Check the GitHub Actions Workflow File
2. Review the Error Logs
3. Verify Environment Variables and Secrets
4. Analyze and Modify Workflow Files
5. Test the Workflow Locally
6. Reach Out for Support and Documentation

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Analyzing Error Logs

To analyze the error logs and identify the cause of the issue, follow these steps:

1. Locate the Error Logs
2. Review the Error Messages
3. Check for Environment-Specific Errors
4. Search for Solutions in Documentation and Forums
5. Utilize GitHub Actions Troubleshooting Tools

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
