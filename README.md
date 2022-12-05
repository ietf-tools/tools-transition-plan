# Transition from tools.ietf.org

We announced on March 2021, that tools.ietf.org would be wound down. [See the announcement here.](https://mailarchive.ietf.org/arch/msg/ietf/0n-6EXEmkTp3Uv_vj-5Vnm3o0bo/) That effort is now complete.

This page documents the changes in the transition, and will provide help for others migrating to the new locations of various services. It also captures what was explicitly not transitioned, and will track the few services that we plan to transition but have deferred.

Anything not discussed on this page was not included in the transition. If you had been using something at tools.ietf.org and haven't found a replacement for it, let the tools team know. The best way now is to open an issue on this repository. A message to tools-discuss will also work.

## New service locations


| Previous Service | Old Location | New Location | Notes |
| -----------------|--------------|--------------|-------|
| htmlized RFCs | https://tools.ietf.org/html/rfcnnnn | https://www.rfc-editor.org/rfc/rfcnnn.html| Preserves #section-n.n anchors |
| htmlized drafts | https://tools.ietf.org/html/draft-some-name | https://datatracker.ietf.org/doc/html/draft-some-name ||
| pdfed-htmlized-drafts | https://tools.ietf.org/pdf/draft-some-name | https://datatracker.ietf.org/doc/pdf/draft-some-name ||
| plain text of draft | https://tools.ietf.org/id/draft-some-name-with-version | https://datatracker.ietf.org/doc/id/draft-some-name ||
| group pages | https://tools.ietf.org/wg/acronym | https://datatracker.ietf.org/group/acronym ||
| meeting agendas | https://tools.ietf.org/agenda/nnn/ | https://datatracker.ietf.org/meeting/nnn/agenda ||
| schedule builder | https://tools.ietf.org/agenda/nnn/calendar | https://datatracker.ietf.org/meeting/nnn/agenda/personalize ||
| bibxml | https://xml2rfc.tools.ietf.org/public/rfc/bibxml-ids/reference.I-D.example-name.xml | https://bib.ietf.org ||
| online conversion | https://xml2rfc.tools.ietf.org or https://xml2rfc.tools.ietf.org/experimental.html | https://author-tools.ietf.org ||
| idnits | https://tools.ietf.org/tools/idnits/ | https://author-tools.ietf.org/idnits | |
| rfcdiff | https://tools.ietf.org/rfcdiff | https://author-tools.ietf.org/iddiff ||
| dailydose | https://tools.ietf.org/dailydose/ | TBD ||
| front page | https://tools.ietf.org | https://authors.ietf.org | New documentation site for authors |
| vocabulary reference | https://xml2rfc.tools.ietf.org/xml2rfc-doc.html | https://authors.ietf.org ||
| XML templates | https://tools.ietf.org/tools/templates/ | https://authors.ietf.org ||
| BAP (ABNF tools) | https://tools.ietf.org/tools/bap | https://author-tools.ietf.org/abnf | |
| svgcheck | https://xml2rfc.tools.ietf.org/experimental.html#svg12checker | https://author-tools.ietf.org/svgcheck | |

## Work remaining
- [ ] Replacing dailydose 

## Services we are not planning to replace
| Previous Service | Old Location | Notes |
| ---------------- | ------------ | ----- |
| citation | https://tools.ietf.org/tools/citation |see [#5](https://github.com/ietf-tools/tools-transition-plan/issues/5)|
| doublespace | https://tools.ietf.org/tools/doublespace/ ||
| idspell | https://tools.ietf.org/tools/idspell/webservice ||
| rfcmarkup | https://tools.ietf.org/tools/rfcmarkup/ | Consider https://github.com/ietf-tools/rfc2html |
| loginmgr | https://tools.ietf.org/tools/loginmgr/newlogin | New services will authenticate via Datatracker if required |
| idcomments | https://tools.ietf.org/tools/idcomments/ ||
