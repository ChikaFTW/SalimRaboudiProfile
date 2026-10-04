# Salim Raboudi — personal portfolio

A static, responsive portfolio. No npm install or build step required.

## Preview in VS Code
Open this folder in VS Code, then use Live Server on `index.html`, or run:

```bash
python -m http.server 5500
```

Open http://localhost:5500. Do not launch the Python server from the parent folder.

## Copy into your existing GitHub Pages repository
1. Create a branch: `git switch -c portfolio-redesign`.
2. Copy `index.html`, `assets/`, `images/`, and this README into the repository root. Existing unrelated files may remain. The redesigned page does not use the old CSS, JavaScript, libraries or contact form.
3. Review locally on desktop and mobile. Gallery supports click, arrows, keyboard, swipe, Escape, and pause; motion respects device accessibility settings.
4. Commit and push the branch. Merge into your GitHub Pages publishing branch when ready.

All paths are relative for compatibility with `/SalimRaboudiProfile/` on GitHub Pages.

## Edit later
- Replace `images/portrait-v2.png` with your new portrait, keeping the filename. A transparent PNG works best with the circular background.
- Edit content and project details directly in `index.html`.
- Change colours in the variables at the start of `assets/style.css`.
- Gallery image order is in `assets/main.js` (`images` array). Update matching gallery buttons in `index.html` when adding or removing images. `assets/gallery.json` is a reference copy, not a runtime dependency.
- Replace `assets/Salim_RABOUDI_EN.pdf` and `assets/Salim_RABOUDI_FR.pdf` when your CVs change.

Content is based on the supplied current CV. The FinOps Certified Engineer is marked certified. Current learning reflects FinOps, AI, infrastructure and monitoring interests. Projects have expandable details without invented public demo links. Contact links open email/phone directly; there is no form requiring a backend.

## Version 2 updates
- Local SVG technology logos (Devicon and Simple Icons) in skills and project stacks; neutral diamond symbols denote concepts that have no product logo.
- Transparent hero portrait at `images/portrait-v2.png`, created from the supplied photo using the built-in image editing tool. Prompt: remove only the surroundings, preserve identity, white shirt, pose, bracelet, hands and arms; produce a clean transparent cutout.
- Prominent core-expertise cards, project outcome callouts, continuous-learning cards and language cards.
- Jobs Hunt links to https://jobs-hunt.com.
- Education title has no forced line break; it fits on one line on desktop and wraps naturally on smaller screens.
- Certificate previews open supplied documents. Verification links are transcribed from the certificates. AWS is correctly labeled Cloud Practitioner Essentials course completion, not an exam certification.
- Azure remains listed from the CV; its certificate preview has not been supplied.
- Jira and the planned FinOps Practitioner pathway have been removed from current learning copy.

## English and French CV downloads
Both supplied updated CVs are installed and downloadable:
- `assets/Salim_RABOUDI_EN.pdf` — English (`Salim_RABOUDI(1).pdf`).
- `assets/Salim_RABOUDI_FR.pdf` — French (`Salim_RABOUDI(2).pdf`).
Replace these files in place for future updates. Hero and contact buttons already point to their respective languages.
The supplied English PDF still mentions the planned FinOps Certified Practitioner pathway. It is retained unchanged pending a later CV correction.

## Asset attribution
Technology SVGs: Devicon (https://github.com/devicons/devicon), and Simple Icons (https://simpleicons.org). Logos remain the property of their respective owners. The generic symbols in this site represent engineering concepts rather than vendor marks.

## Validation
JavaScript syntax and local asset references checked. Chromium desktop/mobile checks cover project filtering, gallery arrow keys, Escape close, mobile navigation, original image count, image loading and horizontal overflow. Additional responsive widths and reduced-motion checks are recorded in `VALIDATION.md`.

## Version 3
OVHcloud appears after Azure in the expertise band and cloud toolkit, with matching icon dimensions. Helm and GitOps were added to the containers expertise card; GitOps also appears in the toolkit. GitOps is represented by the Git logo, as requested. GitOps is a workflow; this is the Git logo rather than a separate official GitOps mark. KVM appears once per project stack and uses an original CPU/virtualization icon distinct from the Linux logo. Both supplied PDFs are included without modifying their contents.

Git Logo by Jason Long: https://git-scm.com/community/logos — licensed under Creative Commons Attribution 3.0 Unported (https://creativecommons.org/licenses/by/3.0/).
