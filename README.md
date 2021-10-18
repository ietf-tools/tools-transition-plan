# Transition from tools.ietf.org

As announced March 2021, tools.ietf.org is being wound down. [See the announcement here.](https://mailarchive.ietf.org/arch/msg/ietf/0n-6EXEmkTp3Uv_vj-5Vnm3o0bo/)

This page is tracking the current plan to finalize the transition, and will provide help for others migrating to the new locations of various services.

Work is currently underway to replace the BibXML services from xml2rfc.tools.ietf.org, and the online document validation/conversion services.

## New service locations

As replacement services have been put in place, tools.ietf.org has been configured to redirect to them. After it is wound down, a redirect service will remain in place.

| Previous Service | Old Location | New Location | Notes |
| -----------------|--------------|--------------|-------|
| htmlized RFCs | https://tools.ietf.org/html/rfcnnnn | https://www.rfc-editor.org/rfc/rfcnnn.html| Preserves #section-n.n anchors |
| htmlized drafts | https://tools.ietf.org/html/draft-some-name | https://datatracker.ietf.org/doc/html/draft-some-name ||
| pdfed-htmlized-drafts | https://tools.ietf.org/pdf/draft-some-name | TBD ||
| group pages | https://tools.ietf.org/wg/acronym | https://datatracker.ietf.org/group/acronym ||
| meeting agendas | https://tools.ietf.org/agenda/nnn/ | https://datatracker.ietf.org/meeting/nnn/agenda ||
| schedule builder | https://tools.ietf.org/agenda/nnn/calendar | https://datatracker.ietf.org/meeting/nnn/agenda/personalize ||
| bibxml | https://xml2rfc.tools.ietf.org/public/rfc/bibxml-ids/reference.I-D.example-name.xml | TBD | All of the bibxml datasets will be available|
| online conversion | https://xml2rfc.tools.ietf.org or https://xml2rfc.tools.ietf.org/experimental.html | https://author-tools.ietf.org | Currently in alpha |

## Work remaining
- [ ] Replacing the BibXML services at xml2rfc.tools.ietf.org
- [ ] Replacing the document validation and conversion services at xml2rfc.tools.ietf.org
- [ ] Containerizing dailydose and changing it to depend on the datatracker
- [ ] pdf-ized views of internet drafts
- [ ] replacing the RPC dependence on tools’ wg-contacts.txt
