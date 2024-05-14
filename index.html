<HTML>
  <style type='text/css'>
        
        .embeddedServiceHelpButton .helpButton .uiButton {
		background-color: #005290;
		font-family: "Arial", sans-serif;
	}
	.embeddedServiceHelpButton .helpButton .uiButton:focus {
		outline: 1px solid #005290;
	}
        
        <div class="slds-scope">
            :host 
            {
            display: flex;
            flex-direction: column;
            }
            
            lightning-button {
            padding-top: 1em;
            }
            .slds-scope .slds-has-error .slds-form-element__help 
            {
            color: var(--slds-g-color-error-base-40, rgb(234, 0, 30)));
            text-align: left;
            }
        </div>
        
    </style>
    <input type="button" value="Start Chat" onclick="startChat();" />

<script type='text/javascript' src='https://service.force.com/embeddedservice/5.0/esw.min.js'></script>
<script type='text/javascript'>
    
    var disableTextTopic = 'Invoice was rejected by reviewer;I want to add a timekeeper;Yes, I am'.split(';');
    
	var initESW = function(gslbBaseURL) {
		embedded_svc.settings.displayHelpButton = false; //Or true
		embedded_svc.settings.language = ''; //For example, enter 'en' or 'en-US'

        //embedded_svc.settings.defaultMinimizedText = '...'; //(Defaults to Chat with an Expert)
        embedded_svc.settings.smallCompanyLogoImgURL = 'https://wolterskluwergrcelm--uat--c.sandbox.vf.force.com/resource/1710761198000/WK_Company_Logo';
        embedded_svc.settings.chatbotAvatarImgURL = 'https://wolterskluwergrcelm--uat--c.sandbox.vf.force.com/resource/1710761198000/Avatar';
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
        embedded_svc.settings.extraPrechatFormDetails = [{"label":"Status","value":"Assigned","displayToAgent":true},
        {"label":"Origin","value":"Chat","displayToAgent":true},
        {"label":"CreatedFrom","value":"LiveChat","displayToAgent":true},
        {"label":"Product","value":"T360","displayToAgent":true},
        {"label":"First Name", "transcriptFields": ["CustomerFirstName__c"]},
        {"label":"Last Name", "transcriptFields": ["CustomerLastName__c"]},
        {"label":"Email", "transcriptFields": ["CustomerEmail__c"]},
        {"label":"Phone", "transcriptFields": ["CustomerPhone__c"]},
        {"label":"Company", "transcriptFields": ["CustomerCompany__c"]},
        {"label":"Company Type", "transcriptFields": ["CustomerCompanyType__c"]},
        {"label":"Network (if applicable)", "transcriptFields": ["Network__c"]},
        {"label":"Case Number (if Applicable)", "transcriptFields": ["CaseNumber__c"]},                                                 
        ];
        
        embedded_svc.settings.extraPrechatInfo = [{
        "entityName": "Contact",
        "showOnCreate": true,
        "linkToEntityName": "Case",
        "linkToEntityField": "ContactId",
        "saveToTranscript": "ContactId",
        "entityFieldMaps" : [{
        "doCreate":false,
        "doFind":true,
        "fieldName":"FirstName",
        "isExactMatch":true,
        "label":"First Name"
        },{
        "doCreate":false,
        "doFind":true,
        "fieldName":"LastName",
        "isExactMatch":true,
        "label":"Last Name"
        },{
        "doCreate":false,
        "doFind":true,
        "fieldName":"Email",
        "isExactMatch":true,
        "label":"Email"
        }],
        }, {
        "entityName":"Case",
        "showOnCreate": true,
        "saveToTranscript": "CaseId",
        "entityFieldMaps": [{
        "isExactMatch": false,
        "fieldName": "Status",
        "doCreate": true,
        "doFind": false,
        "label": "Status"
        },{
        "isExactMatch": false,
        "fieldName": "Origin",
        "doCreate": true,
        "doFind": false,
        "label": "Origin"
        },{
        "doCreate":true,
        "doFind":false,
        "fieldName":"CreatedFrom__c",
        "isExactMatch":true,
        "label":"CreatedFrom"
        } , {
        "doCreate":true,
        "doFind":false,
        "fieldName":"Product__c",
        "isExactMatch":true,
        "label":"Product"
        },{
        "doCreate":false,
        "doFind":true,
        "fieldName":"casenumber",
        "isExactMatch":true,
        "label":"Case Number (if Applicable)"
        }]
        }];

		embedded_svc.init(
			'https://wolterskluwergrcelm--uat.sandbox.my.salesforce.com',
			'https://wolterskluwergrcelm--uat.sandbox.my.salesforce-sites.com/Chatbot',
			gslbBaseURL,
			'00DOy0000016WO4',
			'ELMerT360ServiceDepolyment',
			{
				baseLiveAgentContentURL: 'https://c.la2s-core1.sfdc-yfeipo.salesforceliveagent.com/content',
				deploymentId: '572Oy000000yWeX',
				buttonId: '573Oy000000QkqP',
				baseLiveAgentURL: 'https://d.la2s-core1.sfdc-yfeipo.salesforceliveagent.com/chat',
				eswLiveAgentDevName: 'EmbeddedServiceLiveAgent_Parent04IOy000000GHL3MAO_18f6d0410e2',
				isOfflineSupportEnabled: false
			}
		);
	};

	if (!window.embedded_svc) {
		var s = document.createElement('script');
		s.setAttribute('src', 'https://wolterskluwergrcelm--uat.sandbox.my.salesforce.com/embeddedservice/5.0/esw.min.js');
		s.onload = function() {
			initESW(null);
		};
		document.body.appendChild(s);
	} else {
		initESW('https://service.force.com');
	}
    /*setInterval(function() {
            var menuOptionsFound = false;
 
            var menuOptionsElements = document.querySelectorAll('.embeddedServiceLiveAgentStateChatButtonMessage .chatContent .uiButton');
			
            menuOptionsElements.forEach(function(element) {

                if (disableTextTopic.includes(element.innerText.trim())) {

                    menuOptionsFound = true;

                }

            });
 
            var chatInputFooter = document.querySelector('.embeddedServiceLiveAgentStateChatInputFooter .chasitorControls .uiInput');

            if (menuOptionsFound) {

                chatInputFooter.style.display = 'none'; // Hide chat input footer

            } else {

                chatInputFooter.style.display = 'block'; // Show chat input footer

            }

        }, 1000); */
    
    function startChat() {
      console.log('Inside Start Chat');
      embedded_svc.bootstrapEmbeddedService();
    }

</script>
</HTML>
