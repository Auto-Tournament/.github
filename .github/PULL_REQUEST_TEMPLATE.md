## What does this change?

<!-- A short description of the change and why it's needed. -->

## AI disclosure

AI assistance is allowed anywhere in Auto Tournament, as long as it's disclosed. Some areas are
read line by line before anything merges:

- Sign-in and identity: `api/src/routes/auth.ts`, `api/src/middleware/auth.ts`,
  `api/src/middleware/serverAuth.ts`, `api/src/services/authIdentityService.ts`,
  `api/src/config/authProviders.ts`
- Module signing and installation: `api/src/modules/` (signature, trustedKeys, archive,
  catalogService)
- Game-server control: `api/src/integrations/cs2/routes/rcon.ts`,
  `api/src/integrations/cs2/services/rconService.ts`, `api/src/integrations/cs2/matchConfig.ts`

Full details: https://docs.autotournament.gg/developer/contributing

- [ ] This PR contains AI-assisted code
- [ ] This PR touches a review-required path (expect a slower, closer review)

## Checklist

- [ ] `yarn lint` passes
- [ ] Typecheck ratchet passes (`node scripts/typecheck-ratchet.mjs`)
- [ ] Tests pass
- [ ] Documentation is updated if needed
- [ ] No breaking changes (or clearly marked)
- [ ] CLA signed (first PR only)
