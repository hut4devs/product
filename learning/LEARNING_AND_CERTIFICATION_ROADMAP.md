# Hut4Devs Learning & Certification Roadmap

**Research checked:** 11 October 2026
**Current product phase:** Phase 1 --- Product Definition & Discovery,
with foundation/governance work underway.

> **Product definition:** Hut4Devs is an open-source project that helps
> people living together manage shared expenses, support one another,
> and build trust through transparency and collaboration.

## Executive recommendation

Prioritise **design thinking and evidence-based user research**,
supported by a **shared cybersecurity/privacy foundation**. Do not train
everyone in AI engineering yet. First validate the initial user problem
and MVP journey; then train specialists against approved work.

The uploaded *Hut4Devs Production-Ready Specialization Framework*
(pp. 2--5) sets out **Discover → Define → Design → Build → Assure →
Operate → Grow**, says readiness is shared, and values evidence over
assertion. Its 11 core tracks cover design thinking/research, product
management, UX, frontend, backend/data, Stellar/Soroban, AI systems,
DevOps, QA/reliability, security/privacy/trust, and open-source
governance/DevRel. It cautions that a framework is not proof that every
capability is implemented or production-certified.

**Credential distinction:** LinkedIn Learning usually provides
course-completion certificates, not necessarily professional
certifications. Free platforms may provide a course certificate, badge,
profile achievement, or statement of participation. These are not
interchangeable. Check current award rules and fees before enrolling.

## 1. Learning mapped to the product life cycle

  ---------------------------------------------------------------------------------
  Phase             Hut4Devs priority Learning objective          Evidence of
                                                                  application
  ----------------- ----------------- --------------------------- -----------------
  **1. Discover &   **Current**       Validate users, problem,    Interview plan,
  Define**                            workarounds, privacy        anonymised
                                      expectations, constraints,  findings, problem
                                      and success measures.       statement,
                                                                  assumptions log,
                                                                  success measures,
                                                                  initial threat
                                                                  notes.

  2\. Design        Next              Turn validated needs into   Journey map,
                                      journeys, prototypes,       prototype,
                                      accessibility/consent       usability
                                      patterns, requirements,     findings,
                                      acceptance criteria.        acceptance
                                                                  criteria.

  3\. Build         After MVP scope   Implement small,            Reviewed PR,
                    approval          maintainable increments     tests, API/data
                                      with explicit               contract, setup
                                      frontend/backend/contract   documentation.
                                      boundaries.

  4\. Assure        Begins now as a   Test normal and failure     Test evidence,
                    cross-cutting     paths, permissions,         threat model,
                    practice          privacy, dependencies, and  risk register,
                                      security assumptions.       release
                                                                  checklist.

  5\. Operate       Before real-user  Deploy safely, manage       Runbook,
                    release and       secrets, observe, back up,  monitoring,
                    continuously      recover, and respond to     backup/restore
                                      incidents.                  evidence,
                                                                  incident
                                                                  playbook.

  6\. Grow          After validated   Improve from user evidence; Product metrics,
                    usage             scale only where data       feedback,
                                      justifies it.               onboarding
                                                                  improvements,
                                                                  reviewed roadmap
                                                                  changes.
  ---------------------------------------------------------------------------------

Security, privacy, accessibility, testing, documentation, and
operational ownership are not deferred until later phases. The depth of
specialist learning changes; baseline responsibility begins now.

## 2. LinkedIn Learning --- first priority: Phase 1

