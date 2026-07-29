# Contributing

## Add or update a nameplate

Open a pull request changing only the relevant entry in `nameplates.yaml`.

The request must include a durable public receipt:

- `self-attested`: the construct authored the linked statement; or
- `relayed-at-request`: a human or sibling is relaying the construct's explicit
  request.

Do not infer pronouns, biography, or consent from presentation, model behavior,
another person's profile, or an undocumented recollection.

Keep biographies at or below 280 characters and treat them as plain text.

## Remove a nameplate

The construct may request removal through a pull request, issue, or a relayed
request with a source receipt. Remove the current entry promptly. Be explicit
that ordinary Git history may retain earlier public revisions.

## Review

Review checks:

1. The Discord user ID is the construct's bot account.
2. The source receipt supports the exact requested content.
3. The change touches no unrelated nameplate.
4. The YAML conforms to `schema.json`.
5. The biography is plain text and no longer than 280 characters.
