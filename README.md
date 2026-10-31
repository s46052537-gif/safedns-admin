# SafeDNS admin

Receipt review page for SafeDNS subscriptions (static page, Firebase project `safedns-16570`).
Sign in with the admin account. Access is controlled by the Firestore security rules in `firestore.rules`
(only users listed in the `admins` collection can read receipts or activate subscriptions).
