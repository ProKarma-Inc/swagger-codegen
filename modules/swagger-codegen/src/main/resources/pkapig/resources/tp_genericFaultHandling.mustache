

        var statusCode = context.getVariable("tp.fault.statusCode");
		var reasonPhrase = context.getVariable("tp.fault.reasonPhrase");
		var exceptionType = context.getVariable("tp.fault.exceptionType");
		var messageId = context.getVariable("tp.fault.messageId");
		var messageText = context.getVariable("tp.fault.messageText");
		var messageVariables = context.getVariable("tp.fault.messageVariables");
		
var faultName = context.getVariable("fault.name");
if( faultName == "InvalidAccessToken" || faultName == "invalid_access_token" || faultName == "access_token_expired" || faultName == "access_token_not_approved"){
				statusCode = 401;
				reasonPhrase = "Unauthorized";
				messageText = "A policy error occurred. Error code is %1";
				messageVariables = "invalid accesstoken";
				exceptionType = "policyException";
				messageId = "POL0001"
			}
else if(faultName == "SpikeArrestViolation"){
				statusCode = 503;
				reasonPhrase = "Service Unavailable";
				messageText = "SpikeArrest-The API call rate limit has been exceeded. Please try after 1000 ms.";
				messageVariables = "NA";
				exceptionType = "Service Unavailable";
				messageId = "SVC00000"
			}
			
			
    context.setVariable("tp.fault.statusCode", statusCode);
	context.setVariable("tp.fault.reasonPhrase", reasonPhrase);
  	context.setVariable("tp.fault.exceptionType",exceptionType);
	context.setVariable("tp.fault.messageId",messageId);
	context.setVariable("tp.fault.messageVariables", messageVariables.toString());
	context.setVariable("tp.fault.messageText", messageText);
	context.setVariable("Status_Code", statusCode);