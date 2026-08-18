# Privacy Policy — YT Dual Subtitle Translator

**NOT SUBMITTABLE:** required public URL and privacy-contact placeholders below must be replaced with verified publisher material before store submission.

**Effective date:** August 15, 2026  
**Last updated:** August 15, 2026

YT Dual Subtitle Translator (the **“Extension”**) adds machine-translated subtitles to YouTube videos. This policy explains what data the Extension handles, why it handles it, where it goes, how long it remains, and what choices you have.

> **Publication placeholders:** Before publishing the Extension, replace **`[PRIVACY_POLICY_PUBLIC_URL — REQUIRED BEFORE STORE SUBMISSION]`** and **`[PRIVACY_CONTACT_EMAIL — REQUIRED BEFORE STORE SUBMISSION]`**. No public policy URL or contact address is asserted by this repository.

## 1. Data the Extension handles

The Extension handles only the data needed to provide and configure subtitle translation:

- **YouTube subtitle data:** the subtitle text selected for translation and related transient subtitle/track information needed to align it with the current video.
- **Translation choice:** the target language selected by the user.
- **Extension settings:** whether translation is enabled; interface and target languages; translation engine selection; original/translated display mode; subtitle sizes, line width, opacity, background enablement/color/opacity; and timing offset.
- **Consent/enablement record:** a local record containing the current consent version and the time an enable action saved the record.
- **Translation output:** translated subtitle text returned by Google Translate and held temporarily for display and caching.

The Extension does **not** ask for or store a Google Translate API key. It does not intentionally collect names, email addresses, account credentials, payment information, browsing history across sites, or the content of non-YouTube pages.

## 2. How and why data is used

Data is used only for the Extension’s single purpose: to display translated subtitles alongside, or instead of, YouTube captions and to remember the user’s subtitle preferences.

- Subtitle text and target language are used to request machine translation.
- YouTube caption metadata and responses are used in the browser to select, parse, time, and render the current subtitle track.
- Settings are used to control translation and subtitle presentation.
- The consent/enablement record is used as a technical gate: the Background Service Worker rejects translation unless a valid current-version record exists and translation remains enabled.
- Translated text is cached briefly in memory to avoid sending duplicate translation requests.

The developer does not sell or rent user data. The Extension has no advertising, behavioral profiling, analytics, telemetry, or developer-operated model-training pipeline. Data handled by the Extension is not used by the developer for advertising, analytics, creditworthiness or lending decisions, or training developer models.

## 3. Consent, defaults, and controls

Translation is **off by default**. The Extension does not begin translation merely because it is installed.

When no valid current-version local record exists, the Popup, Options page, and YouTube-player settings panel show a disclosure that subtitle text and the selected target language will be sent to Google Translate. Only **Enable translation** in that disclosure saves the record and enables translation. The ordinary **Enable translated subtitles** switch does not grant consent; it can enable translation only after a valid consent record already exists. Selecting **Later** saves `enabled: false` and does not create the record. Turning YouTube CC on is not consent and cannot create the record or enable translation.

The Extension synchronizes trusted user changes to YouTube’s CC button with its translation-enabled setting only after consent already exists. If no consent exists, a trusted CC-on event is blocked: it does not save consent, enable the synced setting, or fetch or translate subtitles; the player shows the disclosure action instead. Turning CC or translation off stops translation but never clears the local consent record.

The Background Service Worker sends translation requests only when both:

1. a valid current-version local consent/enablement record exists; and
2. the translation setting remains enabled.

Turning translation off stops new translation requests. Resetting settings restores default subtitle settings, including the default-off state, but currently does not delete the prior local record. Uninstalling the Extension stops its processing; Chrome normally removes extension-owned local and synced data according to Chrome’s uninstall and sync behavior.

## 4. Data sharing and third-party boundary

When translation is enabled and the valid current-version local record exists, the Extension sends:

- the subtitle text being translated; and
- the selected target language

directly from the browser to the Google Translate GTX endpoint at `https://translate.googleapis.com/translate_a/single` over HTTPS. The request currently uses HTTP GET, so the text and language are encoded in the HTTPS URL query. HTTPS encrypts the request in transit, including the query, between the browser and the service endpoint; endpoint operators and software with access to request URLs may still process or log it.

There is **no developer-operated relay server**: subtitle text and translations are not routed through a server controlled by the Extension developer. Google is the third-party recipient and processes translation requests under Google’s own terms and privacy practices. The developer does not control Google’s retention, logging, security, or secondary use after data crosses this boundary. Users should review Google’s applicable policies before enabling translation.

YouTube remains a separate third party. The Extension runs only on `https://www.youtube.com/*`, reads caption data made available to the current YouTube page/player, and may directly request valid YouTube timed-text resources over HTTPS. YouTube’s handling of video, account, and caption data is governed by YouTube/Google policies, not this policy.

## 5. Storage, cache size, and retention

### Synced settings

Extension settings are saved in `chrome.storage.sync`. Chrome may synchronize these settings through the user’s signed-in Chrome profile according to the user’s Chrome sync configuration and Google’s applicable policies. Subtitle text and translated text are not written to `chrome.storage.sync` by the translation cache.

### Local consent/enablement record

The consent/enablement version and enablement timestamp are saved in `chrome.storage.local`, local to the Chrome profile rather than intentionally synchronized by the Extension. A separate settings-schema version marker is also stored locally. These local records remain until extension-owned data is removed, such as through uninstall or browser/profile storage management. Resetting subtitle settings removes and recreates the settings-version marker but currently does not remove the consent/enablement record.

### In-memory translation cache

The Background Service Worker maintains an in-memory least-recently-used translation cache containing the source text as part of the cache key and the translated text as its value. Its verified defaults are:

