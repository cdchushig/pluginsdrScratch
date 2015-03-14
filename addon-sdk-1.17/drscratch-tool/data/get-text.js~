
self.port.on("gresponse", function(gresponse){
	var jrespuesta = gresponse;
	var mastery = JSON.parse(gresponse);
	var level = mastery.project.level;
	var idproject = mastery.project.idProject;
	var points = mastery.project.points;
	var abst = mastery.plugins.Mastery.Abstraction;
	var paralel = mastery.plugins.Mastery.Parallelization;
	var logic = mastery.plugins.Mastery.Logic;
	var flowc = mastery.plugins.Mastery.FlowControl;
	var uinter = mastery.plugins.Mastery.UserInteractivity;
	console.log("recibido desde main.js " + gresponse);
	$("#projectInfo").html("ID Project: " + idproject + " Level: " + level + " Points: " + points);
	$("#mastery1").html("Abstraction: " + abst + " Logic: " + logic + " FlowControl: " + flowc);
	$("#mastery2").html("Parallelization: " + paralel + " UserInteractivity: " + uinter);
});

// Listen for the "show" event being sent from the
// main add-on code. It means that the panel's about
// to be shown.
// Set the focus to the text area so the user can
// just start typing.
//self.port.on("show", function onShow() {
//  textArea.focus();
//});
