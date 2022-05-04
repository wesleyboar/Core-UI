# TACC Core UI

The shared styles and components for TACC WMA Workspace Portals & Websites

> __Notice__: This is a potential future repo for [Core Styles].


## Related Repositories

- [Core CMS], the base CMS code for TACC WMA CMS Websites
- [Core Portal], the base Portal code for TACC WMA CMS Websites
- TAPIS UI, the base Portal code for TACC APIs (TAPIS)


## External Project Usage

...

## Local Development Setup

### Prequisites for Building the UI

* Nodejs 16.x

### ...

...


## Testing

...

### Production Deployment

The Core UI are not deployed alone _yet_. ¹

_For now_, the stylesheets are acquired or accessed by other repositories.

| Repo | Current Usage | Future Usage |
| - | - | - |
| __[Core CMS]__                  | ✅ as dependency used in Node script to build styles | ❌                                              |
| __[Core Portal]__               | ⚠️  copying code from [Core Styles]                   | as dependency that offers pre-built stylesheets |
| __TAPIS UI__                    | ❌                                                   | as dependency that offers pre-built stylesheets |
| __[Core CMS Pattern Library]¹__ | ❌ [researching][research-pattern-lib]               | as dependency that offers pre-built stylesheets |

<sub>¹ We wish to have a deployable pattern library that showcase avaialble UI.</sub>

[research-pattern-lib]: https://confluence.tacc.utexas.edu/x/FADMBQ


## Contributing

### Development Workflow

We use a modifed version of [GitFlow](https://datasift.github.io/gitflow/IntroducingGitFlow.html) as our development workflow. Our [development site](https://dev.cep.tacc.utexas.edu) (accessible behind the TACC Network) is always up-to-date with `main`, while the [production site](https://prod.cep.tacc.utexas.edu) is built to a hashed commit tag.
- Feature branches contain major updates, bug fixes, and hot fixes with respective branch prefixes:
    - `task/` for features and updates
    - `bug/` for bugfixes
    - `fix/` for hotfixes

### Best Practices

Sign your commits ([see this link](https://help.github.com/en/github/authenticating-to-github/managing-commit-signature-verification) for help)

### Resources

* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo)


<!-- Link Aliases -->

[Core CMS Pattern Library]: https://github.com/wesleyboar/Core-CMS-Pattern-Library
[Core Portal Deployments]: https://github.com/TACC/Core-Portal-Deployments
[Camino]: https://github.com/TACC/Camino
[Core Styles]: https://github.com/TACC/Core-Styles
[Core CMS]: https://github.com/TACC/Core-CMS
[Core Portal]: https://github.com/TACC/Core-Portal
