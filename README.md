# Streamlit (streamlit)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Streamlit is an open-source Python framework that makes it easy to build and share beautiful, custom web apps for machine learning and data science. With Streamlit, you can turn data scripts into shareable web applications in minutes without needing front-end experience. Streamlit Community Cloud provides free hosting for Streamlit apps directly from GitHub repositories. The framework offers a Python API for displaying data, creating interactive widgets, caching computation, and connecting to databases and APIs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/streamlit/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/streamlit/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Data Science
- Machine Learning
- Open Source
- Python
- Web Applications

## Timestamps

- **Created:** 2025-02-12
- **Modified:** 2026-05-19

## APIs

### Streamlit Python API

The Streamlit Python library API provides a rich set of functions for building interactive data applications. Organized by activity type: display data (st.write, st.dataframe, st.table), input widgets (st.button, st.slider, st.selectbox), layout (st.columns, st.tabs, st.sidebar), media (st.image, st.video, st.audio), charts (st.line_chart, st.bar_chart, st.map), and performance (st.cache_data, st.cache_resource). Also includes connection management via st.connection.

- **Human URL:** [https://docs.streamlit.io/develop/api-reference](https://docs.streamlit.io/develop/api-reference)

#### Tags

- Data Science
- Machine Learning
- Open Source
- Python
- Web Applications

#### Properties

- [Documentation](https://docs.streamlit.io/develop/api-reference)
- [Git Hub](https://github.com/streamlit/streamlit)
- [Changelog](https://docs.streamlit.io/develop/quick-reference/changelog)
- [Postman Collection](collections/streamlit-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/streamlit-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Streamlit Community Cloud API

The Streamlit Community Cloud API provides programmatic access to manage deployed Streamlit applications. Supports deploying apps from GitHub repositories, managing app secrets, restarting apps, and workspace management. Authentication uses bearer tokens issued from account settings.

- **Human URL:** [https://docs.streamlit.io/deploy/streamlit-community-cloud](https://docs.streamlit.io/deploy/streamlit-community-cloud)
- **Base URL:** `https://api.streamlit.io/v1`

#### Tags

- Cloud
- Deployment
- DevOps
- Open Source

#### Properties

- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/streamlit/refs/heads/main/openapi/streamlit-cloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://docs.streamlit.io/deploy/streamlit-community-cloud/manage-your-app)
- [Postman Collection](collections/streamlit-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/streamlit-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/streamlit)
- [Website](https://streamlit.io)
- [Documentation](https://docs.streamlit.io)
- [Git Hub](https://github.com/streamlit/streamlit)
- [Forum](https://discuss.streamlit.io)
- [Blog](https://blog.streamlit.io)
- [Gallery](https://streamlit.io/gallery)
- [Changelog](https://docs.streamlit.io/develop/quick-reference/changelog)
- [Terms of Service](https://streamlit.io/terms-of-use)
- [Privacy Policy](https://streamlit.io/privacy-policy)
- [Sign Up](https://share.streamlit.io/signup)
- [Py P I](https://pypi.org/project/streamlit/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/streamlit/refs/heads/main/openapi/streamlit-cloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/streamlit/refs/heads/main/json-schema/streamlit-app-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/streamlit/refs/heads/main/json-ld/streamlit-context.jsonld)
- [L L Ms Txt](https://docs.streamlit.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
