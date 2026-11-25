# Whenever

Build and manage [Whenever](https://www.whenever.dev) automations from Antigravity. Describe a
recurring task and the Antigravity agent writes the workflow, checks it, and saves a draft in your
Whenever account. It can also turn workflows on, show their triggers, and read the results of past
runs. It runs a workflow by hand only when you ask.

## Install

With the [Antigravity CLI](https://antigravity.google/docs/install?tab=cli):

```
agy plugin install https://github.com/wix-incubator/whenever-antigravity-plugin
```

The plugin then shows up in the Antigravity App, CLI, and IDE. To try a local checkout instead,
run `agy plugin install ./whenever-antigravity-plugin`.

## Sign in

The plugin connects to `https://mcp.whenever.dev/` and signs in with your Whenever account. In the
Antigravity CLI, open `/plugin`, expand **whenever** under **Installed**, and choose **Sign in**. In
the Antigravity App, open **Customizations > Installed** and choose **Authenticate** next to the
Whenever MCP server. Antigravity sees only your own workflows. Provider connections and secrets are
set up in Whenever in your browser; Antigravity never sees their values.

## Support

Email `support` at `whenever.dev` (spelled out to keep the address away from spam crawlers).

## Privacy

[Whenever privacy policy](https://www.whenever.dev/privacy).
