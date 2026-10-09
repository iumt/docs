# IUMT Manifesto

> **Draft 0.1 · Open for discussion**
>
> This document is a proposal for the shared principles of the Internet Unicode Migration Taskforce (IUMT). It has not yet been adopted by community consensus and does not represent an approved Internet standard.

## Our vision

**Different languages. Different scripts. One shared Internet.**

We envision an Internet in which people can use their own languages and writing systems throughout their digital lives, including in domain names, email addresses, and other essential identifiers.

The Internet should be a common space for humanity. The languages people speak and the scripts they write should not determine how fully they can participate.

**Names that belong. Zeichen, die verbinden.**

## Why we are here

Unicode already enables people to write and read in a wide range of languages. Yet parts of the Internet's underlying naming and addressing infrastructure still depend on historical ASCII-based representations.

Internationalized Domain Names (IDNs), IDNA, and Punycode have helped bridge this gap. They remain important for interoperability today, but they also reveal a distinction between the names people see and the representations machines exchange. Support for internationalized names and email addresses is still inconsistent across services and software.

IUMT seeks to investigate whether, where, and how more native Unicode support can be introduced through open standards and careful migration, without compromising the reliability of the Internet.

We do not assume that replacing Punycode alone would solve these challenges. DNS protocols, applications, security models, operational practices, and existing deployments all matter.

## Our guiding principles

### 1. Linguistic equality

Every language and writing system deserves respectful consideration in the design of digital infrastructure. Meaningful access should not depend on familiarity with the Latin alphabet.

### 2. Open standards and transparent development

Proposals should be publicly documented, technically reviewable, and developed through open cooperation. We seek dialogue with existing standards communities and institutions, not unilateral changes to shared Internet infrastructure.

### 3. Security and trust

Internationalized naming must account for visual confusables, script mixing, normalization, spoofing, phishing, and other security concerns. Greater linguistic inclusion must be accompanied by trustworthy safeguards.

### 4. Interoperability and continuity

Compatibility with existing systems, including DNS, DNSSEC, IDNA, email protocols, registries, resolvers, and applications, must be evaluated before proposing migration paths. Any transition should be realistic, measurable, and considerate of users and operators.

### 5. Evidence, experimentation, and practical results

Research, prototypes, interoperability tests, and reproducible experiments should inform decisions. We welcome difficult questions, critical analysis, and evidence that challenges our assumptions.

### 6. Consensus through understanding

We value listening over winning arguments and cooperation over competition. Consensus does not require everyone to think alike or every proposal to receive unanimous approval. Reasoned objections should be heard, documented, and addressed openly.

### 7. Voluntary and inclusive participation

People from technical, linguistic, cultural, academic, civic, and other backgrounds are invited to contribute. No participant should need institutional status to be heard.

## What we want to explore

IUMT invites collaborative work on questions such as:

- What would genuinely Unicode-native naming and addressing require at the protocol and application levels?
- Which limitations can be resolved through wider adoption of existing internationalization standards, and which require new standards?
- How can diverse scripts be supported while preserving predictable matching, resolution, and security?
- Which changes would be required for registries, root-zone operations, resolvers, DNSSEC, browsers, mail systems, and other software?
- How can experiments and migration strategies preserve backward compatibility and avoid fragmentation?
- How can communities whose scripts are currently underserved participate in setting requirements and evaluating results?

No answer is predetermined. Proposals should explain their tradeoffs and remain open to revision.

## How we work together

We aim to:

1. **Discuss openly** and welcome constructive disagreement.
2. **Document proposals and objections** so decisions can be understood and revisited.
3. **Test ideas** where practical, and publish methods and findings.
4. **Seek broad, informed agreement** before presenting collective positions.
5. **Respect existing standards processes** and the people responsible for operating today's Internet.

## Join the conversation

Explore ideas, raise questions, or propose changes in **[IUMT Consensus](https://github.com/orgs/iumt/discussions)**.

Concrete documentation changes and technical work can be proposed through **[GitHub Issues](https://github.com/iumt/docs/issues)** and pull requests.

This manifesto is intended to evolve with the community. Contributions are welcome.

## Status and endorsement

**This text is a draft, not a declaration of achieved consensus.** No formal endorsement or signature process has been established yet. Until such a process is openly defined, participation in a discussion or pull request should not be interpreted as signing this manifesto.

---

*An Internet for every language, shaped together.*
