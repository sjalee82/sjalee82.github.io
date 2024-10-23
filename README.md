
<!DOCTYPE HTML>
<html>
	<head>
		<br><br>
		<title>ESW_scrt1stg9402 ESW CHAT</title>
		<meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1, maximum-scale=1, user-scalable=0">
	</head>

	<body>
		<p>
			<a id="editThisPageLink" target="_blank" style="color:red">Edit this page</a>
		</p>
		
		<script>
			document.getElementById('editThisPageLink').href = "https://github.com/sjalee82/sjalee82.github.io/edit/master" + window.location.pathname;
		</script>
		<br>
		<h2 align="center"><font color ="green"> ESW_SCRT1STG9402 ESW CHAT </font></h2>

		<br/>

		<!-- 5.0 snippet -->

<style type='text/css'>
	.embeddedServiceHelpButton .helpButton .uiButton {
		background-color: #005290;
		font-family: "Arial", sans-serif;
	}
	.embeddedServiceHelpButton .helpButton .uiButton:focus {
		outline: 1px solid #005290;
	}
</style>

<script type='text/javascript' src='https://service.force.com/embeddedservice/5.0/esw.min.js'></script>
<script type='text/javascript'>
	var initESW = function(gslbBaseURL) {
		embedded_svc.settings.displayHelpButton = true; //Or false
		embedded_svc.settings.language = ''; //For example, enter 'en' or 'en-US'

		//embedded_svc.settings.defaultMinimizedText = '...'; //(Defaults to Chat with an Expert)
		//embedded_svc.settings.disabledMinimizedText = '...'; //(Defaults to Agent Offline)

		//embedded_svc.settings.loadingText = ''; //(Defaults to Loading)
		//embedded_svc.settings.storageDomain = 'yourdomain.com'; //(Sets the domain for your deployment so that visitors can navigate subdomains during a chat session)

		// Settings for Chat
		//embedded_svc.settings.directToButtonRouting = function(prechatFormData) {
			// Dynamically changes the button ID based on what the visitor enters in the pre-chat form.
			// Returns a valid button ID.
		//};
		//embedded_svc.settings.prepopulatedPrechatFields = {}; //Sets the auto-population of pre-chat form fields
		//embedded_svc.settings.fallbackRouting = []; //An array of button IDs, user IDs, or userId_buttonId
		//embedded_svc.settings.offlineSupportMinimizedText = '...'; //(Defaults to Contact Us)

		embedded_svc.settings.enabledFeatures = ['LiveAgent'];
		embedded_svc.settings.entryFeature = 'LiveAgent';

		embedded_svc.init(
			'https://scrt1stg9402.stagecom.my.pc-rnd.salesforce.mil',
			'https://scrt1stg9402.stagecom.experience.pc-rnd.crmforce.mil',
			gslbBaseURL,
			'00DRV00000009WL',
			'ESWDep_Ch2',
			{
				baseLiveAgentContentURL: 'https://c.la11-core1dod.sfdc-qge8bq.scrt1.salesforce.mil/content',
				deploymentId: '572RV00000001vN',
				buttonId: '573RV00000001dd',
				baseLiveAgentURL: 'https://d.la11-core1dod.sfdc-qge8bq.scrt1.salesforce.mil/chat',
				eswLiveAgentDevName: 'EmbeddedServiceLiveAgent_Parent04IRV000000001d2AA_192680d55bd',
				isOfflineSupportEnabled: true
			}
		);
	};

	if (!window.embedded_svc) {
		var s = document.createElement('script');
		s.setAttribute('src', 'https://scrt1stg9402.stagecom.my.pc-rnd.salesforce.mil/embeddedservice/5.0/esw.min.js');
		s.onload = function() {
			initESW(null);
		};
		document.body.appendChild(s);
	} else {
		initESW('https://service.force.com');
	}
</script>
    
    	</body>
</html>
