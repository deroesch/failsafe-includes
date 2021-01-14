#  failsafe-01

I'm experimenting with profiles to control which tests are run in a session.

The best option is to ignore <includesFile> and uses profiles instead.  You could use <includesFile> but it's harder.  Plus, profiles offer more control over what included and excluded.

- To run everything, say `mvn verify`
- To run only the alpha tests, say `mvn verify -P alphaTests`
- To run only the beta  tests, say `mvn verify -P betaTests`
