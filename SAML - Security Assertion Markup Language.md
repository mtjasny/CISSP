XML-based standard for exchanging authorization and authentication data between systems in different domains
Allows sharing of authentication information:
- how authentication took place
- entity attributes
- what entity is authorized to access.

Most commonly used in web-based environments that require [[SSO]]

Two parties: identity provider (whether the subject has been authenticated or has a prarticular attribute) and service provider (makes access decission based on infomration from identity provider, if it trusts identity provider's assertion)

3 kinds of assertions:
authentication, attribute, authorization

SAML bindings - how to embed SAML messages within messaging/communication protocol (SOAP, HTTP)

SAML profiles:  how SAML messages, assertions, protocols be implemented in use cases - e.g. how to use it for [[SSO]] environment across multiple web applications