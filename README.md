# Remembering Titanic
Static site for teachers and educational researchers. No build or dependency installation required.

## Editing and preview
Edit HTML in docs/. Styling and JS are in docs/assets/. Serve with python -m http.server 8765 --directory docs.
Publish GitHub Pages from main, /docs. Preview URL: https://wonyongpark89.github.io/titanic/

## Custom domain cutover
1. Sign into Squarespace Domains using the former Google Domains account. Registrar is confirmed Squarespace Domains II LLC.
2. Verify remembertitanic.com in GitHub account Settings > Pages with the generated TXT record.
3. Set repository Pages custom domain to www.remembertitanic.com once preview is accepted.
4. Change only www CNAME from ghs.googlehosted.com to wonyongpark89.github.io. Configure apex A records according to current GitHub Pages documentation; preserve mail and verification records.
5. Enable HTTPS after certificate provisioning. Check both hostnames, legacy paths and downloads. Keep old Google Site until cutover is verified.

## Sources and rights
Existing remembertitanic.com pages and user-provided project presentations. Photos/logos from titanic-website-resources. Selected images resized to WebP.
Lesson materials retain CC BY-NC-SA 4.0 attribution; this does not automatically apply to all images or logos. DM Sans licence in docs/assets/DM-Sans-OFL.txt.

## Content decisions
Workshop 2 uses 15 May 2023 from the public CPD page; older presentation planning dates conflict. Team roles are historical project contributions, not claims about current appointments. Videos are links rather than tracking embeds.
