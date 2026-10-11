# echolines-site

Static site for EchoLines at https://echolines.thetonda.com: landing page, privacy policy and support, in English (`/`) and Simplified Chinese (`/zh/`). The privacy policy and support URLs are the ones listed in App Store Connect.

Plain HTML and one stylesheet, no build step. Deployed with Cloudflare Pages from `main` (build command: none, output directory: `/`); the custom domain `echolines.thetonda.com` is attached to the Pages project.

Keep the privacy policy in sync with what the app actually does (network requests, Wi-Fi Transfer, notifications) whenever the app changes.
