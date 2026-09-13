# Manual actions required

Only actions that cannot be completed or independently verified through the connected repository tooling are listed here.

## 1. Verify GitHub hiring status

**Action:** Confirm **Available for hire** is enabled.

**Why manual:** The connected repository tooling does not expose or modify this account-level Jobs Profile setting.

**Steps:**
1. Sign in to GitHub.
2. Open your profile menu and select **Settings**.
3. Under **Jobs Profile**, select **Available for hire**.
4. Click **Save jobs profile**.

**Expected result:** Your GitHub account is explicitly marked as open to job opportunities.

**Verification:** Re-open the Jobs Profile settings and confirm **Available for hire** remains selected.

GitHub documentation: https://docs.github.com/en/account-and-profile/how-tos/account-settings/set-your-hiring-status

## 2. Curate pinned repositories

**Action:** Set the profile pins in this order:

1. `eskom-strategic-intelligence`
2. `analytics-release-gate`
3. `insurance-claims-intelligence-powerbi`
4. `banking-process-excellence-lean-six-sigma`
5. `motor-claims-triage`
6. `garethmackenzie.github.io`

**Why manual:** The connected repository tooling does not expose profile pin management.

**Steps:**
1. Open your GitHub profile.
2. In the **Pinned** section, select **Customize your pins**.
3. Select the six repositories above.
4. Drag them into the stated order.
5. Save the pins.

**Expected result:** A recruiter sees executive BI first, analytics engineering/tooling second, domain analytics third, then supporting projects.

**Verification:** Open the public profile in a signed-out/incognito browser and confirm the first three pinned repositories are Eskom Strategic Intelligence, Analytics Release Gate and Insurance Claims Intelligence.

GitHub documentation: https://docs.github.com/en/account-and-profile/how-tos/profile-customization/pinning-items-to-your-profile

## 3. Power BI Desktop rendering check for Insurance Claims Intelligence

**Action:** Complete the repository's Power BI Desktop verification checklist on a current Power BI Desktop host.

**Why manual:** Repository source and hosted CI can validate PBIP/PBIR/TMDL structure, but the connected tooling cannot launch Power BI Desktop or verify rendered interactions.

**Steps:**
1. Follow `docs/desktop-verification-checklist.md` in `insurance-claims-intelligence-powerbi`.
2. Open `InsuranceClaimsIntelligence.pbip` in a current Power BI Desktop release.
3. Set the documented project-root parameter.
4. Refresh the model.
5. Verify all eight report pages, interactions, labels and visuals.
6. Record the outcome only if the checklist completes successfully.

**Expected result:** The project renders and behaves as intended in Power BI Desktop.

**Verification:** Update the repository runtime evidence record only after completing the checklist.

## 4. Optional external credential verification

**Action:** Ensure each credential listed in the profile can be supported by a public verification URL or certificate on request.

**Why manual:** The connected GitHub repository data confirms the claims are present in the profile README, but it does not independently validate external certification records.

**Expected result:** Every credential in the public profile is defensible during recruiter verification.
