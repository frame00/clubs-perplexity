# CLUBS for Perplexity

The plugin Perplexity imports to connect [CLUBS](https://clubs.place).
CLUBS keeps your team's decisions by project. After working with AI, say "save this to CLUBS", and pick up where you left off — another day, or with another AI.

The repository root holds `plugin.json` and `mcp.json`. There is no API key in the package; you sign in with your own CLUBS account.

## Import

1. In Perplexity Computer, open **Plugins**, choose **Add custom**, then **Import plugin from GitHub**, and paste:

   https://github.com/frame00/clubs-perplexity

2. Open the plugin and choose **Connect**, then sign in to CLUBS and allow the connection.
3. In a new thread, turn on `clubs` under Connectors and try: "Sum up my work from the past 7 days and save it to CLUBS".

Connect CLUBS only once. If `clubs` appears twice under Connectors, remove one.

## Updates

Perplexity copies the repository when you import it. To update, open the plugin, choose **More actions → Replace file**, and upload a zip of `plugin.json` and `mcp.json` (both at the zip's root). Or delete the plugin and import the URL again.

The server type is `streamable-http` and the URL is `https://clubs.place/api/mcp`.

---

## 日本語

Perplexity で [CLUBS](https://clubs.place) を使うためのプラグインです。

1. Perplexity の Computer で **Plugins → Add custom → Import plugin from GitHub** を選び、次の URL を貼ります。

   https://github.com/frame00/clubs-perplexity

2. プラグインを開いて **Connect** を押し、CLUBS にログインして接続を許可します。
3. 新しい会話でコネクタの `clubs` をオンにし、「この1週間の仕事を、CLUBS にまとめて」と頼んでみてください。

CLUBS の接続は1つだけにしてください（コネクタに `clubs` が2つあるときは、1つを外す）。

お問い合わせ：contact@frame00.com
