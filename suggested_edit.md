
Suggested edit for "Maintaining ownership continuity of your personal account's repositories"

Summary

Clarify the specific criteria and steps that allow a repository transfer or delegation of management for user-owned repositories when the owner cannot manage them personally. Add links to the relevant GitHub policies and practical guidance for both cases: when the owner is deceased and when the owner is alive but temporarily unable to respond.

Proposed changes

1. Replace the sentence:

"You can invite someone to manage your user owned repositories if you are not able to."

With:

"You can invite another user to manage a repository you own in situations where you will be unable to access or maintain it, provided GitHub's eligibility criteria are met. Repository transfer or delegation options depend on the specific circumstances — for example, an active owner who is temporarily unavailable versus an owner who has passed away — and may require verification under GitHub's policies."

2. Add a new subsection titled "When transfers or delegation are permitted" with the following guidance:

- Temporary unavailability (owner alive but unreachable):
  - GitHub does not provide an automatic global "temporary access delegation" feature, but you can proactively add a collaborator or an organization owner as a maintainer for the repository using repository settings. This requires the owner to perform the change while they still control the account.
  - If the owner wants an arrangement that will take effect only after a defined period of inactivity, they should adopt an organizational approach (transfer the repository to an organization they control, then add other users as owners or maintainers) or use third-party estate-planning tools. GitHub Support cannot perform a conditional transfer based only on a timeout without verifying account control.

- Owner permanently unavailable (deceased or legally incapacitated):
  - In cases of death or legal incapacity, GitHub handles requests under the GitHub Deceased User Policy and may transfer repositories after receiving valid legal documentation and following their internal review process. Link: https://docs.github.com/en/site-policy/other-site-policies/github-deceased-user-policy
  - Explain the typical verification steps (proof of death, proof of authority such as executorship or power of attorney, or local legal process), and note that the process and available remedies depend on local law and GitHub's policy.

3. Add a link and short explanation to the "GitHub Deceased User Policy" and cross-reference the repository transfer docs. Clarify that the Deceased User Policy is the main pathway for transfers when the account owner is deceased, but that proactive measures (e.g., organization transfers, adding maintainers, or documented succession plans) are recommended for those who want a friendly, low-friction handover.

4. Add sample wording users can place in their account documentation or wills, e.g.:

"I authorize the holder of [email address or name] to request transfer or management access to my GitHub repositories in the event I become unable to access my account. I understand GitHub may require proof of authority before transferring repositories."

5. Add short FAQ entries:

Q: Can GitHub transfer my repositories to someone I nominate if I'm alive but unresponsive? A: No — GitHub requires verification that the requester controls the account or has legal authority. Proactive steps are recommended.

Q: What should I do now to make handover easier? A: Consider transferring critical repositories to an organization you control and add co-owners, set up documented executor contact details, and record access instructions securely (password manager, legal will, or estate plan).

Editorial notes

- Provide links to: repository transfer docs, the Deceased User Policy, and repository collaborator/organization docs.
- Keep language non-legalistic but clear about verification and potential legal documentation.
- Recommend that users consult local legal counsel or estate planners for binding instructions.

