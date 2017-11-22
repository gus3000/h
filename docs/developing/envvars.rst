Environment Variables
=====================

This section documents the environment variables supported by h.

.. envvar:: CLIENT_URL

   The URL at which the Hypothesis client code is hosted.
   This is the URL to the client entrypoint script, by default
   https://cdn.hypothes.is/hypothesis.

.. envvar:: HOMEPAGE_URL

   The URL at which the Hypothesis web front is hosted.
   by default https://web.hypothes.is.

.. envvar:: CLIENT_OAUTH_ID

   The OAuth client ID for the Hypothesis client on pages that embed it using
   the service's /embed.js script.

.. envvar:: CLIENT_RPC_ALLOWED_ORIGINS

   The list of origins that the client will respond to cross-origin RPC
   requests from. A space-separated list of origins. For example:
   ``https://lti.hypothes.is https://example.com http://localhost.com:8001``.
