# Security Policy

This security policy applies to all projects under the [MyDecisive organization](https://github.com/mydecisive) on GitHub. Security reports involving a specific project should still be reported following the instructions in this document: the report will be shared with the relevant project maintainers, who might not all have access to the private key required to decrypt your message.

## Security model

When assessing the urgency and importance of a security fix, confidentiality and integrity are our topmost concerns for all MyDecisive software artifacts.

We highly recommend not relying on our Octant UI alone to generate secure configurations for you. You should review and understand each configuration directive to the best of your abilities to help ensure secure deployment of SmartHub and Octant in your environment. To protect the availability and integrity of your MyDecisive solution, users should require authentication for their endpoint communication.

## Supported Versions

MyDecisive provides community support for the `main` branch. Bug fixes and security fixes are delivered on `main`, and any patch or release versions are cumulative, meaning that they represent the state of our `main` branch at the moment of the release. We recommend tracking `main` to ensure you have the latest fixes.

Security fixes are given priority and might be enough to cause a new release.

## Reporting a Vulnerability

If you find something suspicious and want to report it, we'd really appreciate it!

### Ways to report

In order for vulnerability reports to reach maintainers as soon as possible, the preferred way is to use the `Report a vulnerability` button on the `Security` tab in the respective GitHub repository. It creates a private communication channel between the reporter and the maintainers.

If you are absolutely unable to, or have strong reasons not to use the GitHub reporting workflow, please reach out to [security@mydecisive.ai](mailto:security@mydecisive.ai).
