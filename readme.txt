ReadMe for Technicality Google Analytics

This is a very simple WordPress plugin that adds the code needed for Google Analytics to your page. If your Google Analytics Tracking ID is UA-XXXXXXXX-1, this code needs to be added to your page headers for tracking to occur:

<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-XXXXXXXX-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-XXXXXXXX-1');
</script>

The plugin adds a field to the General Settings page for you to enter your Tracking ID. Activate the plugin, enter your Tracking ID - that's all you have to do. The code above (with your Tracking ID) will automatically be inserted into the header of each page your readers view.

This has been tested with WordPress version 5.2.1.

