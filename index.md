# CaveBuddy privacy policy

Draft for the developer to complete before hosting. Replace the bracketed fields with the developer’s verified information before hosting.

Effective date · [release date]

CaveBuddy is provided by [developer or business name]. For privacy questions or to request deletion of a report, contact [public privacy contact email].

## Chats and model download

CaveBuddy uses an AI model on your device to generate replies. The app uses the text you enter and recent chat messages to answer. It keeps the conversation in memory for the current session. When you start a new chat or the app process closes, the app clears the session. Generating replies does not send your text to a server. The app does not require an account.

In the language learning preview, words, aliases, concepts, definitions, learned concept links, practice, XP, abilities, and personality scores are stored privately on the device across sessions. CaveBuddy analyzes potential lessons and uses the bundled dictionary on the device. CaveBuddy keeps a limited set of hashes of recognized interactions to limit repeated personality changes. Starting a new chat leaves that progress in place. Resetting the character, clearing app data, or uninstalling clears the progress.

On model setup, the app connects to Hugging Face over Wi-Fi or mobile data to download the model after you approve it. The download service receives ordinary connection information such as your IP address and the requested file. It receives no chat text through the download. The model is stored in the app's private storage and can be removed by clearing app data or uninstalling. Hugging Face's handling of connection information is described in its own privacy policy (https://huggingface.co/privacy).

## Advertising

Android releases with ads enabled use Google AdMob while online. CaveBuddy requests non-personalized ads and applies Google's protections for users of unknown age. Google can receive information such as your IP address, ad interactions, diagnostics, and supported device identifiers for ad delivery, measurement, and fraud prevention. CaveBuddy removes the Android advertising ID permission and does not send chat messages or learned vocabulary to AdMob. The app stores the last video ad time on your device to limit how often a video can appear. If Google makes privacy options available for your region, you can open them from the app. Google's advertising privacy information (https://policies.google.com/technologies/ads)

## Reports

If you confirm a reply report, CaveBuddy sends the selected reply and its report category over HTTPS to a Cloudflare Worker so the developer can review it and improve moderation. The report does not include your chat history. The selected reply may contain information mentioned in your conversation.

The service records the selected reply, category, and submission time in a private Cloudflare D1 database restricted to the EU. It uses the connecting IP address for rate limiting and does not include the address in the report record. A daily cleanup deletes records older than 30 days from the live database. Cloudflare may retain backups under its own backup schedule. To request deletion of an individual report, contact the developer using the privacy address above and include enough information for the developer to locate the report.
