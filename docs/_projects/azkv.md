---
title: Azure Keyvault CLI
order: 2
---

In cooperation with other developers I've developed a CLI tool for Azure Keyvault. The tool is written in Python and is available on PyPi. 
The tool enables developers to use Azure Keyvaults as a secret store.

**PyPi**: <a href="https://test.pypi.org/project/azure-keyvault-cli/" target="_blank">PyPi package</a>
**Code**: <a href="https://github.com/mkah91/azure-keyvault-cli" target="_blank">https://github.com/mkah91/azure-keyvault-cli</a> 

Some of you may know [gopass](https://github.com/gopasspw/gopass) which is a cli tool for a password store maintained in a git repository.
The tool is restricted to use the git boundaries, which does mean, that you cant really manage access rights to the secrets.
The idea behind this project was to build a similar tool for Azure Keyvaults, in order to have a safe, secure and managed way to store secrets.
