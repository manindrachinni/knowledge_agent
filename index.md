<html>
<body>
	<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DKj00000EAwzP',
				'Knowledge_Agent_ESD',
				'https://nu1738425293563.my.site.com/ESWKnowledgeAgentESD1741175165575',
				{
					scrt2URL: 'https://nu1738425293563.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://nu1738425293563.my.site.com/ESWKnowledgeAgentESD1741175165575/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</body>
</html>
