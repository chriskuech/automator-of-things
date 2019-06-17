Mostly inspired from our time working on microsoft.com SRE team.

# Guides

<a id="aot-security"></a>
## Security
#### [Managing Application Secrets](https://medium.com/@zwc101/managing-application-secrets-88dd8d54d14a)
Harden your application against attacks by applying these security best practices to your DevOps system.
#### [Defensive PowerShell with Validation Attributes](https://medium.com/@cjkuech/defensive-powershell-with-validation-attributes-8e7303e179fd)
Identify malicious input early, often, and easily with Validation Attributes.

<a id="aot-patterns"></a>
## PowerShell Patterns
General programming patterns you can apply to your PowerShell to encourage idiomatic code.
### Maintainability
PowerShell can be hard to maintain at scale because it lacks well-known patterns for maintainability.  Rather than resort to more cumbersome languages, we can apply these patterns to make sure our PowerShell projects stay maintainable at scale.
#### [Writing Maintainable PowerShell](https://medium.com/@cjkuech/writing-maintainable-powershell-503e5b680ed9)
The MVC design pattern keeps large user-facing applications maintainable with strict separation of concerns.  We can adapt the same pattern to make our PowerShell DevOps code more maintainable.
#### [Defensive PowerShell with Validation Attributes](https://medium.com/@cjkuech/defensive-powershell-with-validation-attributes-8e7303e179fd)
Validation Attributes are a declarative way of validating variables early and often.  Learn about the value of defensive programming and how to fail-fast in your PowerShell code with Validation Attributes.
### [Functional Programming](https://medium.com/@cjkuech/functional-programming-in-powershell-876edde1aadb)
Functional Programming is a paradigm partially supported by PowerShell.  Understand the concepts and value of this paradigm, and learn to write idiomatic PowerShell using these patterns.
#### [Deep Equality with Pester](https://medium.com/@cjkuech/deep-equality-with-pester-a9a00c3cd8a1)
Pester does not support deep equality testing in its assertion library.  This tutorial explains recursive functions and the various types of equality in PowerShell, as it walks you through writing your own deep equality function for use with Pester.
#### [Functional PowerShell with Classes](https://medium.com/@cjkuech/functional-powershell-with-classes-820c8e9acd8f)
Classes are associated with Object-Oriented Programming and rarely associated with Functional Programming.  This guide shows you how to leverage PowerShell classes while keeping your code functional.
### [Classes](https://medium.com/@cjkuech/you-should-be-using-powershell-classes-9966db76f909)
Classes are a new construct as of PowerShell 5.  They still have room for improvement, but can still be leveraged to immediately improve your code.
#### [New to PowerShell? Use Classes](https://medium.com/@cjkuech/new-to-powershell-use-classes-ab7b1e6f72ec)
New PowerShell developers can use classes to minimize PowerShell's learning curve.
#### [Functional PowerShell with Classes](https://medium.com/@cjkuech/functional-powershell-with-classes-820c8e9acd8f)
Advanced PowerShell programmers can apply classes to make their code more abstracted and functional.

<a id="aot-microframeworks"></a>
## Declarative DevOps Microframeworks
[Declarative DevOps Microframeworks](https://medium.com/@cjkuech/declarative-devops-microframeworks-9908c8d05332) is the most robust, portable, and scalable pattern for managing your DevOps systems with less code. This series will help you understand the concepts behind Declarative DevOps Microframeworks, then walk you through implementing some common use cases in the most DevOps-friendly language: PowerShell.
### Concepts
First, learn about Declarative DevOps systems, the Microframeworks pattern, and how to package a DevOps microframework.
#### [Functional Programming in PowerShell](https://medium.com/@cjkuech/functional-programming-in-powershell-876edde1aadb)
Functional Programming is closely related to Declarative Programming and very beneficial for idiomatic PowerShell code. This article is beyond the scope of this series, but most of the articles in this series either implicitly or explicitly reference the concepts outlined in Functional Programming in PowerShell.
#### [Declarative DevOps](https://medium.com/@cjkuech/declarative-devops-30788ddd43cd)
Declarative DevOps is a rapidly growing trend. Learn how Declarative Programming has influenced DevOps, what constitutes a Declarative config file, and where you can start using Declarative DevOps tools today.
#### [DevOps Microframeworks](https://medium.com/@cjkuech/devops-microframeworks-715b882b979c)
Microframeworks are small frameworks that adhere to Separation of Concerns. Rather solving all your problems, a microframework only solves one of your problems, helping you avoid locking yourself into a specific technology. Learn why microframeworks are especially beneficial for DevOps.
#### [Private PowerShell Modules](https://itnext.io/private-powershell-modules-76f51a1bf893)
PowerShell modules are the easiest way to package and deploy your DevOps Microframeworks. Before you learn how to write your microframeworks, learn how to package and consume them.

<a id="aot-applications"></a>
### Application
Learn how to apply the concepts behind Declarative DevOps Microframeworks with these walkthroughs of practical use cases for Declarative DevOps Microframeworks.
#### [Declarative Configuration Management](https://medium.com/@cjkuech/declarative-config-management-daec4007bb77)
Configuration management can be either extremely difficult or extremely simple. This walkthrough will show you how thoughtfully posing the problem can help you solve configuration management in only a few lines of PowerShell.
#### [Declarative Idempotency](https://medium.com/@cjkuech/declarative-idempotency-aaa07c6dd9a0)
Idempotency is extremely pertinent to DevOps, as errors in DevOps code can easily cause system outages. Idempotency can add a lot of redundant code to your codebase. Learn how to factor out your idempotency code into a Declarative DevOps Microframework.
#### [Declarative Work-Item Management](https://medium.com/@cjkuech/automating-work-item-management-fd9add6351d0)
Your processes should make your team more agile, not cause daily toil. This guide walks through creating a microframework for declaratively managing work items as code annotations instead of manually updating work items in Azure Boards or Jira.
