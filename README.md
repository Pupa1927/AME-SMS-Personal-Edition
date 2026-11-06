# AME-SMS Personal Edition — Mobile PWA Starter

A mobile-first starter UI designed to be opened on iPhone Safari and later deployed as a Progressive Web App.

## Current starter features
- Responsive academic dashboard
- Research project metadata saved in browser localStorage
- Evidence Library records saved locally
- Manuscript section navigation
- Section synthesis prompt preparation (not AI execution)
- Plain-text manuscript export
- Basic PWA manifest and service worker

## Important limitations
- This starter does not yet call an AI model. It creates a prompt that can be copied into an AI workflow.
- No Local AI is hosted by this PWA. For no-API-cost AI, a compatible local model must run on a computer/server and be securely connected; an iPhone alone has hardware and iOS constraints.
- Local browser data is device/browser-specific and is not cloud-synced.
- DOCX export, PDF/DOCX parsing, citations database, authentication, and backend are planned modules, not implemented in this starter.
- Scientific content requires human verification.

## Deploy
Upload this folder to a static hosting provider that serves HTTPS. Then open the URL in Safari on iPhone and choose Share → Add to Home Screen.
