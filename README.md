TASK DATE: 28.11.2017 - FINISHED: 28.11.2017 (VERY EASY)

TASK SHORT DESCRIPTION: 1091 (hide ways to donate widget box, when empty)

GITHUB REPOSITORY CODE: hotfix/task-1091-hide-donate-widget-box-when-empty

ORIGINAL WORK: https://github.com/BusinessBecause/network-site/tree/hotfix/task-1091-hide-donate-widget-box-when-empty


CHANGES
 
	IN FILES: 
	
		\network-site\addons\default\modules\fundraising\views\supportus.php
		\network-site\addons\default\modules\network_settings\views\content\preview.php
		
			CHANGED CODE: 
			
				FROM: <div class="donate" style="display:block">
				
				TO: <div class="donate" style="display: <?php echo !empty($custom_section_one) ? "block" : "none" ?>;">
	
