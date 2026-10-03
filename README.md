# Shishu Breath

Independent fictional provider: Prana Child Health. Synthetic evaluation only.

Support a full-minute breathing count and document danger signs.

AI role: Speech-to-text for breathing observations; respiratory rate is manually counted, not inferred from video.

Run node build.mjs, then serve dist/server/wrangler.json with Wrangler. Sites provides private dispatch authentication, D1 and server-only PARTNER_KEY. Migrations are generated from db/schema.ts.

Browser models process recordings/images on-device. Corrected synthetic text and worker-confirmed observations are sent to the provider and retained as receipts. Signed receipts attest rule processing, not browser inference execution. Manual/sample evidence never claims AI inference. Browser speech/OCR evidence is explicitly client-reported. Uncertain results support lookup without re-inference. No clinical approval, prescribing or automatic patient update.
