---
---

# web-native front-end integration

integrating/orchestrating different applications or services is often one of
the biggest challenges within an organization's IT landscape

for web applications, typically an application queries various services and
aggregates the results within a single HTML page - this aggregation can occur
either on the server or on the client side (e.g. via AJAX)

however, such aggregation requires not only awareness of individual services,
but also a fairly thorough understanding of the data being provided, as it
needs to be transformed into the final result

yet if a provider system provides its own self-contained UI (cf.
[[self-contained-systems]]) in the form of an HTML page, a simple hyperlink is
often sufficient to connect two such systems: e.g. moving between product
catalog and checkout

of course providing a seamless experience in which the end-user does not notice
the transition between systems requires some conventions, e.g. shared styling,
possibly even common elements like navigation and footer (each of which might
be an application of its own)

the sequential traversal of distinct systems can be augmented with client-side
components which optionally resolve a link and embed it within the surrounding
context, effectively transcluding the referenced content
