# Whyfern model catalog

Public model curation, fallback catalogs and harness-version compatibility metadata for Whyfern. Model discovery remains owned by the individual harness: Codex supplies its account-visible models; OpenCode supplies connected providers and their models. This repository contains no account inventories or credentials.

Installed Whyfern apps refresh the version-1 JSON manifest with a one-hour freshness interval, validated disk cache and bundled offline fallback. Unknown discovered models remain visible; only explicit legacy metadata places them in the legacy category. Remote recommendations never change saved learner selections. Actual model access depends on the connected account and harness.

The application maintains the canonical bundled JSON. Publication copies the reviewed file here byte-for-byte. Compatibility and fallback metadata for deferred adapters does not mean those adapters are enabled or verified for learning.

The manifest was adapted from T3 Code's model manifest. The upstream MIT license and copyright notice are retained in LICENSE.
