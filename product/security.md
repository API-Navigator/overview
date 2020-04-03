# [CAM](../) [Product Compass](./): Security

With APIs having the goal of opening up capabilities for access and interaction, it is clear that securing them is important, as APIs by definition create a new attack surface. However, the good news is that with connectivity always being managed through APIs (and not through one-off integration projects that are harder to secure and track consistently), security can focus on APIs as the uniform method of interaction. At the API level, security means to protect your capabilities from unauthorized access, to make sure that they stay available for authorized access, and to make sure that capabilities are designed and implemented in ways that fit well into your security model.

* What are the identity and access management support and tools that you have currently available?

* The API product controls basic technical security issues (identities, authenticate clients and end users, authorize usage, and implement rate limits, ...) either itself or by using libraries or tooling.

* Documentation and design expose as little information about implementation details as possible to reduce the attack surface.

* The API exposes as little information as possible to reduce the risk of information leakage.

* Do you know the relevant legislation and regulation that applies to your API product?

* Data management by the API product has been reviewed and verified to comply with the applicable regulations.

* The API supports necessary support functions to comply with known regulations (such as GDPR) around security and privacy.

* Security considerations are part of the deployment considerations, so that for example geographic locations are taken into account.

* Do you protect against the top ten OWASP API attacks?