- **maximum size:** 1,000 entries;
- **time to live:** 30 minutes per entry from insertion; and
- **eviction:** expired entries are removed when accessed, and least-recently-used entries are removed when capacity is exceeded.

The cache is not persisted to Chrome storage. It disappears when the service worker’s memory is discarded, the Extension is reloaded, or the Extension is uninstalled; Chrome may discard that memory before the 30-minute TTL.

### Other transient processing

Current YouTube caption payloads and translation work may exist temporarily in page, content-script, or service-worker memory while a video is processed. The Extension does not provide a developer database or cloud account in which this data is retained.

## 6. Permissions and security

The Extension requests only:

- **`storage`** to save settings, the local consent/enablement record, and the settings-schema version marker;
- **host access to `https://www.youtube.com/*`** to identify the current YouTube watch page and caption track, access valid YouTube timed-text responses, synchronize captions with playback, render translated subtitles, and add the extension’s settings entry to the YouTube player. The content script is matched on the YouTube host, but subtitle processing starts only for a watch page with a video ID; the Extension does not request broad access to other websites; and
- **host access to `https://translate.googleapis.com/*`** to send gated translation requests directly to Google Translate.

Network endpoints are HTTPS. Stored settings and local consent/enablement records are restricted to trusted extension contexts when Chrome supports the relevant access-level API. The Extension uses packaged JavaScript and does not intentionally download or execute remote code. No method of transmission or storage is guaranteed to be completely secure, however.

## 7. Disclosure, transfer, and sale

The developer does not sell user data and does not disclose it to advertisers, data brokers, analytics providers, or developer-operated training systems. Data is transferred to Google Translate only to provide the user-requested translation, as described above. The developer does not use handled data for creditworthiness or lending decisions. Data may also be disclosed if required by applicable law; because the Extension has no developer relay or backend collection, the developer ordinarily does not possess subtitle requests sent directly to Google.

## 8. Children and sensitive content

The Extension is a general-purpose subtitle utility and is not directed specifically to children. Subtitle text can reflect whatever a user chooses to watch and may contain personal or sensitive information. Users should not enable translation for content they do not want sent to Google Translate. If applicable law requires parental consent for a user, that consent should be obtained before using the translation feature.

## 9. International processing

Google may process translation requests in countries other than the user’s country. Chrome sync may likewise process synchronized settings through Google infrastructure. Those transfers are governed by Google’s applicable terms, privacy policies, and legal mechanisms. The Extension developer does not choose Google’s processing locations.

## 10. Your choices and requests

Users can:

- leave translation off or select **Later** at the disclosure;
- turn translation off at any time to stop new translation requests; note that trusted changes to YouTube CC can synchronize with the translation setting only after consent exists;
- change the target language or other saved settings;
- use **Reset all settings** to restore subtitle settings to defaults (this does not currently remove the saved local consent/enablement record); or
- uninstall the Extension to stop processing; Chrome normally removes extension-owned local and synced data according to Chrome’s uninstall and sync behavior.

Because the developer does not operate an account system, relay server, analytics service, or user database for this Extension, the developer generally cannot identify or retrieve an individual user’s subtitle requests. Privacy questions or legally applicable requests may be sent to **`[PRIVACY_CONTACT_EMAIL — REQUIRED BEFORE STORE SUBMISSION]`**.

## 11. Changes to this policy

This policy may change when the Extension’s features, providers, data practices, or legal obligations change. Material changes should be reflected by updating the “Last updated” date, publishing the revised policy, and updating in-product/store disclosures where required. A future consent-version change and re-consent mechanism is tracked in [`TODO.md`](TODO.md); the current implementation recognizes consent version 1.

## 12. Contact

Privacy contact: **`[PRIVACY_CONTACT_EMAIL — REQUIRED BEFORE STORE SUBMISSION]`**  
Support contact: **`[SUPPORT_CONTACT_OR_URL — REQUIRED BEFORE STORE SUBMISSION]`**  
Public privacy-policy URL: **`[PRIVACY_POLICY_PUBLIC_URL — REQUIRED BEFORE STORE SUBMISSION]`**

## Publishing this policy with GitHub Pages

These steps intentionally do not invent a repository owner, repository name, branch deployment URL, or custom domain.

1. Replace **every bracketed placeholder in this file and in `store-listing.md`**, including those marked `REQUIRED IF APPLICABLE`, with verified publisher information; remove any inapplicable field rather than leaving placeholder text. Treat any remaining `[`…`REQUIRED`…`]` token as a submission blocker.
2. In the GitHub repository, open **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**. Under the branch selector, select the intended branch and the **`/docs`** folder, then click **Save**. If the repository uses an approved GitHub Actions Pages workflow instead, configure and review that workflow rather than selecting a branch source.
4. Wait for GitHub to report a successful Pages deployment. If GitHub does not offer the branch or `/docs` source, verify that the intended branch contains this `docs/` directory, Pages is available for the repository/plan, and your repository permissions allow Pages configuration; do not invent a fallback URL.
5. Open the exact policy file URL displayed or implied by the successful deployment—under the standard GitHub Pages branch/Jekyll flow for this repository, that is the project-site URL plus **`/privacy-policy.html`**, not the site root—and verify that the policy renders, all headings are readable, and the contact information is correct.
6. Copy that verified URL into **`[PRIVACY_POLICY_PUBLIC_URL — REQUIRED BEFORE STORE SUBMISSION]`** here, the Chrome Web Store Dashboard privacy-policy field, and [`store-listing.md`](store-listing.md). Do not infer the URL from an unverified owner/repository name.
7. Recheck the public page in a signed-out/private browser window before submitting the listing.
