<html>
<body>
<h1> In APP Web Client - CISCO MIAW CLIENT</h1>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US';
			embeddedservice_bootstrap.init(
				'00Dx00000008aLX',
				'Agents0102_MIAW',
				'https://ciscosales.perf2r.pc-rnd.force.com/ESWAgents0102MIAW1737461420750',
				{
					scrt2URL: 'https://syntheticciscosales5.perf2r.my.pc-rnd.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://ciscosales.perf2r.pc-rnd.force.com/ESWAgents0102MIAW1737461420750/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</body>
</html>
