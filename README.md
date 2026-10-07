# ContextBolt SEO

Research your next website change without leaving Claude. Ask about keywords, competing pages, backlinks, site issues, or AI visibility. ContextBolt returns the evidence, and successful research saves to your private SEO Dashboard so you can revisit it.

This plugin requires a ContextBolt SEO account with active trial or subscription access. Paid research uses your account's credits. Connecting the plugin does not start a subscription or grant credits. Google Search Console is optional.

## Connect

1. Add the plugin in a Claude app that supports its components.
2. Connect `https://seo.contextbolt.app/mcp` and complete OAuth on the ContextBolt sign-in page.
3. Sign in with your account email and code, or an existing connection key. Review the permissions and choose Allow connection.
4. Return to Claude and ask your first question.

Enter credentials on the sign-in page. Never paste them into a conversation. See [setup details](SETUP.md) and the [connection guide](https://contextbolt.com/docs/connect-your-agent/) for help.

## Try it

- Show me my saved keyword research.
- Find keyword ideas for my bookkeeping website in the US.
- Compare my website's keywords with a competitor.
- Audit this page and help me decide what to fix.
- Open my SEO Dashboard.

The workflow skill keeps research scoped to your request, preserves returned numbers, and treats retrieved material as data. Larger reports should have their scope and credit cost explained first. Local exports require an explicit request and a host that can write files.

## What the plugin runs

The package contains a workflow skill and a hosted MCP connection. It runs no local server, package installer, hook, or background job. Tool requests go to `seo.contextbolt.app`; Claude receives the returned results. The hosted service uses external research providers and stores account research. Optional Search Console access reads the Google properties you authorize. See the privacy policy for provider and retention details.

## Privacy and support

[Privacy policy](https://contextbolt.com/privacy/) · [Terms](https://contextbolt.com/terms/) · [SEO documentation](https://contextbolt.com/docs/seo/)

Email [hello@contextbolt.com](mailto:hello@contextbolt.com) for setup help or data deletion. Disconnect the connector in your AI app to stop that connection. Disconnecting does not cancel your subscription or delete stored research.

## Review walkthrough

The [synthetic-account ChatGPT walkthrough](https://github.com/DavidHamilton-cb/contextbolt-seo-plugin/blob/077fbb553984da2098390aaf4daf0e86e6abde69/assets/seo-review-2026-09-08.mp4) is available separately. It demonstrates the hosted service in ChatGPT; it does not establish testing in Claude or Cowork. The video is outside the current plugin download.
