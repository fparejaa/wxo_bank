<!DOCTYPE html>
<html lang="en-US">
<head>
    <meta charset="UTF-8">
    <title>New Watson Assistant Bank</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <script>
      window.watsonAssistantChatOptions = {
        integrationID: "a0e1daa7-904b-4841-a140-884cab4ec3e5",
        region: "aws-us-east-1",
        serviceInstanceID: "20240201-1637-3041-7099-be50fcdfec64",
        orchestrateUIAgentExtensions: false,
        onLoad: async (instance) => { await instance.render(); }
      };
      setTimeout(function() {
        const t = document.createElement('script');
        t.src = "https://web-chat.global.assistant.watson.appdomain.cloud/versions/" +
                (window.watsonAssistantChatOptions.clientVersion || 'latest') +
                "/WatsonAssistantChatEntry.js";
        document.head.appendChild(t);
      });
    </script>
</head>
<body>

    <img src="DTE_Bank_wxO.png"
         height="1200"
         alt="New Watson Assistant Bank" />

</body>
</html>
