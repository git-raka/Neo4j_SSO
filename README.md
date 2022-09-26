# Neo4j_SSO

### Neo4j supports OpenID Connect (OIDC)
```
dbms.security.authentication_providers=oidc-google
dbms.security.authorization_providers=native
dbms.security.oidc.google.display_name=Google
dbms.security.oidc.google.auth_flow=pkce
dbms.security.oidc.google.well_known_discovery_uri=https://accounts.google.com/.well-known/openid-configuration
dbms.security.oidc.google.audience=104995753265-c2s5iluk6ifc8g4pv1s0gda1uhjitcel.apps.googleusercontent.com
dbms.security.oidc.google.claims.username=email
dbms.security.oidc.google.params=client_id=104995753265-c2s5iluk6ifc8g4pv1s0gda1uhjitcel.apps.googleusercontent.com;response_type=code;scope=openid profile email
dbms.security.oidc.google.token_params=client_secret=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
dbms.security.oidc.google.config=token_type_principal=id_token;token_type_authentication=id_token
```
