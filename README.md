Experimental application to explore Blazor.

Aim is to have apps that have a "ping" button. When anyone clicks the ping
button, then everyone who has installed the app should get a ping message.

Target platform are mobile phones. Aim is to be a like-native app experience.


<script src="https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.min.js"></script>
<script>mermaid.initialize({startOnLoad:true});</script>
# Purpose

To demo SignalR talking with Blazor WebAssembly. Application is a simple client application that displays messages broadcast from the SignalR server.

# Mermaid.js Test

<div class="mermaid">
    graph TD
    A[Client] --> B[Load Balancer]
    B --> C[Server01]
    B --> D[Server02]
</div>
