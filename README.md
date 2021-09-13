# argeadCombatTechPublic

  -- ARGEAD TECH - PUBLIC RELEASE
	
	
	--// DESCRIPTION \\--
	
	Argead Tech is a combat tech originally made for Argead Makedonia, an Ancient Era Group. This version of
	the Tech is a public version that is intentionally re-coded to be a "lighter" version of the Argead Tech
	that can be found at Macedonian Anatolia or the Totalis Bellum Battlegrounds.
	
	Being that it is a "light" version of Argead Tech, this means that this version lacks many of the complex
	features that you may be used to or that you may have seen. The original tech contains about **21** different
	animation tracks PER weapon. In order to make Argead Tech's implementation easy peasy, all the essential
	animations have been condensed into a single track per weapon. You may notice the choppy animations and
	transitions because of this decision.
	
	As of now this version of Argead tech contains the BASICS, up-down attack directions for the Dory and Kopis,
	a shield that automatically welds to the arm, and a main folder that controls the stamina and miscellaneous
	features.
	
	**NOTE: There are some pieces of code included into the tech that allows moderation that's in place to benefit
	the genre as a whole. Totalis Bellum Moderators+ are able to check the hitboxes for the shields and weapons
	to determine if the tech has been unfairly tampered with at a place. If these features are removed, it is
	automatically assumed that you have a version of the tech that is modified for unfair advantages.
	
	--// HOW TO INSTALL ARGEAD TECH \\--
	
		--// UPLOAD ANIMATIONS
			--** IF THE PLACE YOU WANT TO UPLOAD THIS TECH TO IS OWNED BY YOU -- UPLOAD ANIMATIONS TO YOUR PROFILE
			--** IF THE PLACE YOU WANT TO UPLOAD THIS TECH TO IS OWNED BY A GROUP -- UPLOAD ANIMATIONS TO THE GROUP
		
		Within the "ANIMATIONS TO UPLOAD" folder, you'll find a handful of `KeyframeSequence` objects. Using Roblox's
		ANIMATION EDITOR, place the keyframes into a dummy's AnimSaves. Use the ANIMATION EDITOR to save and export
		these animations to your GROUP or PROFILE. Once you've successfully uploaded these animations, change the animation
		IDs located in every tool and model provided.
		
			-| Dory --> WeaponAnims --> AnimationId
			-| Kopis --> WeaponAnims --> AnimationId
			-| CharShield --> ShieldAnims --> AnimationId
			
		--// ALTERNATE ANIMATIONS UPLOAD - DUMMY
		
		If you already have the animation plugin installed, simply highlight the dummy and "load" in the animations through the plugin. The keyframe
		sequences are already within the dummy. All you would need to do is load it onto the plugin and export to your profile or on your group inventory.
	 
		--// PLACE ITEMS WITHIN THE FOLDERS TO DESIGNATED LOCATIONS
	
		When you open up Argead Tech in the explorer, you should see labeled folders with instructions on where
		to place the items inside of it. Simply place them in the correct locations to easily implement Argead Tech
		at your place.
		
		In v1.3, two shield types have been added for default use. One shield that has a roman shield and one that has a greek shield. Feel free to
		use any of the two for your own personal use.
		
		
		**--// ARGEAD TECH SHOULD BE FUNCTIONAL IF EVERY STEP ABOVE WAS FOLLOWED \\--**
--]]
	
