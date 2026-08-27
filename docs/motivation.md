# Objective & Motivation

The established practice for creating electronic software-based control systems in regulated industries is based largely on methodological approaches developed for proprietary, organization-controlled software development. These approaches do not always take open source code-driven development, including its governance and collaboration models, into account.

However, the success of open source software in critical business and societal applications demonstrates that open source communities can develop effective methodologies and practices. Some projects have achieved widespread acceptance, including in areas with stringent quality, security, or certification expectations. This makes open source software relevant to other regulated and high-assurance domains, including functional safety. Nevertheless, a project's success or adoption does not by itself establish its suitability for a particular use case or its compliance with a specific standard.

As a consequence, to support the informed evaluation, adoption, and improvement of open source software, including its wider adoption in regulated industries, it is crucial to document the practices and processes executed by open source communities and the evidence available for them. This documentation provides transparency and facilitates understanding of the methodologies employed. Much of this information is publicly observable, but it is often distributed across source code repositories, project documentation, development infrastructure, and community processes. By making it easier to identify and assess, the work further supports downstream organizations to relate open source practices to their own quality-management and assurance obligations.

The initial direction for this work was presented in [Best Practices Standard](https://directory.elisa.tech/workshops/2025-05-Lund/3-3-Best_Practices_Standard.pdf) at the ELISA Workshop in Lund in May 2025 and further developed in [Kickoff: OSS Best Practices Standard](https://github.com/elisa-tech/lighthouse-oss/wiki/files/2025-06-20_lighthouse-oss-kickoff.pdf) at the Lighthouse OSS SIG kickoff in June 2025. These presentations distinguished the immediate work of documenting established open source development best practices and providing an assessment guide from the longer-term objective of developing a standard.

## Objectives

The Lighthouse OSS Special Interest Group aims to:

- evaluate and document established open source development best practices;
- provide a checklist and assessment guide for users to evaluate open source project quality; and
- help users understand which practices a project defines, how they are applied, what observable evidence is available, and where gaps may remain.

The work draws on research literature, existing standards, public best-practice frameworks, and evidence observed in open source projects.

## Scope

Software quality is the broad scope of this work. Safety, security, and other regulated or high-assurance environments are important application contexts, but they are not the exclusive focus.

The checklist and assessment guide do not claim general equivalence between open source development and proprietary or requirements-driven development. Instead, they provide a structured way to examine open source practices and their supporting evidence. Conclusions about suitability or compliance depend on the intended use and the applicable assurance or regulatory context.

## Relation to functional safety

Quality, cybersecurity, and functional safety (FuSa) standards aim for a certain level of reliability for the development of electronic devices with a protective function for hazardous machines and systems that reduces the risk to people and society when operating these machines and systems to an acceptable level. All these standards, although aiming for different verticals as well as different risk scenarios, require disciplined development practices, software resilience and stability, and evidence that relevant risks have been identified and addressed.

Functional safety standards such as IEC 61508 and ISO 26262 describe lifecycle processes, methods, and tools for developing electronic systems with safety-relevant functions, with which the unacceptable risk of errors is reduced to an acceptable level. When open source software is considered in such a context, its publicly observable practices and evidence can help downstream users understand how relevant expectations may be addressed, where gaps remain, and which additional downstream activities may be necessary. The SIG's work can inform this analysis, but does not replace and cannot be held accountable for use-case-specific safety analysis, qualification, or certification activities.

## Relationship to existing work

The SIG studies existing standards, best-practice frameworks, assessment programs, and related ecosystem initiatives to understand their purposes, coverage, expected evidence, overlaps, and gaps. The goal is to build on and reference existing work where appropriate, not to reproduce it, impose a single ranking, or claim universal equivalence between different approaches.

## Longer-term objective

The current work focuses on documenting best practices and developing a practical assessment guide. In the longer term, these community-developed artifacts may provide a foundation for a standard on open source development best practices. This possible future standardization is an ambition rather than a claim about the current maturity or status of the work.
