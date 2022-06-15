# github-notifier

Policy For Branch Protection
Webhook Notifier to Discord

```
curl -X PUT -H "Accept: application/vnd.github.v3+json" -H "Authorization: token <token>" https://api.github.com/repos/digitalfastlane/template1234/branches/secure/protection -d '{"required_status_checks":{"strict":true,"contexts":["continuous-integration/travis-ci"]},"enforce_admins":true,"required_pull_request_reviews":{"dismissal_restrictions":{"users":["javathecup"],"teams":["devs"]},"dismiss_stale_reviews":true,"require_code_owner_reviews":true,"required_approving_review_count":2,"bypass_pull_request_allowances":{"users":["javathecup"],"teams":["devs"]},"restrictions":{"users":["javathecup"],"teams":["devs"]},"required_linear_history":true,"allow_force_pushes":true,"allow_deletions":true,"block_creations":true,"required_conversation_resolution":true}'
```

