# Web-Chat-ibm-waston
محادثة شات مع البوت و دمجها مع واجهة التحكم

في ملف(robot_base+arm.html)


الكود:

<script>
    window.watsonAssistantChatOptions = {
        integrationID: "53077708-dcd5-4fad-95f5-d7cb7276c7cf", // The ID of this integration.
        region: "eu-de", // The region your integration is hosted in.
        serviceInstanceID: "cca76660-6b50-488f-baf1-c6e8572801dc", // The ID of your service instance.
        onLoad: function(instance) { instance.render(); }
      };
    setTimeout(function(){
      const t=document.createElement('script');
      t.src="https://web-chat.global.assistant.watson.appdomain.cloud/loadWatsonAssistantChat.js";
      document.head.appendChild(t);
    });
  </script>