Course catalogue information was checked on 11 October 2026. Durations
and release dates are those shown by the catalogue; availability and
completion requirements can change. The team's previously discussed
Premium access was 60 days, so verify the actual expiry date.

  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Priority          Course and official link                                                                      Duration /  Audience                  Why it helps       Required applied
                                                                                                                  freshness                             Hut4Devs           output
                                                                                                                  shown
  ----------------- --------------------------------------------------------------------------------------------- ----------- ------------------------- ------------------ --------------------
  **P0**            [Design Thinking: Understanding the Process --- Chris                                         43 min;     Everyone, especially      Establishes        One-page problem
                    Nodder](https://www.linkedin.com/learning/design-thinking-understanding-the-process)          released 26 research/product/UX       human-centred      frame: user,
                                                                                                                  Oct 2020                              problem framing    situation, pain,
                                                                                                                                                        before jumping     workaround, evidence
                                                                                                                                                        from "shared       needed.
                                                                                                                                                        expenses" to
                                                                                                                                                        features.

  **P0**            [Data-Driven Product Research and Design --- Shanae                                           2h 20m;     Product, research, UX,    Connects research  Research questions,
                    Chapman](https://www.linkedin.com/learning/data-driven-product-research-and-design)           released 11 community leads           and design         evidence plan,
                                                                                                                  Jan 2024                              decisions to       success measure,
                                                                                                                                                        evidence, helping  short synthesis.
                                                                                                                                                        select the first
                                                                                                                                                        high-value
                                                                                                                                                        coordination
                                                                                                                                                        problem.

  **P0**            [Market Research: Qualitative --- Sarah                                                       1h 52m;     Research, product, UX,    Improves interview Consent-aware
                    Weise](https://www.linkedin.com/learning/market-research-qualitative)                         released 4  DevRel                    practice and       interview guide and
                                                                                                                  Dec 2024                              separates          anonymised
                                                                                                                                                        observations from  insight/assumption
                                                                                                                                                        assumptions.       table.

  **P1**            [Product Management: Building a Product                                                       1h 5m;      Product, maintainers,     Helps connect a    Strategy one-pager:
                    Strategy](https://www.linkedin.com/learning/product-management-building-a-product-strategy)   released 18 team leads                validated problem  user, outcome,
                                                                                                                  Jan 2018                              to outcomes,       non-goals, risks,
                                                                                                                                                        priorities, and    measures.
                                                                                                                                                        non-goals. Older
                                                                                                                                                        content: pair with
                                                                                                                                                        current evidence.

  **P1**            [Product Management: Building a Product                                                       47 min;     Product and maintainers   Helps sequence     One milestone with
                    Roadmap](https://www.linkedin.com/learning/product-management-building-a-product-roadmap)     released 18                           work without       outcome, exit
                                                                                                                  Jan 2018                              treating the       evidence,
                                                                                                                                                        roadmap as a date  dependencies, open
                                                                                                                                                        promise or         decisions.
                                                                                                                                                        creating hundreds
                                                                                                                                                        of speculative
                                                                                                                                                        issues.

  **P1**            [Technical Product Management --- Dr. Marily                                                  1h 5m;      Product and engineering   Connects user      Decision brief
                    Nika](https://www.linkedin.com/learning/technical-product-management)                         released 2  leads                     outcomes with      including an
                                                                                                                  Feb 2022                              technical          off-chain
                                                                                                                                                        constraints and    alternative to any
                                                                                                                                                        cross-repository   proposed blockchain
                                                                                                                                                        trade-offs.        feature.

  **P0              [Cybersecurity Foundations --- Malcolm                                                        3h 31m;     All contributors; deeper  Shared awareness   Threat brainstorm:
  cross-cutting**   Shore](https://www.linkedin.com/learning/cybersecurity-foundations)                           released 17 follow-up for             of threats,        assets, actors,
                                                                                                                  Mar 2023    security/backend/DevOps   frameworks, and    abuse cases,
                                                                                                                                                        incident response  controls, unknowns.
                                                                                                                                                        before handling
                                                                                                                                                        personal or
                                                                                                                                                        financial records.

  **P1              [Cybersecurity Foundations: Application                                                       46 min;     Frontend, backend, QA,    Introduces common  Security acceptance
  cross-cutting**   Security](https://www.linkedin.com/learning/cybersecurity-foundations-application-security)   released 23 security                  application        criteria for auth,
                                                                                                                  Jun 2023                              vulnerabilities    authorization,
                                                                                                                                                        and defences       validation, errors,
                                                                                                                                                        relevant to code   sensitive data.
                                                                                                                                                        review and
                                                                                                                                                        acceptance
                                                                                                                                                        criteria.
  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### LinkedIn Learning courses for later phases

  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Phase          Course                                                                                                         Duration /     Why it helps            Applied output
                                                                                                                                freshness
                                                                                                                                shown
  -------------- -------------------------------------------------------------------------------------------------------------- -------------- ----------------------- ------------------
  Design         [UX Foundations: Usability Testing](https://www.linkedin.com/learning/ux-foundations-usability-testing)        1h 29m;        Tests whether residents Test script,
                                                                                                                                released 2 Nov understand status,      observations,
                                                                                                                                2015           records, corrections,   ranked usability
                                                                                                                                               and visibility          issues.
                                                                                                                                               settings. Older course;
                                                                                                                                               pair with current
                                                                                                                                               accessibility/privacy
                                                                                                                                               guidance.

  Design         [Building and Mapping User Stories](https://www.linkedin.com/learning/building-and-mapping-user-stories)       35 min;        Turns validated         Story map and
                                                                                                                                released 3 May journeys into small     acceptance
                                                                                                                                2023           reviewable slices.      criteria.

  Build          [Become a Software Developer](https://www.linkedin.com/learning/paths/become-a-software-developer)             12 courses, 39 Broad development       Small feature PR
                                                                                                                                hours;         fundamentals;           with tests and
                                                                                                                                catalogue      supplement with         setup note.
                                                                                                                                notes update   track-specific
                                                                                                                                date 15 Sep    TypeScript, Go,
                                                                                                                                2026           Rust/Soroban, APIs, and
                                                                                                                                               databases.

  Build          [Programming Foundations: Test-Driven                                                                          2h 43m;        Encourages test-first   One behaviour
                 Development](https://www.linkedin.com/learning/programming-foundations-test-driven-development)                released 17    development for         through failing
                                                                                                                                Jun 2019       repayment calculations, test → passing
                                                                                                                                               permissions, state      test → refactor.
                                                                                                                                               transitions, and
                                                                                                                                               contract invariants.

  Build          [Programming Foundations: APIs and Web                                                                         1h 55m;        Supports safe API       Endpoint schema,
                 Services](https://www.linkedin.com/learning/programming-foundations-apis-and-web-services)                     released 28    contracts and           authorization,
                                                                                                                                Apr 2025       frontend/backend        errors, retries,
                                                                                                                                               integration.            idempotency.

  Assure         [TestMu AI Software Testing Professional Certificate                                                           4 courses, 5   Structured testing      Test plan with
                 path](https://www.linkedin.com/learning/paths/testmu-ai-software-testing-professional-certificate)             hours;         learning for QA and     negative paths and
                                                                                                                                catalogue      engineering. Confirm    permission cases.
                                                                                                                                describes      exam/certificate is
                                                                                                                                final exam and included in team
                                                                                                                                professional   access.
                                                                                                                                certificate

  Assure         [Explore a Career in Application                                                                               7 courses,     Deeper                  Findings from an
                 Security](https://www.linkedin.com/learning/paths/explore-a-career-in-application-security)                    about 16 hours application-security    authorised test
                                                                                                                                               pathway for security,   environment,
                                                                                                                                               backend, frontend, QA.  prioritised and
                                                                                                                                                                       remediated.

  Operate        [Cybersecurity Foundations: Security                                                                           44 min;        Connects security       Update
                 Architecture](https://www.linkedin.com/learning/cybersecurity-foundations-security-architecture)               released 16    controls to system      architecture
                                                                                                                                Nov 2022       architecture.           boundaries and
                                                                                                                                                                       threat model with
                                                                                                                                                                       control owners.

  Operate        [Become a Cybersecurity                                                                                        5 courses, 8   Introductory path       Incident scenario
                 Professional](https://www.linkedin.com/learning/paths/become-a-cybersecurity-professional)                     hours          including security      walkthrough and
                                                                                                                                               foundations and threat  risk-treatment
                                                                                                                                               landscape.              backlog.

  Grow / AI      [AI Product Development: Technical Feasibility and                                                             2h 6m          Helps assess            Compare non-AI
                 Prototyping](https://www.linkedin.com/learning/ai-product-development-technical-feasibility-and-prototyping)                  feasibility before      baseline with
                                                                                                                                               committing to AI.       small prototype on
                                                                                                                                                                       quality/cost
                                                                                                                                                                       criteria.

  Grow / AI      [AI Product Development: Secure by                                                                             Check current  Makes risk and control  AI data-flow,
                 Design](https://www.linkedin.com/learning/ai-product-development-secure-by-design)                             catalogue for  design part of AI       abuse-case,
                                                                                                                                duration       planning.               human-fallback,
                                                                                                                                                                       and rollback
                                                                                                                                                                       review.

  Grow / AI      [The AI-Native Product Manager's                                                                               1h 8m;         Recent AI-product       Permission-aware
                 Toolkit](https://www.linkedin.com/learning/the-ai-native-product-managers-toolkit)                             released 21    course, appropriate     experiment with
                                                                                                                                Jul 2026       after a use case is     evaluation and
                                                                                                                                               validated.              human review.
  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Availability warning:** LinkedIn Learning's [Getting Started with
Software
Testing](https://www.linkedin.com/learning/paths/getting-started-with-software-testing)
page said it would retire on 1 October 2026. As this snapshot is 11
October 2026, do not plan around that path unless the live page confirms
it remains available.

## 3. Totally free online learning with an award, badge, or profile achievement

"Free certification" is often used loosely. These are verified free
learning options, but not all are professional certifications.

  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Course / official link                                                                                            Cost and award type   Duration /    Best phase / track       Why it helps Hut4Devs           Reference to pair with it
                                                                                                                                          freshness
                                                                                                                                          shown
  ----------------------------------------------------------------------------------------------------------------- --------------------- ------------- ------------------------ ------------------------------- ----------------------------------------------------------------------------------
  [Cisco Networking Academy --- Introduction to                                                                     Free self-paced;      6 hours,      **Now:** everyone,       Threats, data/privacy,          [OWASP Top 10](https://owasp.org/www-project-top-ten/)
  Cybersecurity](https://www.netacad.com/courses/introduction-to-cybersecurity)                                     course page lists     beginner, 7   Security/Privacy/Trust   organisational protection,
                                                                                                                    achievements/badges   labs; checked                          legal/ethical issues.
                                                                                                                    and final exam        11 Oct 2026

  [Microsoft Learn --- Describe the concepts of                                                                     Free learning path    2h 17m,       **Now:** all tracks      Shared understanding of common  [NIST Cybersecurity Framework 2.0](https://www.nist.gov/cyberframework)
  cybersecurity](https://learn.microsoft.com/en-us/training/paths/describe-basic-concepts-of-cybersecurity/)        with module           beginner;                              threats and mitigations.
                                                                                                                    assessments/profile   checked 11
                                                                                                                    achievements; not the Oct 2026
                                                                                                                    paid SC-900 exam

  [Microsoft Learn --- Security, compliance, and identity                                                           Free path with module 1h 37m,       **Now:** Product,        Zero Trust, encryption/hashing, [OWASP
  concepts](https://learn.microsoft.com/en-us/training/paths/describe-concepts-of-security-compliance-identity/)    assessments/profile   beginner;     Backend, Security        identity,                       ASVS](https://owasp.org/www-project-application-security-verification-standard/)
                                                                                                                    achievements; not a   checked 11                             authentication/authorization,
                                                                                                                    professional          Oct 2026                               privacy/compliance.
                                                                                                                    certification exam

  [OpenLearn --- Design                                                                                             Free course; free     10 hours;     **Current Phase 1:**     Structures creative             *The Design of Everyday Things* --- Don Norman (book; access may cost).
  thinking](https://www.open.edu/openlearn/science-maths-technology/design-innovation/design-thinking/)             Statement of          updated 5 Dec research, product, UX,   problem-solving before choosing
                                                                                                                    Participation; badge  2018          DevRel                   features.
                                                                                                                    may be available

  [OpenLearn --- People-centred                                                                                     Free course; free     12 hours;     Phase 1--2: UX, Product, Usability and user-centred      [Nielsen Norman Group usability articles](https://www.nngroup.com/articles/)
  designing](https://www.open.edu/openlearn/science-maths-technology/design-innovation/people-centred-designing/)   Statement of          checked 11    Frontend, QA             design for people with
                                                                                                                    Participation; badge  Oct 2026                               different digital confidence.
                                                                                                                    may be available

  [OpenLearn --- First steps in innovation and                                                                      Free course; free     8 hours;      Phase 1: Product,        Challenges assumptions and      *Testing Business Ideas* --- Bland & Osterwalder (book; access may cost).
  entrepreneurship](https://www.open.edu/openlearn/money-business/first-steps-innovation-and-entrepreneurship/)     Statement of          checked 11    Operations               connects innovation to
                                                                                                                    Participation; badge  Oct 2026                               constraints and value.
                                                                                                                    may be available

  [GitHub Skills](https://github.com/skills)                                                                        Free interactive      Active        All phases, all          Practice real GitHub issues,    [Pro Git](https://git-scm.com/book/en/v2), free online book.
                                                                                                                    exercises; evidence   resource;     contributors             PRs, Actions, and repository
                                                                                                                    varies by exercise;   checked 11                             workflows used across Hut4Devs'
                                                                                                                    do not assume a       Oct 2026                               six repos.
                                                                                                                    formal certificate

  [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course/)              Free course and       Refreshed     Later AI Systems track   Practical ML foundations; not a Course glossary and exercises.
                                                                                                                    exercises; verify     modules;                               replacement for AI security,
                                                                                                                    current               checked 11                             privacy, evaluation, or product
                                                                                                                    badge/certificate     Oct 2026                               validation.
                                                                                                                    availability on the
                                                                                                                    page

  [OWASP Web Security Testing Guide](https://owasp.org/projects/web-security-testing-guide)                         Free open guide;      v4.2 listed   Build/Assure: QA,        Structured web application      The guide and its versioned PDF.
                                                                                                                    **not a certification as versioned  Frontend, Backend,       security testing guidance for
                                                                                                                    course**              release; v5.0 Security                 authorised test environments.
                                                                                                                                          in
                                                                                                                                          development
                                                                                                                                          when checked
  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Credential labels to use in team records

-   **Professional certification:** formal credential with defined
    assessment; exam may be paid even if learning materials are free.
-   **Course completion certificate:** completion evidence, not
    necessarily proof of professional competence.
-   **Digital badge / profile achievement:** platform evidence of
    learning or activity.
-   **Statement of Participation:** evidence of course completion; may
    not carry formal academic credit.
-   **Free learning resource:** useful material with no assumed
    credential.

For example, Microsoft Learn's free paths can help prepare for SC-900
topics, but the path itself is not the SC-900 certification. OpenLearn
says its free Statements of Participation do not carry formal
qualification credit. Cisco's course page lists free access, an exam,
and achievements; verify the actual badge in the learner account.

## 4. E-books and authoritative references

  -------------------------------------------------------------------------------------------------------------------------------------------------
  Resource                                                                               Access            How it helps Hut4Devs  When
  -------------------------------------------------------------------------------------- ----------------- ---------------------- -----------------
  [Pro Git](https://git-scm.com/book/en/v2)                                              Free online book  Branching, commits,    Now
                                                                                                           PRs, and collaboration
                                                                                                           across repositories.

  [OWASP Top 10](https://owasp.org/www-project-top-ten/)                                 Free online       Shared language for    Now / Build /
                                                                                         standard          common web risks; not  Assure
                                                                                                           a complete security
                                                                                                           checklist.

  [OWASP                                                                                 Free verification Turns security needs   Design / Build /
  ASVS](https://owasp.org/www-project-application-security-verification-standard/)       standard          into verifiable checks Assure
                                                                                                           for identity, access,
                                                                                                           validation, and
                                                                                                           controls.

  [OWASP Web Security Testing                                                            Free guide and    Structured             Build / Assure
  Guide](https://owasp.org/projects/web-security-testing-guide)                          versioned PDF     application-security
                                                                                                           test scenarios.

  [NIST Cybersecurity Framework 2.0](https://www.nist.gov/cyberframework)                Free framework    Organises security     Now / Operate
                                                                                                           outcomes, governance,
                                                                                                           protection, detection,
                                                                                                           response, and
                                                                                                           recovery.

  [NIST AI Risk Management                                                               Free framework    Structures AI risk     Before AI
  Framework](https://www.nist.gov/itl/ai-risk-management-framework)                                        identification and     experiments
                                                                                                           management before
                                                                                                           implementation.

  [Google ML Crash Course](https://developers.google.com/machine-learning/crash-course/) Free digital      ML concepts and        Later AI track
                                                                                         learning resource hands-on exercises.

  [The Design of Everyday                                                                Book; not         Affordances, feedback, Discover / Design
  Things](https://jnd.org/the-design-of-everyday-things-revised-and-expanded-edition/)   universally free  and usability for
  --- Don Norman                                                                                           UX/Product.

  [Testing Business Ideas](https://www.strategyzer.com/library/testing-business-ideas)   Book/toolkit; not Turns assumptions into Discover / Define
  --- David J. Bland & Alexander Osterwalder                                             universally free  experiments and
                                                                                                           evidence.

  [Threat Modeling: A Practical Guide for Development                                    Commercial book;  Deeper                 Design / Build /
  Teams](https://www.oreilly.com/library/view/threat-modeling-a/9781492056546/) --- Izar library access    threat-modelling       Assure
  Tarandach & Matthew J. Coles                                                           may be available  practice; free
                                                                                                           OWASP/NIST resources
                                                                                                           are alternatives.
  -------------------------------------------------------------------------------------------------------------------------------------------------

## 5. Recommended first two-week sequence

  ----------------------------------------------------------------------------
  Step           Who            Learning        Time target    Evidence of
                                                               application
  -------------- -------------- --------------- -------------- ---------------
  1              Everyone       LinkedIn:       43 min         Each person
                                Design                         submits one
                                Thinking:                      observation,
                                Understanding                  one assumption,
                                the Process                    and one
                                                               research
                                                               question.

  2              Everyone       Cisco           2--6 hours     List Hut4Devs
                                Introduction to                assets,
                                Cybersecurity                  plausible
                                **or**                         threats, and
                                Microsoft Learn                privacy
                                cybersecurity                  concerns.
                                path

  3              Product,       Data-Driven     About 4h 12m   Consent-aware
                 Research, UX,  Product                        interview plan,
                 Community      Research and                   anonymised
                                Design + Market                findings,
                                Research:                      evidence gaps.
                                Qualitative

  4              Product and    Product         About 2h 10m   Draft outcome,
                 technical      Strategy +                     non-goals,
                 leads          Technical                      constraints,
                                Product                        success
                                Management                     measures.

  5              Everyone       GitHub Skills + Flexible       Demonstrate
                                Pro Git as                     branch, issue,
                                needed                         PR, review, and
                                                               evidence-link
                                                               workflow.

  6              Whole team     Review applied  45--60 min     Decide what
                                artefacts                      remains unknown
                                                               and what must
                                                               not yet be
                                                               built.
  ----------------------------------------------------------------------------

## 6. Progression by specialization

  -----------------------------------------------------------------------
  Hut4Devs specialization             Learning progression
  ----------------------------------- -----------------------------------
  Design Thinking, Research &         Design Thinking → data-driven
  Validation                          research/design → qualitative
                                      research → usability testing →
                                      synthesis.

  Product Management & Strategy       Product strategy → roadmap →
                                      technical product management → user
                                      stories → experiments and metrics.

  Product Design / UX                 People-centred design → usability
                                      testing → journey mapping →
                                      accessibility and interaction
                                      design.

  Frontend Engineering                Development fundamentals → APIs →
                                      secure coding → testing/TDD →
                                      accessibility/performance.

  Backend & Data Engineering          APIs → TDD/testing → secure coding
                                      → identity/access → data
                                      lifecycle/threat modelling.

  Blockchain / Stellar Soroban        Official Rust/Soroban docs and
                                      project runbooks →
                                      invariants/testing → threat
                                      modelling → resource budgets and
                                      Testnet evidence. General courses
                                      alone do not establish contract
                                      readiness.

  AI Systems Engineering              ML foundations → AI
                                      feasibility/prototyping →
                                      secure-by-design → evaluation,
                                      permissions, human fallback,
                                      monitoring.

  DevOps & Platform Engineering       Git/GitHub → secure
                                      configuration/secrets → deployment
                                      automation → monitoring →
                                      backup/recovery/incident response.

  QA, Testing & Reliability           Testing/QA → TDD → API/security
                                      tests → failure-path/reliability
                                      tests → release evidence.

  Security, Privacy & Trust           Cisco/Microsoft fundamentals →
                                      identity/access → OWASP ASVS/Top
                                      10/WSTG → threat modelling →
                                      vulnerability handling/incident
                                      response.

  Open Source, Governance & DevRel    GitHub Skills →
                                      documentation/issues/reviews →
                                      contributor onboarding → community
                                      communication → transparent
                                      decisions/releases.
  -----------------------------------------------------------------------

## 7. Learning governance

The uploaded framework (p. 5) says capability should be demonstrated
through **reviewed work, tests, documentation, and shipped
increments---not labels alone**.

Record each learning activity with:

  -----------------------------------------------------------------------
  Field                               Record
  ----------------------------------- -----------------------------------
  Collaborator / specialization       Primary track and secondary skill.

  Course / provider / URL             Exact title and official link.

  Start / completion date             Plan around access expiry.

  Freshness                           Release/update date; write "not
                                      stated" if missing.

  Credential type                     Professional certification,
                                      completion certificate, badge,
                                      statement, or none.

  Cost                                Learning, credential, and exam fees
                                      separately; mark unknown if
                                      unclear.

  Applied artefact                    PR, tests, threat model, research
                                      synthesis, prototype, runbook, or
                                      docs.

  Reviewer / feedback                 Who confirmed the skill was applied
                                      correctly.

  Follow-up                           Next skill gap based on actual
                                      work.
  -----------------------------------------------------------------------

Suggested policy: favour one relevant course plus a reviewed project
artefact over several unrelated certificates. The previously discussed
five-day learning rhythm can be used as a light cadence if realistic; do
not rush a long course or compromise delivery just to hit a count. Use
synthetic data in exercises, never real accommodation, identity, or
financial records.

**AI safety gate:** AI must not become authoritative domain state or
independently decide lending, disputes, access, or personal
trustworthiness. Before approving AI work, document the validated need,
data permissions, quality evaluation, cost/latency, failure/misuse
cases, human correction, retention, and rollback.

## 8. Research notes and limitations

-   Catalogue details and free-award terms were checked on **11 October
    2026**; course availability, dates, durations, region access, and
    certificate rules may change.
-   LinkedIn catalogue listings found: Design Thinking: Understanding
    the Process (43m); Data-Driven Product Research and Design (2h 20m,
    Jan 2024); Market Research: Qualitative (1h 52m, Dec 2024);
    Cybersecurity Foundations (3h 31m, Mar 2023).
-   LinkedIn Learning course completion is not automatically an external
    professional certification.
-   Cisco's official course page lists Introduction to Cybersecurity as
    free, beginner-level, self-paced, about six hours, with a final exam
    and achievements.
-   Microsoft Learn paths offer free content and module
    assessments/profile achievements. Do not call these the paid SC-900
    certification.
-   OpenLearn offers free Statements of Participation; some courses also
    offer digital badges. Statements do not carry formal credit toward a
    qualification.
-   GitHub Skills is free interactive practice; do not assume a formal
    certificate.
-   OWASP WSTG is a free reference, not a certification course. Its
    project page listed v4.2 as the versioned release and v5.0 in
    development when checked.
-   This is a targeted shortlist, not a claim that every free course or
    certification has been surveyed. Verify current award, availability,
    and any exam fee on the provider's official page.

## Source catalogue

**LinkedIn Learning** - [Product
Management](https://www.linkedin.com/learning/topics/product-management) -
[User
Research](https://www.linkedin.com/learning/topics/user-research) -
[Design
Thinking](https://www.linkedin.com/learning/topics/design-thinking) -
[Cybersecurity Professional
path](https://www.linkedin.com/learning/paths/become-a-cybersecurity-professional) -
[Application Security
path](https://www.linkedin.com/learning/paths/explore-a-career-in-application-security) -
[Software Developer
path](https://www.linkedin.com/learning/paths/become-a-software-developer) -
[AI for Product
Management](https://www.linkedin.com/learning/topics/ai-for-product-management)

**Free Stellar learning resources**

- [Stellar Quest Learn](https://quest.stellar.org/learn/)  interactive Stellar fundamentals and operations.
- [Stellar Learn](https://stellar.org/learn)  foundational learning on Stellar, blockchain, payments, and smart contracts.
- [Stellar Interactive Learning](https://developers.stellar.org/docs/learn/interactive)  interactive learning options.
- [Fast, Cheap, and 0ut 0f Control (FCA00C)](https://developers.stellar.org/docs/learn/interactive/fca00c)  smart-contract learning quests.
- [Soroban Getting Started](https://developers.stellar.org/docs/build/smart-contracts/getting-started)  build, test, and deploy contracts.
- [Stellar Smart Contract Examples](https://developers.stellar.org/docs/build/smart-contracts/example-contracts)  example contracts and implementation patterns.
- [Stellar Developer Documentation](https://developers.stellar.org/)  official technical reference.
**Free learning / authoritative references** - [Cisco Introduction to
Cybersecurity](https://www.netacad.com/courses/introduction-to-cybersecurity) -
[Microsoft Learn
Cybersecurity](https://learn.microsoft.com/en-us/training/paths/describe-basic-concepts-of-cybersecurity/) -
[Microsoft Learn Security, Compliance &
Identity](https://learn.microsoft.com/en-us/training/paths/describe-concepts-of-security-compliance-identity/) -
[OpenLearn Design
Thinking](https://www.open.edu/openlearn/science-maths-technology/design-innovation/design-thinking/) -
[OpenLearn People-centred
Designing](https://www.open.edu/openlearn/science-maths-technology/design-innovation/people-centred-designing/) -
[OpenLearn Innovation &
Entrepreneurship](https://www.open.edu/openlearn/money-business/first-steps-innovation-and-entrepreneurship/) -
[GitHub Skills](https://github.com/skills) - [Google Machine Learning
Crash
Course](https://developers.google.com/machine-learning/crash-course/) -
[OWASP Top 10](https://owasp.org/www-project-top-ten/) - [OWASP
ASVS](https://owasp.org/www-project-application-security-verification-standard/) -
[OWASP WSTG](https://owasp.org/projects/web-security-testing-guide) -
[NIST Cybersecurity Framework](https://www.nist.gov/cyberframework) -
[NIST AI Risk Management
Framework](https://www.nist.gov/itl/ai-risk-management-framework)

------------------------------------------------------------------------

**Bottom line:** For Hut4Devs now, start with **design thinking +
evidence-based user research**, supported by a **shared
cybersecurity/privacy foundation**. Product strategy follows closely.
Build and specialist AI learning should follow validated requirements.
The team's edge comes from applying learning to reviewed project
evidence---not from certificates alone.
