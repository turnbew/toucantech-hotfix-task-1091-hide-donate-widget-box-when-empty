FOR PRIVACY AND CODE PROTECTING REASONS THIS IS A SIMPLIFIED VERSION OF CHANGES AND NEW FEATURES

TASK DATE: 28.11.2017 - FINISHED: 28.11.2017

TASK LEVEL: VERY EASY

TASK SHORT DESCRIPTION: 1091 (hide ways to donate widget box, when empty)
	
GITHUB REPOSITORY CODE: hotfix/task-1091-hide-donate-widget-box-when-empty

CHANGES
 
	IN FILES: 
	
		supportus.php
		preview.php
		
			CHANGED CODE: 
			
				FROM: <div class="donate" style="display:block">
				
				TO: <div class="donate" style="display: <?php echo !empty($custom_section_one) ? "block" : "none" ?>;">
	
