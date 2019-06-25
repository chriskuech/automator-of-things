These are various articles inspired by our time working on the microsoft.com SRE team primarily working on DevOps automation in PowerShell.  These practices allowed us to reduce our code volume by 95%.

Note that Medium is a soft-paywalled site, but these are special non-paywalled links.

# Guides

<a id="aot-security"></a>
## Security
#### [Managing Application Secrets](https://medium.com/@zwc101/managing-application-secrets-88dd8d54d14a)
Harden your application against attacks by applying these security best practices to your DevOps system.  (Currently not a friend link)
#### [Defensive PowerShell with Validation Attributes](https://itnext.io/defensive-powershell-with-validation-attributes-8e7303e179fd?source=friends_link&sk=14765ca9554709a77f8af7d73612ef5b)
Identify malicious input early, often, and easily with Validation Attributes.

<a id="aot-patterns"></a>
## PowerShell Patterns
General programming patterns you can apply to your PowerShell to encourage idiomatic code.
### Maintainability
PowerShell can be hard to maintain at scale because it lacks well-known patterns for maintainability.  Rather than resort to more cumbersome languages, we can apply these patterns to make sure our PowerShell projects stay maintainable at scale.
#### [Writing Maintainable PowerShell](https://itnext.io/writing-maintainable-powershell-503e5b680ed9?source=friends_link&sk=cb9d5774841a296904560f3e834776c1)
The MVC design pattern keeps large user-facing applications maintainable with strict separation of concerns.  We can adapt the same pattern to make our PowerShell DevOps code more maintainable.
#### [Defensive PowerShell with Validation Attributes](https://itnext.io/defensive-powershell-with-validation-attributes-8e7303e179fd?source=friends_link&sk=14765ca9554709a77f8af7d73612ef5b)
Validation Attributes are a declarative way of validating variables early and often.  Learn about the value of defensive programming and how to fail-fast in your PowerShell code with Validation Attributes.
### [Functional Programming](https://medium.com/swlh/functional-programming-in-powershell-876edde1aadb?source=friends_link&sk=e684adbee39b5c936e44e59a1126f4eb)
Functional Programming is a paradigm partially supported by PowerShell.  Understand the concepts and value of this paradigm, and learn to write idiomatic PowerShell using these patterns.
#### [Deep Equality with Pester](https://medium.com/swlh/deep-equality-with-pester-a9a00c3cd8a1?source=friends_link&sk=2013644007cecad8a8f667686c4f870e)
Pester does not support deep equality testing in its assertion library.  This tutorial explains recursive functions and the various types of equality in PowerShell, as it walks you through writing your own deep equality function for use with Pester.
#### [Functional PowerShell with Classes](https://medium.com/faun/functional-powershell-with-classes-820c8e9acd8f?source=friends_link&sk=9570a8944584ba79819dd755954b7534)
Classes are associated with Object-Oriented Programming and rarely associated with Functional Programming.  This guide shows you how to leverage PowerShell classes while keeping your code functional.
### [Classes](https://medium.com/@cjkuech/you-should-be-using-powershell-classes-9966db76f909?source=friends_link&sk=53484c368e5fd6d3f892bb7bb7aa8be7)
Classes are a new construct as of PowerShell 5.  They still have room for improvement, but can still be leveraged to immediately improve your code.
#### [New to PowerShell? Use Classes](https://itnext.io/new-to-powershell-use-classes-ab7b1e6f72ec?source=friends_link&sk=818e1447e59e377d5d37f641aade3d9d)
New PowerShell developers can use classes to minimize PowerShell's learning curve.
#### [Functional PowerShell with Classes](https://medium.com/faun/functional-powershell-with-classes-820c8e9acd8f?source=friends_link&sk=9570a8944584ba79819dd755954b7534)
Advanced PowerShell programmers can apply classes to make their code more abstracted and functional.

<a id="aot-microframeworks"></a>
## Declarative DevOps Microframeworks
[Declarative DevOps Microframeworks](https://medium.com/@cjkuech/declarative-devops-microframeworks-9908c8d05332?source=friends_link&sk=4e361c6020912fb160e626994a6e5184) is the most robust, portable, and scalable pattern for managing your DevOps systems with less code. This series will help you understand the concepts behind Declarative DevOps Microframeworks, then walk you through implementing some common use cases in the most DevOps-friendly language: PowerShell.
### Concepts
First, learn about Declarative DevOps systems, the Microframeworks pattern, and how to package a DevOps microframework.
#### [Functional Programming in PowerShell](https://medium.com/swlh/functional-programming-in-powershell-876edde1aadb?source=friends_link&sk=e684adbee39b5c936e44e59a1126f4eb)
Functional Programming is closely related to Declarative Programming and very beneficial for idiomatic PowerShell code. This article is beyond the scope of this series, but most of the articles in this series either implicitly or explicitly reference the concepts outlined in Functional Programming in PowerShell.
#### [Declarative DevOps](https://itnext.io/declarative-devops-30788ddd43cd?source=friends_link&sk=f7363f0ff3b3a31059f9a6473e2f949e)
Declarative DevOps is a rapidly growing trend. Learn how Declarative Programming has influenced DevOps, what constitutes a Declarative config file, and where you can start using Declarative DevOps tools today.
#### [DevOps Microframeworks](https://medium.com/@cjkuech/devops-microframeworks-715b882b979c?source=friends_link&sk=9872eebbc5966c7d31b7f3754303a036)
Microframeworks are small frameworks that adhere to Separation of Concerns. Rather solving all your problems, a microframework only solves one of your problems, helping you avoid locking yourself into a specific technology. Learn why microframeworks are especially beneficial for DevOps.
#### [Private PowerShell Modules](https://itnext.io/private-powershell-modules-76f51a1bf893?source=friends_link&sk=6091d95285ebfd4df4483cd6e9babee4)
PowerShell modules are the easiest way to package and deploy your DevOps Microframeworks. Before you learn how to write your microframeworks, learn how to package and consume them.

<a id="aot-applications"></a>
### Application
Learn how to apply the concepts behind Declarative DevOps Microframeworks with these walkthroughs of practical use cases for Declarative DevOps Microframeworks.
#### [Declarative Configuration Management](https://medium.com/@cjkuech/declarative-config-management-daec4007bb77?source=friends_link&sk=eced0bf506385e79292fc3ae2249776d)
Configuration management can be either extremely difficult or extremely simple. This walkthrough will show you how thoughtfully posing the problem can help you solve configuration management in only a few lines of PowerShell.
#### [Declarative Idempotency](https://itnext.io/declarative-idempotency-aaa07c6dd9a0?source=friends_link&sk=f0464e8e29525b23aabe766bfb557dd7)
Idempotency is extremely pertinent to DevOps, as errors in DevOps code can easily cause system outages. Idempotency can add a lot of redundant code to your codebase. Learn how to factor out your idempotency code into a Declarative DevOps Microframework.
#### [Declarative Work-Item Management](https://medium.com/swlh/automating-work-item-management-fd9add6351d0?source=friends_link&sk=5bfb6cd0379fdd489560d194521c4007)
Your processes should make your team more agile, not cause daily toil. This guide walks through creating a microframework for declaratively managing work items as code annotations instead of manually updating work items in Azure Boards or Jira.
