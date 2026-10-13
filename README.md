# Chuhaijiang

Chuhaijiang connects your agent to real-time TikTok Shop data, AI content generation, and social media operations for cross-border commerce.

This plugin connects the **Chuhaijiang MCP server** (remote, streamable HTTP). It provides 21 tools covering product, creator, video, shop, ad, livestream, and Amazon data; AI image, video, and script generation; AI Canvas and video editing; social account, publishing, comment, analytics, and direct-message management; TikTok Shop seller operations; account info and file upload.

## Setup

1. Install the plugin.
2. Open the MCP settings and connect the `chuhaijiang` server. Your browser opens the Chuhaijiang sign-in and consent page.
3. Sign in with your Chuhaijiang account and approve access. No API key is needed.

You need a Chuhaijiang account with available credits. Tool calls are billed against your account the same way as direct OpenAPI calls. Create an account or top up at <https://developer.chuhaijiang.com>.

### API key (fallback)

If your client cannot complete OAuth, add a custom remote MCP server instead:

- URL: `https://mcp.gateway.chuhaijiang.com/mcp`
- Header: `X-API-Key: <your sk_live_ key>`

Create a key at <https://developer.chuhaijiang.com/dashboard/apps>. Keep the key in your client's MCP settings and never paste it into a chat.

## Example prompts

- Assess the seven-day growth, competition, and market-entry opportunity for Leak Proof Design Mini Portable Juicer Blender (ID: 1731889645432705669) in the US
- Analyze sales, review pain points, creators, and similar competitors for 580ML Portable Juicer with LED Display (ID: 1732374678933836006)
- Find 10 mid-tier creators to contact for USB Rechargeable Portable Smoothies Blender & Juicer (ID: 1731172842143585192)
- Use viral videos for 580ML Portable Juicer with LED Display (ID: 1732374678933836006) to write a TikTok shoppable script for a similar portable blender
- Review the past seven days of my connected TikTok and Instagram accounts, then identify high-engagement comments and direct messages that need a reply

## Support

- Documentation: <https://developer.chuhaijiang.com/dashboard/mcp>
- Email: info@chuhaijiang.com

## License

MIT. See [LICENSE](LICENSE).
