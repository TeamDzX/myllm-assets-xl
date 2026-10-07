# myllm-assets-xl

Large MyLLMos gallery apps, kept apart from [myllm-assets](https://github.com/TeamDzX/myllm-assets) so that repo stays under jsDelivr's 50 MB package limit.

The gallery manifest (`apps.json`) lives in myllm-assets. Its entries for these apps point here, pinned to a commit:

    https://cdn.jsdelivr.net/gh/TeamDzX/myllm-assets-xl@<commit>/apps-src/<slug>.html

Updating an app here:
1. Commit the new `.html` and `.myllmapp`.
2. Point the entry's `html`/`json` in myllm-assets/apps.json at the new commit.
3. Bump its `version`.

The pin workflow in myllm-assets only re-pins its own URLs, so step 2 is done by hand.

| App | Size |
|---|---|
| space-range | ~2 MB |

Same licence as myllm-assets (source-available, see LICENSE).
