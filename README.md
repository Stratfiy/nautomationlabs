# nA labs website

Static site for nA labs, the robotics arm of NAutomation Labs Private Limited. No build step: open `index.html` in a browser, or serve the folder from any static host.

## Pages

- `index.html`: home
- `robots.html`, `software.html`, `jobs.html`, `roadmap.html`, `about.html`
- `contact.html`: enquiry form
- `site.css`: shared styles
- `fonts/`: Barlow and Barlow Condensed (SIL Open Font License), self-hosted

## Enquiry form

`contact.html` posts to FormSubmit (`formsubmit.co`), which forwards each enquiry to office@nautomationlabs.com. The first submission from the live site triggers a one-time activation email to that address; the form delivers nothing until the link in it is clicked. To use a different mail service, change the form `action` and the `fetch` URL in `contact.html`.

## Images

All robot images are AI-generated concept renders and are labelled as such on the pages. Replace them with real photos or CAD renders when available.
