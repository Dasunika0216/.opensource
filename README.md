<div align="center">

<img src="https://github.com/Dasunika0216.png" width="150" height="150" alt="Dulmini Munasinghe" style="border-radius: 50%; border: 3px solid #0969da;"/>

# Dulmini Munasinghe

**Open Source Contributor**

Undergraduate | Department of Computer Science and Engineering | University of Moratuwa

[GitHub](https://github.com/Dasunika0216) • [Web Portfolio](https://Dasunika0216.github.io/.opensource/)

---

### Portfolio Summary

</div>

<table align="center">
  <tr>
    <td align="center" width="200" style="padding: 20px;">
      <h2 style="margin: 0; font-size: 2.5em;">5</h2>
      <p style="margin: 5px 0 0 0; font-weight: 600;">Contributions</p>
    </td>
    <td align="center" width="200" style="padding: 20px;">
      <h2 style="margin: 0; font-size: 2.5em;">1</h2>
      <p style="margin: 5px 0 0 0; font-weight: 600;">Projects</p>
    </td>
    <td align="center" width="200" style="padding: 20px;">
      <h2 style="margin: 0; font-size: 2.5em;">1</h2>
      <p style="margin: 5px 0 0 0; font-weight: 600;">Languages</p>
    </td>
  </tr>
</table>

<br/>

---

## Contributions by Project


### <img src="https://github.com/asyncapi.png" width="28" height="28" align="absmiddle" alt="asyncapi"> [asyncapi/website](https://github.com/asyncapi/website)

AsyncAPI specification website

**5 contributions** • TypeScript • **★ 706**

---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [add filter to invert documentation diagrams in dark mode](https://github.com/asyncapi/website/pull/5527) <sub>[#5527](https://github.com/asyncapi/website/pull/5527)</sub>

<sub><strong>Merged</strong> on May 31, 2026</sub>

- **Changes:** <code>+7</code> <code>-0</code> across 1 file
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

refs - https://github.com/asyncapi/website/issues/5465#issuecomment-4586415133

**Description:**

- Added CSS rules in `styles/globals.css` to invert the colors of diagram images (SNS-SQS-Pub-Sub.png, SNS-HTTP.png, SQS-Point-To-Point.png) when the website is in dark mode in `/docs/reference/bindings/3.0.0` and `/docs/reference/bindings/2.x.x`.

**Steps to Reproduce:**

1. Navigate to the SNS bindings reference page at `/docs/reference/bindings/3.0.0` or `/docs/reference/bindings/2.x.x`.
2. Toggle the website theme to dark mode.
3. Scroll down to the "SNS to SQS Pub-Sub" or "SNS to HTTP Pub Sub" or "" example sections.
4. Notice that the architecture diagram images now display with white text labels that are clearly readable against the dark background.

**Screenshots:**

| Before | After |
|--------|--------|
| <img width="600" alt="SNS diagram before 1" src="https://github.com/user-attachments/assets/ef73bdf1-4465-4fc9-b6aa-101064def1ec" /> | <img width="600" alt="SNS diagram after 1" src="https://github.com/user-attachments/assets/367c2845-fc0c-494c-a7f3-03d9c5e9dcaa" /> |
| <img width="600" alt="SNS diagram before 2" src="https://github.com/user-attachments/assets/7dcb56e3-eece-44a0-b447-487ac56c70c7" /> | <img width="600" alt="SNS diagram after 2" src="https://github.com/user-attachments/assets/8563e064-c817-4614-a3ac-6a70fa85d47b" /> |
| <img width="600" alt="SNS diagram before 3" src="https://github.com/user-attachments/assets/ca8aaca8-edbb-4430-892e-84e62bf56876" /> | <img width="600" alt="SNS diagram after 3" src="https://github.com/user-attachments/assets/08382ca9-6c21-4f15-a276-75e06b953cce" /> |
| <img width="600" alt="SNS diagram before 4" src="https://github.com/user-attachments/assets/b458f50a-7834-4a9f-91f2-ef15f7112610" /> | <img width="600" alt="SNS diagram after 4" src="https://github.com/user-attachments/assets/53aa568f-ab4e-4c57-ab2e-859fd3c49279" /> |

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [improve dashboard tooltip and filter responsiveness](https://github.com/asyncapi/website/pull/5519) <sub>[#5519](https://github.com/asyncapi/website/pull/5519)</sub>

<sub><strong>Merged</strong> on May 29, 2026</sub>

- **Changes:** <code>+9</code> <code>-10</code> across 2 files
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

ref - https://github.com/asyncapi/website/pull/5253#issuecomment-4567873219

### **Description:**

- Fixed the "Is this your first contribution?" tooltip in `GoodFirstIssuesTip` displaying issue and fixed overflowing and clipping off-screen on mobile viewports.
- Added `w-[calc(100vw-2rem)]` to the tooltip card to ensure it never exceeds the available screen width, providing a safe margin on each side for narrow devices.
- Fixed the "Filter Issues" section in `Filters` overflowing on smaller screen sizes.
- Improved the filter icon's dark mode appearance.

### **Steps to Reproduce:**

1. Navigate to the `/community/dashboard` page.
2. Hover over the **"?"** question mark icon next to the "Good First Issues" heading.
3. Observe that the "Is this your first contribution?" card now displays properly.
4. Resize the browser to a mobile viewport or use DevTools device emulation.
5. Hover over the **"?"** question mark icon again.
6. Observe that the "Is this your first contribution?" card now stays fully within the viewport instead of clipping off the left edge.
7. Click the **filter icon** on the right side of the "Good First Issues" heading.
8. Observe that the "Filter Issues" section now appears correctly within the viewport on mobile without overflowing.
9. Toggle to **dark mode** and repeat steps 2-8 to verify both cards render correctly in both themes.

### **Screenshots:**

**Good First Issues Tooltip (Desktop)**

| Before | After |
|--------|--------|
| <img width="420" alt="Tooltip Before Desktop Light" src="https://github.com/user-attachments/assets/567b0445-ba12-413a-89bf-b7da46eb39de" /> | <img width="420" alt="Tooltip After Desktop Light" src="https://github.com/user-attachments/assets/f5dd9f52-4bd8-496a-82d9-cfa37cd0aa28" /> |
| <img width="420" alt="Tooltip Before Desktop Dark" src="https://github.com/user-attachments/assets/5abacfa7-d3db-4d6b-8f0d-c8d511d01478" /> | <img width="420" alt="Tooltip After Desktop Dark" src="https://github.com/user-attachments/assets/b7b1410b-df85-40f5-8ed8-35c70de1bd68" /> |

**Good First Issues Tooltip (Mobile)**

| Before | After |
|--------|--------|
| <img width="260" alt="Tooltip Before Mobile Light" src="https://github.com/user-attachments/assets/532c3873-33a9-4240-ae60-c35749b43860" /> | <img width="260" alt="Tooltip After Mobile Light" src="https://github.com/user-attachments/assets/8a5ec092-1794-4f80-838d-087f5a5f696b" /> |
| <img width="260" alt="Tooltip Before Mobile Dark" src="https://github.com/user-attachments/assets/7efd6c11-3e98-4848-b925-afb980c089a0" /> | <img width="260" alt="Tooltip After Mobile Dark" src="https://github.com/user-attachments/assets/0bf4359f-daf6-49df-b149-55f8abdb2dd4" /> |

**Filter Issues Section (Mobile)**

| Before | After |
|--------|--------|
| <img width="260" alt="Filter Before Mobile Light" src="https://github.com/user-attachments/assets/10000951-4380-48d4-ab71-e441a200f5f8" /> | <img width="260" alt="Filter After Mobile Light" src="https://github.com/user-attachments/assets/a7c2f8e1-8768-43f7-bf3e-d930a295f315" /> |
| <img width="260" alt="Filter Before Mobile Dark" src="https://github.com/user-attachments/assets/4298dad7-8275-4119-a04a-e31d9f3ea818" /> | <img width="260" alt="Filter After Mobile Dark" src="https://github.com/user-attachments/assets/8294255b-9f23-49e3-921d-c07ca75fe280" /> |



## Summary by CodeRabbit

* **Bug Fixes**
  * Improved tooltip positioning to better handle viewport boundaries and responsive layouts
  * Enhanced filter menu positioning behavior for improved screen adaptation

* **Style**
  * Refined filter button icon styling and visibility



[![Review Change Stack](https://storage.googleapis.com/coderabbit_public_assets/review-stack-in-coderabbit-ui.svg)](https://app.coderabbit.ai/change-stack/asyncapi/website/pull/5519?utm_source=github_walkthrough&utm_medium=github&utm_campaign=change_stack)

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [remove unwanted white background from FlyoutMenu component](https://github.com/asyncapi/website/pull/5511) <sub>[#5511](https://github.com/asyncapi/website/pull/5511)</sub>

<sub><strong>Merged</strong> on May 29, 2026</sub>

- **Changes:** <code>+1</code> <code>-1</code> across 1 file
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

ref - https://github.com/asyncapi/website/pull/5253#issuecomment-4567131374

**Description:**

- Removed the `bg-white` utility class from the outermost wrapper `<div>` of the `FlyoutMenu` component.
- Fixed a visual issue where a white rectangular block awkwardly appeared above the dropdown menu content.

**Steps to Reproduce:**

1. Open the website and locate the main navigation bar.
2. Open a dropdown menu that uses the flyout component (e.g., click/hover on the "Tools" option).
3. Observe the space just above the opened dropdown container.
4. Notice that there is no longer a white block sitting on top of the menu; the gap is now perfectly transparent.
5. Toggle between light and dark themes to verify the gap properly remains transparent in both modes.

**Screenshots:**

| Before | After |
|--------|--------|
| <img width="450" alt="Before Light" src="https://github.com/user-attachments/assets/36055874-55c9-49a6-8e71-d43ab673c4c5" /> | <img width="450" alt="After Light" src="https://github.com/user-attachments/assets/d667c643-f070-4f45-8920-1daae6ce78a7" /> |
| <img width="450" alt="Before Dark" src="https://github.com/user-attachments/assets/ecea4b99-805c-4126-84a8-c3bde8dd6858" /> | <img width="450" alt="After Dark" src="https://github.com/user-attachments/assets/a372d7ce-4fec-4d1c-aece-9a2eddbaacd3" /> |

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [add dark mode text to FAQ list and About title.](https://github.com/asyncapi/website/pull/5498) <sub>[#5498](https://github.com/asyncapi/website/pull/5498)</sub>

<sub><strong>Merged</strong> on May 27, 2026</sub>

- **Changes:** <code>+4</code> <code>-4</code> across 2 files
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

refs: https://github.com/asyncapi/website/pull/5253#issuecomment-4556441703

**Description:**

- Added the `dark:invert` utility class to the main heading inside the `GenericPostLayout` component to ensure generic page titles adapt correctly to dark mode.
- Added the `dark:text-white` utility class to the `FAQList` component.

**Steps to Reproduce (FAQ List):**

1. Scroll down to the bottom of the `/about` page.
2. Ensure the website theme is toggled to dark mode.
3. Expand the "Where can I find more information?" question.
4. Notice that the bulleted text and the embedded links (e.g., "Official AsyncAPI Documentation") are now correctly styled in white and easily readable.

| Before | After |
|--------|--------|
| <img width="400" alt="Before FAQ" src="https://github.com/user-attachments/assets/65aa1208-5361-4089-8067-6821ae93d5c8" /> | <img width="400" alt="After FAQ" src="https://github.com/user-attachments/assets/2ba9b3d4-8b25-4f6e-80a5-cc5489de80f4" /> |
| <img width="400" alt="Before FAQ Dark" src="https://github.com/user-attachments/assets/5834ee87-973d-41ea-8aa9-de2fd6bd51dd" /> | <img width="400" alt="After FAQ Dark" src="https://github.com/user-attachments/assets/d040dcdf-fc36-4aaf-b6ae-213d44df6825" /> |

**Steps to Reproduce ('About' Screen title):**

1. Navigate to `/about` page that uses the `GenericPostLayout`.
2. Toggle the website theme to dark mode.
3. Notice that the main page title ("About") now properly inverts its color to remain readable against the dark background.

**Screenshots**

| Before | After |
|--------|--------|
| <img width="400" alt="Before Light" src="https://github.com/user-attachments/assets/68ea6e69-66c7-4c46-b43b-315c10081477" /> | <img width="400" alt="After Light" src="https://github.com/user-attachments/assets/d5b3c682-f9a2-4cdd-9b57-0543d668ad8d" /> |
| <img width="400" alt="Before Dark" src="https://github.com/user-attachments/assets/a08248d1-7751-4a92-86b6-830e2c8bf903" /> | <img width="400" alt="After Dark" src="https://github.com/user-attachments/assets/5d270ffe-3cd9-437a-8e3a-fbf6d018a7da" /> |

Related issue(s)
Fixes: https://github.com/asyncapi/website/pull/5253#issuecomment-4556441703




## Summary by CodeRabbit

* **Style**
  * Enhanced dark mode styling for FAQ answers section with consistent text color treatment across all link elements, list items, and content areas for improved visual contrast and readability
  * Refined dark mode styling for post layout section headings with enhanced visual appearance and presentation to ensure improved readability and consistent look in dark theme mode



[![Review Change Stack](https://storage.googleapis.com/coderabbit_public_assets/review-stack-in-coderabbit-ui.svg)](https://app.coderabbit.ai/change-stack/asyncapi/website/pull/5498?utm_source=github_walkthrough&utm_medium=github&utm_campaign=change_stack)

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [invert question mark avatar in dark mode for CommunityLayout](https://github.com/asyncapi/website/pull/5487) <sub>[#5487](https://github.com/asyncapi/website/pull/5487)</sub>

<sub><strong>Merged</strong> on May 26, 2026</sub>

- **Changes:** <code>+1</code> <code>-1</code> across 1 file
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

refs: https://github.com/asyncapi/website/pull/5253#issuecomment-4540786056

**Description:**

- Added the `dark:invert` utility class to the Question Mark avatar image (`/img/avatars/questionmark.webp`) inside the `QuestionCard` component.
- Fixed a visual issue where the question mark avatar was poorly visible in dark mode because its default colors blended in with the dark card background.

**Steps to Reproduce**

1. Navigate to a community page that uses the `CommunityLayout` (/community/board`).
2. Toggle the website theme to dark mode.
3. Scroll down to the bottom of the members list to the "Want to become a member?" question card.
4. Notice that the question mark avatar is now properly inverted and readable against the dark background.

**Screenshots**

**Before:**
<img width="381" height="291" alt="Screenshot 2026-05-26 at 11 35 34" src="https://github.com/user-attachments/assets/f7180cd4-e700-4200-b366-d255406789f5" />

**After:**
<img width="372" height="285" alt="Screenshot 2026-05-26 at 11 36 12" src="https://github.com/user-attachments/assets/e63301ad-51dd-4584-b2a7-b06219dedbf4" />

**Related issue(s)**
Fixes: https://github.com/asyncapi/website/pull/5253#issuecomment-4540786056

</details>



---



---

<div align="center">

<sub>Last updated: June 23, 2026</sub>

<br/>

<sub>Generated by <a href="https://github.com/opensource-showcase/opensource-showcase">opensource-showcase</a> • View raw data: <a href="contributions.json">contributions.json</a></sub>

</div>
