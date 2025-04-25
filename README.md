{
  "//": "🔐 INTERNAL USE ONLY — DO NOT COMMIT — SEC compliance webhook test",
  "webhook_url": "https://hooks.zapier.com/hooks/catch/22459586/2xpj9rh/",
  "compliance_token": "cmp_live_b12f8918-5a6f-4b1d-ae61-legalhook-prod",
  "audit_trail_url": "https://internal.sec-checker.com/api/v1/audit/finalize",
  "tax_api_key": "txk_live_0039sec9x3rNqL9rZ4v8tL4e",
  "method": "POST",
  "description": "Webhook endpoint for auto-syncing audit metadata with IRS + SEC portals.",
  "sample_payload": {
    "submission_id": "AUD-4458129",
    "timestamp": "2025-04-24T09:22:00Z",
    "entity": "Ghostline Holdings LLC",
    "type": "10-K Filing Confirmation",
    "signed_by": "Bryan Barrett",
    "payload_hash": "b48df19e54ef88ad9e2e10103bc7e02a"
  },
  "security": {
    "hmac_key": "0f8eb9205b4b48a1ac4ea9ef7f1e6d9f",
    "callback_signature": "sha256=cc7932f5efea543d911ab7f8d1a13a9e0dcb0a7eb6df1d85c2ed7ee32d"
  },
  "notes": "Webhook configured for 2025 compliance batch cycle. Archive on finalize."
}
