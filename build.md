1DM: 18.2  
AmazonShopping: 32.18.0.100  
Excel: 16.0.20228.20090  
GoogleMaps: 26.36.04.973607363  
Music: 9.20.53  
Pinterest: 14.41.0  
Shazam: 16.63.0-261008  
TikTok: 47.4.3  
YouTube: 21.20.405  

Install [Microg](https://github.com/MorpheApp/MicroG-RE/) for non-root YouTube and YT Music APKs  
Use [zygisk-detach](https://github.com/j-hc/zygisk-detach) to detach YouTube and YT Music modules from Play Store  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)
  
Patches: bearinmindcat/morphe-patches/patches-2.5.5.mpp  
[Changelog](https://github.com/bearinmindcat/morphe-patches/releases/tag/v2.5.5)

## [2.5.5](https://github.com/bearinmindcat/morphe-patches/compare/v2.5.4...v2.5.5) (2026-10-14)

### 🐛 Bug Fixes

* navigation in landscape no longer keeps the portrait layout after turning the phone; issue [#48](https://github.com/bearinmindcat/morphe-patches/issues/48) ([0e27aca](https://github.com/bearinmindcat/morphe-patches/commit/0e27acae74dbd2349005bd8ee76adf9d88b280a3))

Patches: dunecache/oyasumi-patches/patches-0.5.3.mpp  
[Changelog](https://github.com/dunecache/oyasumi-patches/releases/tag/v0.5.3)

## [0.5.3](https://github.com/dunecache/oyasumi-patches/compare/v0.5.2...v0.5.3) (2026-09-30)

### 🐛 Bug Fixes

* push a zero before the forced steps, not just the steps ([f51ed17](https://github.com/dunecache/oyasumi-patches/commit/f51ed1783a74db8ddf6b33b5113aeff89d6e169d))

CLI: MorpheApp/morphe-cli/morphe-desktop-1.19.0-all.jar  
Patches: heval99/Heval-Morphe-Patches/patches-1.18.0.mpp  
[Changelog](https://github.com/heval99/Heval-Morphe-Patches/releases/tag/v1.18.0)

## [1.18.0](https://github.com/heval99/Heval-Morphe-Patches/compare/v1.17.0...v1.18.0) (2026-10-22)

### 🐛 Bug Fixes

* **ads:** make Disable ads block what it promises in Castbox, Podcast Republic, Pi Music Player, BeSoccer, Expert Player and Moneycontrol ([40ac9d3](https://github.com/heval99/Heval-Morphe-Patches/commit/40ac9d3c3d730801d6ae3b39c01b3f3a219e7242))
* fail loudly on drift and harden GmsCore support ([7dd00a6](https://github.com/heval99/Heval-Morphe-Patches/commit/7dd00a6284a765eb924d40017e33cf3baf28ef32))
* **kakaotalk,line:** remove KakaoTalk and LINE support ([dd9dd18](https://github.com/heval99/Heval-Morphe-Patches/commit/dd9dd188ef4adbfb5597f779b4adff9d2100c2ab))
* keep only the latest verified version per app and correct the patch notes ([d0f5354](https://github.com/heval99/Heval-Morphe-Patches/commit/d0f5354314601b483cdf0007ded73092668f1ad6))
* **shazam:** open the Spotify login in a browser tab ([7075b7f](https://github.com/heval99/Heval-Morphe-Patches/commit/7075b7fe3815148b016ba8ac435f6020b90ba7a2)), closes [#62](https://github.com/heval99/Heval-Morphe-Patches/issues/62)
* **sofascore,shazam,brave,truecaller:** complete the telemetry, Web Discovery and server-backed premium gates ([8708913](https://github.com/heval99/Heval-Morphe-Patches/commit/8708913a197aba881423f7352f16847619762762))

### ✨ New Features

* **truecaller:** add Disable contact upload ([94b5eca](https://github.com/heval99/Heval-Morphe-Patches/commit/94b5ecaec85fcf23ac97302f4ea6ebf4b03231cb))
* **wemuslim:** add WeMuslim 3.5.4 support ([ef5b416](https://github.com/heval99/Heval-Morphe-Patches/commit/ef5b416ccd58b78a643e9d8fae74388a48013822))

Patches: MorpheApp/morphe-patches/patches-1.48.0.mpp  
[Changelog](https://github.com/MorpheApp/morphe-patches/releases/tag/v1.48.0)

## [1.48.0](https://github.com/MorpheApp/morphe-patches/compare/v1.47.0...v1.48.0) (2026-10-22)

### 🐛 Bug Fixes

* **Downloads:** Allow using in-app downloads with player overlay external download button ([3df6c0a](https://github.com/MorpheApp/morphe-patches/commit/3df6c0a3d9ad097db63709cf5b559223d4575dd6))
* Export only filtered logs and stream file exports efficiently ([#3746](https://github.com/MorpheApp/morphe-patches/issues/3746)) ([e04c72d](https://github.com/MorpheApp/morphe-patches/commit/e04c72d8e068204c3a2178b75451fb8bfbb4d755))
* Temporarily revert patches-library update to fix app startup crash ([fd8cc0f](https://github.com/MorpheApp/morphe-patches/commit/fd8cc0fb14540b1e0d6adec903a7c2720a80b2f7))
* **YouTube - Add to queue:** Fix Premium-style queue bugs ([#3752](https://github.com/MorpheApp/morphe-patches/issues/3752)) ([b07a6ac](https://github.com/MorpheApp/morphe-patches/commit/b07a6ac48bae7e6cd0336d4afdc12e368d5442d4))
* **YouTube - Ambient mode:** Force Ambient mode when the server turns it off ([0eda16c](https://github.com/MorpheApp/morphe-patches/commit/0eda16c28e7ca4842a9087bba0fb47d146feddfa))
* **YouTube - Captions:** Restore all translation menu getter routes ([#3818](https://github.com/MorpheApp/morphe-patches/issues/3818)) ([3a6a5b3](https://github.com/MorpheApp/morphe-patches/commit/3a6a5b3ae1d934114668a68ebe56bd512baae18e))
* **YouTube - Captions:** Restore translations from original caption sources ([#3794](https://github.com/MorpheApp/morphe-patches/issues/3794)) ([46ab900](https://github.com/MorpheApp/morphe-patches/commit/46ab900bd9daa990a4d741a6e7f3dc5611173cdb))
* **YouTube - Captions:** Show auto-translated captions of styled caption tracks ([#3837](https://github.com/MorpheApp/morphe-patches/issues/3837)) ([aedcf19](https://github.com/MorpheApp/morphe-patches/commit/aedcf198849b226d3b23638e5e810d9ea39999ba))
* **YouTube - Custom font:** Show custom font picker if no font is selected yet ([8347b98](https://github.com/MorpheApp/morphe-patches/commit/8347b98e007c98065bbe2d546a89bf4f1daa1dce))
* **YouTube - Default video quality:** Forcely disabled automatic stock quality selection and deprecated the code to handle both Stock/Morphe quality selections ([93e0c2b](https://github.com/MorpheApp/morphe-patches/commit/93e0c2b4db27760a22b1e48aef8b87dc330a92bf))
* **YouTube - Default video quality:** SABR video quality drops while the video plays ([#3853](https://github.com/MorpheApp/morphe-patches/issues/3853)) ([0488bda](https://github.com/MorpheApp/morphe-patches/commit/0488bda28d4d5844a2a739d3eefd00c28afd43fa))
* **YouTube - Default video quality:** Video quality drops while the video plays ([9f7b7eb](https://github.com/MorpheApp/morphe-patches/commit/9f7b7ebb10c909f7d2bc480de9fdbd3dd6076e2f))
* **YouTube - Disable translucent bar:** Replace flag override with a proper patch ([88f77a8](https://github.com/MorpheApp/morphe-patches/commit/88f77a86ae737bc5da476011918d480baeff90b3))
* **YouTube - Downloads:** Music videos may not download ([0bac4fa](https://github.com/MorpheApp/morphe-patches/commit/0bac4fa12101e5729e5b4c060d9bac10250281aa))
* **YouTube - Downloads:** Playing video enters picture-in-picture when the external downloader opens ([#3882](https://github.com/MorpheApp/morphe-patches/issues/3882)) ([cf43209](https://github.com/MorpheApp/morphe-patches/commit/cf43209679dbba198e963aa381ce25110a6aa8fb))
* **YouTube - Feed card layout:** Remove the feed vertical spacing override, which can crash the app ([31a85c7](https://github.com/MorpheApp/morphe-patches/commit/31a85c7d1bfb99658c668444c37fd96e16500398))
* **YouTube - Feed card layout:** Round the top outer corners of the Shorts shelves ([8effa2e](https://github.com/MorpheApp/morphe-patches/commit/8effa2e103947e57455e2b93629186a411c86f37))
* **YouTube - Feed card layout:** Shorts shelves of the search results are not cards ([12ed02f](https://github.com/MorpheApp/morphe-patches/commit/12ed02f49d3059875435c6d8cdebe548c7e80dd3))
* **YouTube - Feed card layout:** Show missing watch progress on feed cards ([#3926](https://github.com/MorpheApp/morphe-patches/issues/3926)) ([096798f](https://github.com/MorpheApp/morphe-patches/commit/096798f5877ffce88bac17adef5a9477931071b0))
* **YouTube - Feed card layout:** Sort buttons of the channel tabs have a card background ([328121e](https://github.com/MorpheApp/morphe-patches/commit/328121e9a5b6552075db00327c12ecf39feda762))
* **YouTube - Feed card layout:** Vertical video shelves are not cards ([44564ee](https://github.com/MorpheApp/morphe-patches/commit/44564eeff5d617dab0b0210c149a9c190e9f0021))
* **YouTube - Feed cards layout:** Cards sometimes lose spacing ([0658f00](https://github.com/MorpheApp/morphe-patches/commit/0658f0083bc5d143b379097b706d4114a845a08f))
* **YouTube - Feed cards layout:** Keep horizontal layout for search results on tablets ([0108028](https://github.com/MorpheApp/morphe-patches/commit/0108028df245e0664974d345c58a291f95a1245e))
* **YouTube - Feed cards layout:** Make new style more consistent ([#3801](https://github.com/MorpheApp/morphe-patches/issues/3801)) ([5dc0d0c](https://github.com/MorpheApp/morphe-patches/commit/5dc0d0c71ef9c9c11709e62568eb9c1778e9a4c7))
* **YouTube - Feed video actions:** Show on the grid of landscape ([#3875](https://github.com/MorpheApp/morphe-patches/issues/3875)) ([db5e7d0](https://github.com/MorpheApp/morphe-patches/commit/db5e7d0f97d44032212e7a4451ab38466fd67506))
* **YouTube - Feed video actions:** Watch later button opens the share sheet ([6c94f32](https://github.com/MorpheApp/morphe-patches/commit/6c94f32df957beda5721729f12385eea3537c975))
* **YouTube - Feed view count:** Keep the badge away from the edges of inset thumbnails, show lakh and crore units ([544013a](https://github.com/MorpheApp/morphe-patches/commit/544013adcc8881104c003d8d5e3280f725fc676e))
* **YouTube - Feed view count:** Show on the grid of landscape, same corners and text size as the other badges ([#3874](https://github.com/MorpheApp/morphe-patches/issues/3874)) ([733b6d1](https://github.com/MorpheApp/morphe-patches/commit/733b6d108f09c23892fbe3201dee55e45224b9c3))
* **YouTube - Force animations:** Animate page transitions when the server turns them off ([79979bc](https://github.com/MorpheApp/morphe-patches/commit/79979bcae286d7bbb11b6ccc06558e812b07637f))
* **YouTube - Forced video codec:** Excluded VP9 stream with forced AVC superseeded by Shorts VP9 with SABR restarting fix ([2335a8f](https://github.com/MorpheApp/morphe-patches/commit/2335a8f22eed59d36f1c3c7f0cb8de9fa846207f))
* **YouTube - Hide layout components:** Video titles being hidden on `20.21.37` ([fead993](https://github.com/MorpheApp/morphe-patches/commit/fead993a68706580163825403b3ffd60a6866333))
* **YouTube - Hide preview comment:** Removed the timestamp from the Spanned String instead of disabling its tap logic ([cca6aca](https://github.com/MorpheApp/morphe-patches/commit/cca6aca240ef99e55740af20342a5d28deda6275))
* **YouTube - Jam queue sharing:** Keep the YouTube Music player aligned when Jam queue sharing is off ([#3704](https://github.com/MorpheApp/morphe-patches/issues/3704)) ([fd0db0b](https://github.com/MorpheApp/morphe-patches/commit/fd0db0b04bc12f80acde7fc259d7f72dbf724b13))
* **YouTube - Minimal comments button:** Hide page selector with new layout ([30a9dd1](https://github.com/MorpheApp/morphe-patches/commit/30a9dd17c87658ae405c6223661e478bce2a9629))
* **YouTube - Minimal miniplayer:** Apply minimized position based on commit [#9d8b0df43](https://github.com/MorpheApp/morphe-patches/issues/9d8b0df43) insets ([7f9fb1f](https://github.com/MorpheApp/morphe-patches/commit/7f9fb1f7df988afc7a21ffa4735227a404c06444))
* **YouTube - Minimal miniplayer:** Bar is cut off by the display cutout in landscape ([01267da](https://github.com/MorpheApp/morphe-patches/commit/01267da0f015fb868edb6b59e1086778966c7900))
* **YouTube - Minimal miniplayer:** Show DeArrow title on type 1 style ([72f7b82](https://github.com/MorpheApp/morphe-patches/commit/72f7b82c8ac8d9032d7834abb10ae9f9b86c5ba1))
* **YouTube - Miniplayer:** Match minimal miniplayer icons by content description name instead of resource id ([4502949](https://github.com/MorpheApp/morphe-patches/commit/4502949a61f6d5d39f72e4052f083cbe1460bd09))
* **YouTube - Miniplayer:** Watch transition animation is missing ([779d81c](https://github.com/MorpheApp/morphe-patches/commit/779d81c856133efc0e59a83e81f9628cd05a581f))
* **YouTube - Navigation bar:** App crashes on Android 12-13 when the player is dragged down to the miniplayer ([#3937](https://github.com/MorpheApp/morphe-patches/issues/3937)) ([a6db8d7](https://github.com/MorpheApp/morphe-patches/commit/a6db8d7aba965471d9a51f27ad7324513e2eb40b))
* **YouTube - Navigation bar:** bug: Navigation bar is not disabled in shorts player ([03f3aa2](https://github.com/MorpheApp/morphe-patches/commit/03f3aa27bc48cfb23a54c723065c83283eed6bc2))
* **YouTube - Navigation bar:** Increased the spacing between Shorts player and navigation bar when this latter is hidden ([a6fdc2f](https://github.com/MorpheApp/morphe-patches/commit/a6fdc2f1331f5d2fe14da2abb89dfe4b8799ce7f))
* **YouTube - Navigation bar:** Navigation bar grows and covers the page when the keyboard is open ([7ec9a54](https://github.com/MorpheApp/morphe-patches/commit/7ec9a549a75798c76439a38400dbc325b7cd78df))
* **YouTube - Navigation bar:** Navigation bar is raised and an empty bar is left at the bottom ([eca3334](https://github.com/MorpheApp/morphe-patches/commit/eca3334c07df995dbbb4f58ed425591883086554))
* **YouTube - Navigation bar:** Navigation bar is raised and an empty bar is left at the bottom on Android 11 and lower ([e91d606](https://github.com/MorpheApp/morphe-patches/commit/e91d60686bbc66182eab43e510c04d247e5fb323))
* **YouTube - New feed cards layout:** Rounded edges and padding was wrong ([7d54662](https://github.com/MorpheApp/morphe-patches/commit/7d5466217e5dc7ea1ea323d4f9d7a6baf9f42f8a))
* **YouTube - Open system share sheet:** Build link from share entity ([#3735](https://github.com/MorpheApp/morphe-patches/issues/3735)) ([92e9eb9](https://github.com/MorpheApp/morphe-patches/commit/92e9eb9d0fa941719c6cf7c048dae16ef163812c))
* **YouTube - Reload video:** Videos playing in the feed replace the reloaded video ([92e41c4](https://github.com/MorpheApp/morphe-patches/commit/92e41c43d2a0deb766f081e5b36e1556675e4090))
* **YouTube - Restore original titles:** Do not reload the same video title once the player is opened ([1648848](https://github.com/MorpheApp/morphe-patches/commit/1648848f2b3b2215f0ed3e6a08ddc0877a9365de))
* **YouTube - Return YouTube Dislike:** Place the feed thumbnail like count on inset thumbnails and channel posts ([#3902](https://github.com/MorpheApp/morphe-patches/issues/3902)) ([de420c2](https://github.com/MorpheApp/morphe-patches/commit/de420c275ea33a3664e5ab6424903ff54c2359c4))
* **YouTube - Spoof video streams:** In-app downloads are slow when using spoof streaming ([6a8b5a9](https://github.com/MorpheApp/morphe-patches/commit/6a8b5a976c011ea1d365e90db143c9b4d8745976))
* **YouTube - Video quality:** Fix VP9 Shorts restarting in a loop with spoofed SABR streams ([ef04cc3](https://github.com/MorpheApp/morphe-patches/commit/ef04cc3c12131d0667e598a935425143d1a6dcf1))
* **YouTube - Video quality:** Improved Shorts VP9 SABR loop restarting fix ([aeccfab](https://github.com/MorpheApp/morphe-patches/commit/aeccfabc5c4f256654ab209ff0741a3b5fada31c))
* **YouTube - VideoInformation:** Separated Video and Shorts informations ([e913727](https://github.com/MorpheApp/morphe-patches/commit/e913727f3a115f7be807bc32efbf6c054b8fa35d))
* **YouTube - VideoInformation:** Videos loaded in the background replace the video and playlist IDs of the player ([0ed3595](https://github.com/MorpheApp/morphe-patches/commit/0ed35954b6db94a12956c98b8db620e09dc65dd5))
* **YouTube Music - Android Auto:** Fix large collections not loading on 9.15 ([#3849](https://github.com/MorpheApp/morphe-patches/issues/3849)) ([1c18d6a](https://github.com/MorpheApp/morphe-patches/commit/1c18d6a02a119d0147593d3615c46dce3a65ff19))
* **YouTube Music - Crossfade:** Preserve repeat state on 9.40+ ([#3916](https://github.com/MorpheApp/morphe-patches/issues/3916)) ([ce688de](https://github.com/MorpheApp/morphe-patches/commit/ce688de5f6a0693a0df01e37cf25478eaac2524b))
* **YouTube Music - Enable exclusive audio playback:** Prevent podcasts stopping in Android Auto ([#3850](https://github.com/MorpheApp/morphe-patches/issues/3850)) ([7a2b926](https://github.com/MorpheApp/morphe-patches/commit/7a2b926302f34d1309fb3896ed6720d0db5ab8a5))
* **YouTube Music:** Experimental app version does not patch ([12fad56](https://github.com/MorpheApp/morphe-patches/commit/12fad5684a453f5f8e359e6f66a2ab04e6caede8))
* **YouTube:** "Play next/last in queue" does nothing from feeds when no video is playing ([c770414](https://github.com/MorpheApp/morphe-patches/commit/c770414fb0ed43ac8f2af7519f7f9222cae8f780))
* **YouTube:** Add missing experimental compatibility declaration ([a81a933](https://github.com/MorpheApp/morphe-patches/commit/a81a933274cde895d3b4e026c2d084f35b9b20c5))
* **YouTube:** App can crash when an observer removes itself while it is notified ([5ee5a72](https://github.com/MorpheApp/morphe-patches/commit/5ee5a724433d6b96b7847e98aaf39c096bd81d5f))
* **YouTube:** Channel search not working properly ([ab2ecc7](https://github.com/MorpheApp/morphe-patches/commit/ab2ecc7a31f6678a698893663ee707d49fc51648))
* **YouTube:** Comments button page indicator is invisible with the light theme ([0f7f6d8](https://github.com/MorpheApp/morphe-patches/commit/0f7f6d8f6625d73941e211c51167097288f8682d))
* **YouTube:** Error toasts on app startup with YouTube 21.40+ ([2151a04](https://github.com/MorpheApp/morphe-patches/commit/2151a04d0dfcc7f54e28af645a0e304f9af2d265))
* **YouTube:** Fixed some 21.42+ fingerprints ([7bf6e1f](https://github.com/MorpheApp/morphe-patches/commit/7bf6e1fe85a75f9fcac4869d5ef548b21e2e5534))
* **YouTube:** Flyout menu text is cut when Morphe items are added ([f8b7669](https://github.com/MorpheApp/morphe-patches/commit/f8b7669dfd9b10ed68da3cfae4190cb0f2c7430a))
* **YouTube:** Force show translucent navigation bar ([e5bb8bf](https://github.com/MorpheApp/morphe-patches/commit/e5bb8bfea55258a6926243fbfb7ed19fffea3925))
* **YouTube:** History items are hidden when the keyboard is open ([3f38b2d](https://github.com/MorpheApp/morphe-patches/commit/3f38b2ded7f857a0240126388686234d3c786892))
* **YouTube:** Light/Dark theme colors are wrong ([93cf169](https://github.com/MorpheApp/morphe-patches/commit/93cf169e8fa7f96bef741fe5f02f5654b2ae70f6))
* **YouTube:** Restore Edge TTS and add voice catalog refresh ([#3840](https://github.com/MorpheApp/morphe-patches/issues/3840)) ([4aa4deb](https://github.com/MorpheApp/morphe-patches/commit/4aa4deb6cd6ad4bf01a0f199e984dd3b33449fab))
* **YouTube:** Some external links can not be opened ([128b8d4](https://github.com/MorpheApp/morphe-patches/commit/128b8d4104e17a5b2527c3f951026f9ff79b4ea6))
* **YouTube:** Status bar becomes dark ([9d8b0df](https://github.com/MorpheApp/morphe-patches/commit/9d8b0df43ae3cd4dfc1a537311d4dfc6aa600ac5))
* **YouTube:** Status bar is opaque, black bar above the player and crash on startup ([b5d9498](https://github.com/MorpheApp/morphe-patches/commit/b5d9498577ea285c8dd490bb823bbbd9c6674624))
* **YouTube:** Video metadata panel text can not be read with the light theme ([332e18e](https://github.com/MorpheApp/morphe-patches/commit/332e18e82b73cc737fc6c84d1126e6fa915821fb))
* **YouTube:** Watch page background turns black in light mode ([4667cb0](https://github.com/MorpheApp/morphe-patches/commit/4667cb0ef1d13ee756c87976801f366869d7144d))

### ✨ New Features

* **Reddit - Full width feed media:** Make embedded video players full width ([#3696](https://github.com/MorpheApp/morphe-patches/issues/3696)) ([53b6448](https://github.com/MorpheApp/morphe-patches/commit/53b64487109e05f13d8e0bc581f86e581cd4662b))
* **Reddit - Redgifs audio:** Download Redgifs videos with audio ([#3869](https://github.com/MorpheApp/morphe-patches/issues/3869)) ([f2ed85e](https://github.com/MorpheApp/morphe-patches/commit/f2ed85e67e518ec9115d51d7d6eb0d208232b646))
* **Reddit:** Add `Copy text` patch ([#3665](https://github.com/MorpheApp/morphe-patches/issues/3665)) ([3068f23](https://github.com/MorpheApp/morphe-patches/commit/3068f23e357825a77f6d67760f427634e3baee0c))
* **Reddit:** Add `Customize post layout` patch ([#3541](https://github.com/MorpheApp/morphe-patches/issues/3541)) ([a301bc1](https://github.com/MorpheApp/morphe-patches/commit/a301bc1d07ebd96390566cc2d4503ca48a013775))
* **Reddit:** Add `Download location` patch ([#3870](https://github.com/MorpheApp/morphe-patches/issues/3870)) ([7d0f9b6](https://github.com/MorpheApp/morphe-patches/commit/7d0f9b67193372a92e7065f5fa4f4e366b2ba41c))
* **Reddit:** Add `Redgifs audio` patch ([#3714](https://github.com/MorpheApp/morphe-patches/issues/3714)) ([b664711](https://github.com/MorpheApp/morphe-patches/commit/b66471189b52974ead5666ac033b6b2ec867de2e))
* **Reddit:** Add `Remember collapsed comments` patch ([#3517](https://github.com/MorpheApp/morphe-patches/issues/3517)) ([fbd5a82](https://github.com/MorpheApp/morphe-patches/commit/fbd5a82666abeeabd6c7aeb19b7ca993b1ba85c6))
* **Reddit:** Add `Show flairs in home feed` patch ([#3260](https://github.com/MorpheApp/morphe-patches/issues/3260)) ([93501dd](https://github.com/MorpheApp/morphe-patches/commit/93501dd4b31a103c37509b1c26f7644ca9082aff))
* **Reddit:** Add media viewer and feed media patches ([#3516](https://github.com/MorpheApp/morphe-patches/issues/3516)) ([1e905b5](https://github.com/MorpheApp/morphe-patches/commit/1e905b5449e6a5468a02f017ce4afb336e8f668e))
* **Spoof video streams:** Offer to fix playback when PotHelper no longer works or the default client keeps failing ([#3659](https://github.com/MorpheApp/morphe-patches/issues/3659)) ([f996510](https://github.com/MorpheApp/morphe-patches/commit/f996510cfdc71a78c5c9579efcf7d604e70ae1ea))
* Update to Patcher 2.0 ([#3945](https://github.com/MorpheApp/morphe-patches/issues/3945)) ([d7c25c2](https://github.com/MorpheApp/morphe-patches/commit/d7c25c26031e77c051973fb71b761fa991ee7ddb))
* **YouTube - Add to queue:** Add Premium-style queue setting ([#3582](https://github.com/MorpheApp/morphe-patches/issues/3582)) ([1b1b2bc](https://github.com/MorpheApp/morphe-patches/commit/1b1b2bc74bb49c0553225fc7b691c55fbc961a69))
* **YouTube - Captions:** Add "Show captions in picture-in-picture" setting ([#3907](https://github.com/MorpheApp/morphe-patches/issues/3907)) ([6c817e7](https://github.com/MorpheApp/morphe-patches/commit/6c817e7daa49a1b0bf007f31fc7eece9ff3af566))
* **YouTube - Captions:** Add additional automatic translation languages ([#3754](https://github.com/MorpheApp/morphe-patches/issues/3754)) ([c036e5f](https://github.com/MorpheApp/morphe-patches/commit/c036e5f2e30b467a7c2e3af3ae948c0715efec48))
* **YouTube - Channel search:** Added loading animation during searching ([d3fc642](https://github.com/MorpheApp/morphe-patches/commit/d3fc6421ca3f8e7ac6cc162d1a51b24c4b087e6e))
* **YouTube - Disable video codecs:** Add "Force VP9 codec" setting ([#3578](https://github.com/MorpheApp/morphe-patches/issues/3578)) ([e1398ca](https://github.com/MorpheApp/morphe-patches/commit/e1398ca7da9dc7829aa8e9d2f798206fff26c1f6))
* **YouTube - Downloads:** Add "Download in-app" setting ([#3905](https://github.com/MorpheApp/morphe-patches/issues/3905)) ([ef266aa](https://github.com/MorpheApp/morphe-patches/commit/ef266aa4bf94bf63e5b85a31673c297bf0ef81ef))
* **YouTube - Force animations:** Expand the content below the player with its animation when it loads ([b0020b2](https://github.com/MorpheApp/morphe-patches/commit/b0020b2513fffb6954c5925af3213958b947f94f))
* **YouTube - Hide layout components:** Add "Hide 'No comments yet' message" setting ([#3819](https://github.com/MorpheApp/morphe-patches/issues/3819)) ([32168f9](https://github.com/MorpheApp/morphe-patches/commit/32168f9ebff2269c98ea5d9adedda07394342ab9))
* **YouTube - Hide layout components:** Add "Hide live chat scroll to bottom button" setting ([#3826](https://github.com/MorpheApp/morphe-patches/issues/3826)) ([1956988](https://github.com/MorpheApp/morphe-patches/commit/19569880caabbaed642ce9c48e829d22141405dd))
* **YouTube - Hide status bar:** Add "Fix status bar covering the top bars" setting ([caa1be0](https://github.com/MorpheApp/morphe-patches/commit/caa1be0fe5faf3351fa49a02667f03ef4946b34f))
* **YouTube - Player icon style:** Add Series tracker button icons ([179ff66](https://github.com/MorpheApp/morphe-patches/commit/179ff663d36806e11bd3869df8d1a66287072a7f))
* **YouTube - Restore original titles:** Restore titles of watch history and fullscreen suggested videos ([f55e541](https://github.com/MorpheApp/morphe-patches/commit/f55e54163bd04b7b6fdd3e015951ad6bf4f8d42f))
* **YouTube - Return YouTube Dislike:** Add "Show feed thumbnail like count" setting ([#3786](https://github.com/MorpheApp/morphe-patches/issues/3786)) ([7b2fd85](https://github.com/MorpheApp/morphe-patches/commit/7b2fd85413a12a955dfcd8ff9928790c2ac993e8))
* **YouTube - Series tracking:** Add "Show Series in navigation bar" setting ([#3814](https://github.com/MorpheApp/morphe-patches/issues/3814)) ([abaca95](https://github.com/MorpheApp/morphe-patches/commit/abaca951b67eeae3dd9f1a9bc8f9c09e72b7c20b))
* **YouTube Music - Android Auto:** Add Home, Library, and search features ([#3852](https://github.com/MorpheApp/morphe-patches/issues/3852)) ([65e200f](https://github.com/MorpheApp/morphe-patches/commit/65e200f623efc8b651a338360555884b717e05af))
* **YouTube Music - Third-party lyrics:** Add new providers ([#3717](https://github.com/MorpheApp/morphe-patches/issues/3717)) ([89e31ba](https://github.com/MorpheApp/morphe-patches/commit/89e31ba6d69e26a08b5bdd97b3afb4daa927048f))
* **YouTube Music - Third-party lyrics:** Custom romanization target ([#3750](https://github.com/MorpheApp/morphe-patches/issues/3750)) ([0dfc834](https://github.com/MorpheApp/morphe-patches/commit/0dfc8347118bb9c10e8dd8275996d31afb5f5d37))
* **YouTube Music - Third-party lyrics:** Local romanization and alignment ([#3851](https://github.com/MorpheApp/morphe-patches/issues/3851)) ([9adcefd](https://github.com/MorpheApp/morphe-patches/commit/9adcefda0e18fb08a5e70933f243cdbc1d99e502))
* **YouTube Music:** Add `Custom font` patch ([#3718](https://github.com/MorpheApp/morphe-patches/issues/3718)) ([30a4b85](https://github.com/MorpheApp/morphe-patches/commit/30a4b85885e96aa8216f2b9fb26ed0ba4951e8fe))
* **YouTube:** Add "Force animations" patch, superseding the Miniplayer watch transition fix ([#3872](https://github.com/MorpheApp/morphe-patches/issues/3872)) ([591ad8b](https://github.com/MorpheApp/morphe-patches/commit/591ad8bd917bc168b0144014022438e395624bef))
* **YouTube:** Add `Ask flyout menu` patch ([#3897](https://github.com/MorpheApp/morphe-patches/issues/3897)) ([04c76d0](https://github.com/MorpheApp/morphe-patches/commit/04c76d0ace8e3e5c6d4e4d015e7bc231199b9c02))
* **YouTube:** Add `Custom font` patch ([#3673](https://github.com/MorpheApp/morphe-patches/issues/3673)) ([fc8c837](https://github.com/MorpheApp/morphe-patches/commit/fc8c837390b05edbc5262ea786d1308729e80c24))
* **YouTube:** Add `Feed video actions` patch ([#3758](https://github.com/MorpheApp/morphe-patches/issues/3758)) ([b263c08](https://github.com/MorpheApp/morphe-patches/commit/b263c08af15eb0a72f6ea707bd49597d95209d29))
* **YouTube:** Add `Feed view count` patch ([#3862](https://github.com/MorpheApp/morphe-patches/issues/3862)) ([cf0ce16](https://github.com/MorpheApp/morphe-patches/commit/cf0ce16d8304c31ca7a89e730c09debe07a67390))
* **YouTube:** Add `Series tracking` patch ([#3114](https://github.com/MorpheApp/morphe-patches/issues/3114)) ([d98558f](https://github.com/MorpheApp/morphe-patches/commit/d98558fde76a7d2f49579a9f794423cd765211c9))
* **YouTube:** Add `Video delay` patch ([#3867](https://github.com/MorpheApp/morphe-patches/issues/3867)) ([ec246e2](https://github.com/MorpheApp/morphe-patches/commit/ec246e292e6c7c18373bb486a53c3db205efb83f))
* **YouTube:** Add playback speed for Shorts and skip live Shorts ([#3847](https://github.com/MorpheApp/morphe-patches/issues/3847)) ([3731d97](https://github.com/MorpheApp/morphe-patches/commit/3731d97f6ec4eaedbccaa7b7e8d4775c8cf9d587))
* **YouTube:** Added new feed card layout ([#3768](https://github.com/MorpheApp/morphe-patches/issues/3768)) ([02a4c3d](https://github.com/MorpheApp/morphe-patches/commit/02a4c3d36745f133bfae4983aa615984970631a2))
* **YouTube:** Added new feed cards layout without action buttons ([#3769](https://github.com/MorpheApp/morphe-patches/issues/3769)) ([096b0bb](https://github.com/MorpheApp/morphe-patches/commit/096b0bb3e7a98e00ba56ce3dc4260c0b7106e905))

### 🚀 Updated App Support

* **Reddit:** Add experimental support for `2026.42.0` ([1302ae1](https://github.com/MorpheApp/morphe-patches/commit/1302ae1d890588d388b18d0c1cd54313689a2ea7))
* **YouTube Music:** Add experimental support for `9.41.52` ([003a445](https://github.com/MorpheApp/morphe-patches/commit/003a445df12a25f0970a6060853d12ccfbcae7b1))
* **YouTube:** Add experimental support for `21.41.525` ([#3658](https://github.com/MorpheApp/morphe-patches/issues/3658)) ([95eb1fb](https://github.com/MorpheApp/morphe-patches/commit/95eb1fbabe8bdb6251c20b962142cd4daefc1e47))
* **YouTube:** Add experimental support for `21.42.240` ([463a4ba](https://github.com/MorpheApp/morphe-patches/commit/463a4ba0a33cdc72111bf3a5d2d4698d1d3c6bf5))

Patches: rushiranpise/morphe-patches/patches-1.23.0.mpp  
[Changelog](https://github.com/rushiranpise/morphe-patches/releases/tag/v1.23.0)

## [1.23.0](https://github.com/rushiranpise/morphe-patches/compare/v1.22.0...v1.23.0) (2026-10-14)

### 🐛 Bug Fixes

* remove Relane patches ([29819ed](https://github.com/rushiranpise/morphe-patches/commit/29819edeab47def853a57a52a5b5fd6f5db6dbdc)), closes [#1033](https://github.com/rushiranpise/morphe-patches/issues/1033)
* update verified app versions ([5ca039c](https://github.com/rushiranpise/morphe-patches/commit/5ca039c16f9d766678d5c697d6dee6cd19f67f7a))

### ✨ New Features

* **life360:** add themed icon patch with adaptive support ([83226e3](https://github.com/rushiranpise/morphe-patches/commit/83226e3034b86e8923915cf09831ad394d291d19))

Patches: SysAdminDoc/hushfeed/patches-0.77.0.mpp  
[Changelog](https://github.com/SysAdminDoc/hushfeed/releases/tag/v0.77.0)

Hushfeed v0.77.0 has 136 patches for global TikTok 47.4.3 (`com.zhiliaoapp.musically`), and 90 of them work on PineDrama 47.4.3 too. It needs Morphe Manager 1.34.0 or newer, since it's built on patcher 1.15.1.

TikTok stays on 47.4.3, so the APK you patched last time is still the one to use. PineDrama moves up to 47.4.3 and its old 47.1.4 build is dropped. Most of this release fixes things 47.4.3 broke, like the Inbox switches and the faded video controls. New switches cover a glass look for the floating bar, caption height and boldness, subscriber-only videos and dark LIVE panels.

Here's every report this release changed something for, and what changed.

For bug reports

* TikTok links opened from Telegram (#227). TikTok now opens as its own app, so going back or swiping TikTok away leaves Telegram alone.
* Video controls that wouldn't fade (#209). `Fade the video controls`, Clear display's fade level and `Burn-in guard`'s dimming reach the right column on 47.4.3 again, and a copy made with `Run beside the store app` gets its tweaks back.
* Two overlapping buttons (#221). The back arrow is gone from the Inbox header, and the Inbox switches reach their rows again.
* Error while patching (#220). Patching needs far less memory at `Turn off haptics` and the privacy patches.
* Overlaps with the comment bar hidden (#153). A post opened from a sound's page stays above TikTok's red `Use sound` bar.
* Missing live streams (#212). `Filter the LIVE feed` leaves the LIVE rows in your Inbox and on the Following tab alone.
* Crash on the gallery icon in comments (#211). `Remove content credential and card scanner assets` no longer takes TikTok down there.
* Stickers and PineDrama links with the SIM override (#214, #215). New `Keep the For You feed on your real SIM` switch keeps your override for the rest of TikTok while For You gets your real SIM.
* Downloads behind a proxy app (#145). Saving works again with Clash, mihomo, sing-box or Xray in fake-IP mode.
* The button in the top left corner (#128). `Hide the side menu button` works on accounts where TikTok builds the top bar from its server rules.

For requests

* PineDrama (#156). It moves to 47.4.3 with the same 90 patches.
* Liquid glass (#218, #124). New `Liquid glass look` switch under `Floating bottom bar`.
* Voice tools (#213). New `Remove voice tools` patch, off unless you pick it, saves about 16 MB.
* Seekbar on sensitive videos (#208). `Show the progress bar` covers videos behind a sensitive content warning.
* Device system font (#7). `Use system font` and `Use an imported font` reach TikTok's in-app web pages like Activity center and Watch history.
* AMOLED for lives (#159). New `Dark LIVE panels in dark mode` switch under Playback.
* Sub-only content (#219). New `Hide subscriber-only videos` switch under Feed filter.
* Subtitle height and boldness (#206). Three `Caption height` rows and a `Caption boldness` picker, from OmerKurdi79's branch.
* Double tap and long press (#136). Both can now turn Clear display on or off.

## What's changed

* PineDrama moves to 47.4.3, the build APKMirror got on 2026-10-19, and 47.1.4 is dropped. The same 90 patches apply to it (#156).
* A TikTok link tapped in Telegram now opens TikTok as its own app instead of inside Telegram. The two used to share one card in Recents, so going back or swiping TikTok away closed Telegram too. Other apps that open links the same way get the same fix, and links from your browser open as they always did (#227).
* `Fade the video controls` reaches the avatar, like, comment, save and share buttons on TikTok 47.4.3 again, and Clear display with a fade level keeps them in sight at that level. On 47.4.3 Hushfeed looked for that column under the name of a thin strip at the top of the video, so the buttons stayed at full strength and a faded Clear display let TikTok take them all away. `Hide the right column` and `Burn-in guard`'s dimming reach the column again too (#209).
* The Inbox switches work on TikTok 47.4.3 again, and the back arrow no longer shows on top of the add people icon. Hushfeed took the Inbox header for the list on 47.4.3, so it treated the header's icons as rows and showed the arrow TikTok keeps hidden there, while `Hide archive`, `Hide conversations` and the other row switches never reached a row. Turning off `Hide the add people icon`, `Hide the Inbox search button` or `Hide activity status` now only brings back what it hid, and leaves alone a header icon TikTok hides on its own (#221).
* Patching needs far less memory at `Turn off haptics`, `Allow screenshots and Circle to Search` and the privacy patches. Finding TikTok's haptic calls used to make a record for every method that touched a view, about 700 MB of allocations on 47.4.3, and patching ran out of memory there with a smaller heap. The calls are now looked up by name, which takes about 20 MB (#220).
* With `Hide the comment bar on opened videos` on, a video or photo you open from a sound's page keeps its spot above TikTok's red `Use sound` bar. The post used to stretch down under that bar, so the bar covered the end of the caption, See translation, the progress bar and the time (#153).
* New `Liquid glass look` switch under `Floating bottom bar` draws the floating tab pill as glass. It's lighter and more see-through than the plain dark pill, brightens toward the top, and has a bright rim along its top edge where the light catches it. The tabs stay exactly where they were (#218, #124).
* New `Remove voice tools` patch, off unless you pick it, removes TikTok's speech recognition files and saves about 16 MB. With it in, voice search, naming a song by listening, talking to TikTok's AI assistant and TikTok's music check on videos you post all stop working (#213).
* A new Region switch, `Keep the For You feed on your real SIM`, keeps the SIM you set in `Override SIM details` for sticker search, PineDrama's episodes and the rest of TikTok, while each For You request goes out with your phone's own SIM country, operator code and carrier. With `Match locale and timezone` on, For You also gets your phone's real locale country and time zone back. TikTok reads the SIM once as it starts and uses that one answer for its feature checks and its feed alike, so the For You request is where the two can be told apart. The row needs the Region spoof patch in your bundle next to SIM spoof (#214, #215).
* `Filter the LIVE feed` leaves the LIVE row in your Inbox and the Following tab's LIVE row alone, apart from blocked creators. TikTok fills those rows through the same page handler as the LIVE feed, so the viewers, followers, gaming and category rules were thinning out the creators you follow too (#212).
* A copy made with `Run beside the store app` gets its bottom navigation, share sheet and video control tweaks back. The renamed copy didn't count as TikTok, so every view name written for 47.4.3 came up missing in it (#209).
* `Remove content credential and card scanner assets` no longer crashes TikTok when you tap the gallery icon while replying to a comment. The photo picker started TikTok's content credential service, which loaded the emptied library and took the app down into safe mode. The service now stays unstarted, and a photo you pick carries no content credential (#211).
* `Show the progress bar` also shows the bar on videos that open behind a sensitive content warning. TikTok kept treating them as covered after you tapped through, so the bar stayed off on those videos even with the switch on (#208).
* `Use system font` and `Use an imported font` now reach Activity center, Watch history, Comment history and TikTok's other web pages. Those screens are web pages inside the app, so they kept TikTok's font. Websites you open in TikTok's browser keep their own fonts. An imported font over 2 MB shows up there as your phone's font instead (#7).
* Hushfeed's downloads work again behind a proxy app running in fake-IP mode, the way Clash, mihomo, sing-box and Xray often run. Those apps answer TikTok's video and photo servers with stand-in addresses from 198.18.0.0/15 or fc00::/18, and Hushfeed turned every save down as a local address, while TikTok's own save still worked (#145).
* Holding a verified account's profile picture saves it again. TikTok 47.4.3 puts the blue check inside the @handle's text, so Hushfeed read the handle as somebody else's and asked you to open the profile again every time.
* `Hide suggested accounts` also takes away the "Suggested accounts" title on Profile > Find people. The suggestions under it were already hidden, so the title sat over an empty list.
* New `Dark LIVE panels in dark mode` switch under Hushfeed settings > Playback opens a LIVE room's panels dark while TikTok is in dark mode. TikTok kept the share menu, the fan club sheet and a host's profile card white even in a dark app, so they lit up over the stream. The daily ranking and TikTok's web sheets, like viewer rankings and a shop's Top customers, keep TikTok's own look, and light mode doesn't change (#159).
* `Hide the side menu button` takes the button away on accounts where TikTok builds the top bar from its own server rules. TikTok never asked whether the button should show there, so it stayed next to LIVE with the switch on (#128).
* `Hide comment box buttons` also takes the photo, @ and gift buttons out of the row over the keyboard. On 47.4.3 that row is built apart from the "Add comment..." bar, so they came back as soon as you started typing, and the photo button's empty spot stayed even after it went. The gift tile in that row's "+" panel goes too, and "+" itself goes when nothing's left in it.
* Turning `Hide comment box buttons` off brings the photo and @ buttons back right away. TikTok keeps the comment box around between videos, so they stayed hidden on every video until you restarted the app.
* Account facts shows an account's language again on TikTok 47.4.3. TikTok stopped sending the join date, region and language with the profile itself, so every line said Not sent. The language now comes from the account's own videos on the profile, and the join date and region do too whenever TikTok sends them there.
* `Copy the full link for short links` stops waiting as soon as you share to another app. When you picked More and then used Copy in Android's own share sheet, Hushfeed read that link once TikTok was back in front and swapped it, and Android showed its "Hushfeed pasted from your clipboard" notice. TikTok's own Copy link still gets the full link.
* With `Show the time zone` on, a language that has no short name for your zone writes it as "GMT-4" instead of "GMT-04:00". The longer form pushed the creator's name off the row in Italian on a narrow phone and cut the time short.
* Hushfeed settings search results show a setting's new value when you change it from a result and come back. They used to keep the old one, so `Caption background` still read Dark after you'd picked TikTok default.
* The Likes field in `Own profile counts` is translated now. It was the only English word in that editor on a phone set to another language.
* `Undo last restore or reset` in Hushfeed settings also gives the Feature Gate Lab its own Undo back. A restore that carried Lab rules threw that away, so after undoing the restore you couldn't take back the Lab change you'd made just before it.
* Tests now run a whole `Save videos without sound` save of a DASH video against a stand-in server. The saved file has to be TikTok's picture stream exactly as it arrived, with no sound track, the same rotation and length, and nothing left behind in the cache.
* New `Hide subscriber-only videos` switch under Feed filter. It hides the posts only a creator's subscribers can watch, the ones with a lock on them, from the feed, search and profile grids. A creator on your exceptions list keeps theirs, and your own posts always stay (#219).
* Three new `Caption height` rows under Captions lift spoken captions higher, up to 300 dp: one while the phone is upright, one while it's sideways, and one for the line `Keep captions in Clear display` leaves on screen. Each only moves its own caption, and 0 puts it back exactly where TikTok had it. `Caption boldness` replaces the `Normal-weight captions` switch with seven choices from Light to Extra bold, and reaches the kept Clear display line too. If you had the old switch on, it comes back as Normal, from a settings backup as well. Thanks to OmerKurdi79, whose branch these come from (#206).
* Double tap and Long press have a new choice, `Turn Clear display on or off`. It hides the buttons over the video the way TikTok's own Clear display does, and the same gesture brings them back without a like. It needs the `Remember clear display` patch, which keeps it on as you swipe, the same as after TikTok's own button (#136).
* `Hide the Tako bubble` also takes TikTok's AI answer card out of search results. That's the "TikTok Tako · AI summary from" card that answers a search typed as a question, above the videos. The rest of the results move up where it was.

## Update

Refresh the Hushfeed source in Morphe Manager 1.34.0 or newer and patch TikTok again. Keep the manager's existing signing key so your login and settings carry over. The .mpp is a patch bundle, not a TikTok APK.

## Checked

* This exact bundle was patched onto TikTok 47.4.3 and run on a phone. It opened to a signed-in For You feed, and Hushfeed settings opened with no crash.
* On a phone with TikTok 47.4.3, a TikTok link tapped in Telegram opened in TikTok's own task whether TikTok was closed or already running, and a link from Chrome opened the way it always has (#227).
* Also on that phone, `Fade the video controls` reached the right column again and dimmed it after 5 seconds (#209), and a `Run beside the store app` copy found all 29 screen areas Hushfeed looks for (#209). The Inbox header lost its stray back arrow and the row switches reached the rows (#221), and a video opened from a sound's page stopped above the red `Use sound` bar (#153). The gallery icon in a comment reply opened the photo picker with no crash (#211), holding a verified account's profile picture saved it, and the font switches reached TikTok's web pages (#7).
* With TikTok set to its own dark theme and `Dark LIVE panels in dark mode` on, a LIVE room's share menu opened dark and the daily ranking kept TikTok's look (#159). PineDrama 47.4.3 took its patches and opened.
* Every patch applied to 47.4.3 with Java held to a 1 GB heap (#220).
* On a signed-in emulator, `Filter the LIVE feed` kept a followed creator's LIVE row in the Inbox (#212), saves went through behind sing-box in fake-IP mode (#145), and Hushfeed settings search showed a setting's new value after a change.

Patches: SysAdminDoc/HushPinterest/patches-0.0.12.mpp  
[Changelog](https://github.com/SysAdminDoc/HushPinterest/releases/tag/v0.0.12)

HushPinterest 0.0.12 has 32 patches for Pinterest 14.41.0. It's built on Morphe patcher 1.15.1, so it needs Morphe Manager 1.34.0 or newer. This one moves to Pinterest's newest version and adds a lot of new switches, every one of them off until you turn it on. Filter feed can hide video pins and pins with words you mute. Keep Home feed stops Home from reloading on its own when you come back to it, and Show posted date puts the day a pin went up under its title. Download pins can copy or share the picture itself now, and its rows show in the full-screen pin menu too. Downloads also stopped settling for the smaller copy now and then.

It's a new Pinterest version. So far APKMirror only has 14.41.0 as an arm64 bundle (`.apkm`) for Android 12L or newer, and Manager merges it before patching. Patch it with the same signing key you used before and install it over your current HushPinterest, and your settings stay as they are. On a phone older than Android 12L, keep 0.0.11 and Pinterest 14.40.0 for now.

## What's new

- The patches now target Pinterest 14.41.0, the newest stable release. 14.40.0 is no longer supported. So far APKMirror has 14.41.0 only as an arm64 bundle (`.apkm`) for Android 12L or newer, and Manager merges it before patching.
- Download pin now shows in the full-screen pin menu some accounts get from the three dots on a pin, along with the other Hush rows, and Pinterest's own Download row in that menu gives way to it. Before, only the smaller pop-up menu had them.
- Download pins has a new switch, Copy image, that starts off. It adds a Copy image row under Download pin, in the small pin menu and in the full-screen one, and puts the full-size picture on the clipboard so you can paste it into a chat or a notes app. Video pins don't get the row. If the picture is too big, isn't really an image, or takes too long, you're told so and your clipboard stays as it was. (#11)
- Download pins also has Share image, another switch that starts off. Its row sits under Copy image and opens Android's share menu with the full-size picture itself rather than a link, so the app you pick gets the image. Video pins don't get it, and if the picture can't be fetched you get a short note instead of the share menu. (#11)
- Long-press download has three new switches on the Pin actions page: Hide Save, Hide Send and Hide Search image in the long-press menu. Each takes that one Pinterest button out of the round menu you get by holding a pin in a grid, and the pin itself still saves, shares and searches as before. They work with Download off too. If everything would be hidden and Download is off, the menu stays Pinterest's own rather than opening empty. All three start off. (#11)
- Black comments now covers the strip under the status bar too. On 14.41.0 the comments fill the whole screen, and that strip stayed dark gray above the black list on photo and video pins alike.
- Downloads no longer save the smaller copy now and then when the original is there. Finding the original asks Pinterest's media server a few quick questions, and one asked just as both lookup helpers were wrapping up the last was turned away, so the download settled for the size the feed showed. It now waits a moment for a helper to come free.
- Copy media link no longer overwrites something you copied after it. When a pin shows only a smaller size, the link to that size goes on the clipboard right away, and it becomes the original's link once Pinterest's media server answers, but only if the clipboard still holds that copy. Before, nothing was copied until the answer came, and a slow answer could replace whatever you'd copied in the meantime.
- Save list no longer hangs when the app holding the picked file stops answering. Each save gets 30 seconds in all, then you're told to check the file, and a late answer from that app doesn't add another message or remove anything. While that app is still busy, a new list says to try later instead of opening a picker. Everything that talks to the file's app now runs on its own helper, never on the screen's thread, including the clean-up after a list that couldn't be written while HushPinterest was paused.
- A list that isn't written no longer deletes an empty file you picked to write over. Only an empty file made since the picker opened gets removed. Any other file is left where it is, and you're told so.
- Save list leaves out a source link that hides a session code behind an encoded `;` (`%3B`, that encoded again, or a longer spelling some servers still read as `;`), the way it already left out a plain `;jsessionid=`. The pin's ID, title and Pinterest link still go in. Ordinary encoded spaces and accented letters stay exactly as given.
- Queue selected and Queue pins stay off until something chosen can actually be saved. A pin with no picture address, or a video Pinterest only streams, doesn't turn them on anymore, though Save list still takes those pins. A mix still queues what it can and counts the rest as unsupported.
- Morphe Manager lists every change of the release your Pinterest was patched with, not just a short summary. For that one release Manager shows the patch bundle's description instead of this changelog, and the description was one paragraph while every older release listed its changes. It now goes on with the release's changes after the summary, starting with this one.
- Hide comments has a second switch, Hide suggested replies, for the row of ready-made replies like "Yum!" and "Came out great!" next to the comment box. You can still write your own comment. It starts off, and the two switches don't turn each other on. (#14)
- Hide AI-labeled pins has a second switch, Hide pins that say they're AI, for AI pins Pinterest doesn't label. It takes a pin whose title or description says something like "AI art", "AI generated", #aiart, "made with AI", Midjourney, Stable Diffusion or PixAI, and pins from sites that only host AI images, like pixai.art and Civitai. It goes by the pin's own words, so a pin that just says "AI" stays, and names like Ai Weiwei or the Portuguese "aí" are left alone. Boards named that way stay too. It starts off, and diagnostics count these pins apart from the labeled ones.
- Hide closeup buttons has a third switch, Hide Search image label on pins. Pinterest puts a "Search image" label on the lens button for your first two pins each day, and with this on the lens shows without it, the way it looks from the third pin on. Tapping the lens still searches. It starts off and sits under Hide lens button on the Interface page. (#13)
- New Filter feed patch, with a Hide video pins switch on the Feed page. It takes pins that play a video out of your home feed, search, related pins and boards, idea pins with video included. Photos and GIFs stay. It starts off.
- Filter feed also has Muted words, a row on the Feed page where you type words and phrases you don't want to see. A pin whose title or description has one of them leaves the same lists. Capitals don't matter and only whole words count, so "cake" takes out "Wedding Cake Ideas" but not cupcakes. The list holds 50 entries of up to 40 characters, starts empty, and goes into settings files with your switches. Boards named after a muted word stay.
- New Keep Home feed patch, with its switch on the Feed page. Pinterest reloads Home with new pins on its own when you come back after five minutes or more, when you pick the Home tab again after a while and when you back out of a search, and the pin you were about to open is gone. With this on, Home stays where you left it. Pull down whenever you want new pins. The new pins prompt, a second tap on the Home tab and a pin you open from a notification still load as before. It starts off.
- New Show posted date patch, with its switch on the Interface page. Pinterest sends the day each pin was posted but never shows it, and with this on you see "Posted" and that day under the title when you open a pin. A pin without a date just doesn't get the line. The date follows the language HushPinterest shows and your phone's time zone. It starts off and shows from the next pin you open. (#11)
- With Debug logging on, the line for a kept pin also says whether Pinterest marked it as a repin or as saved to one of your boards. It shows only that the field is set, never which board.
- The Feed page has a new row under the AI switches, Pinterest's own AI setting. It opens the page where Pinterest lets you see fewer AI pins among the ones it picks for you, since neither that page nor the switches catch every AI pin alone. It's there whenever Hide AI-labeled pins is patched in.

## Behind the scenes

- The pin model fixture test also checks the fields Hide video pins reads, the two inside Pinterest's video and idea pin models included, and the grid title that the AI words and video filters use to tell a pin from other models.
- The pre-push and release checks take a declared build kept as APKMirror's `.apkm` bundle, since that's the only way 14.41.0 ships. The bug report form's example names a bundle too, and the release step keeps whatever kind of file the form names.
- The release gate's advisory check works in Windows PowerShell 5.1 again. Since 0.0.11, any failed OSV request stopped it there with an "Unable to find type" error. A dropped connection or a busy server now gets asked again in 5.1, the way it already did in PowerShell 7.
- The README's Help now goes through why Android might refuse the install. It says where Manager keeps its signing key, so an update that won't go over your patched copy can be fixed without losing your settings. It also covers stock Pinterest and the unknown apps prompt.
- The README sends people on v0.0.11 to Pinterest 14.40.0 again, the build that release patches, and names 14.41.0 as the next release's build. It had pointed them at 14.41.0, which v0.0.11 refuses. The release's prepare step now stops while the README still names a next release, so it gets rewritten for the new build before a release is cut.
- The patch verifier checks how the long-press hide switches tell Pinterest's buttons apart. The sorter has to read the held button's own id and send Save, Send and both search ids to the right answer, with the ids found the way the patch finds them, and a build without them has to keep the plain answer.
- The bug report form lists Filter feed among the patches you can tick. It was the one patch the form left out, and the release check stopped on that.
- The release check and the publish step leave a GitHub description alone when it names no version, patch count or Pinterest build, since there's nothing in it to go stale. One that names any of them still has to match the release. This release would have stopped on the shorter description the repository uses now.
- The source census reads Jman's bundle registry again. On October 14 the registry took down the files the audit read and now serves the same list from its own site, so every audit since stopped on a missing file. It reads all of the site's pages, not only the first hundred releases.
- The device scripts write their lease times in UTC with a `Z` at the end. They used `+00:00`, and the other tools sharing the test phone took a lease written that way as already expired. They also read a `Z` time as UTC now. Before, a busy phone's expiry was read as local clock time, so an expired lease looked hours from ending.
- The script tests now clean up after themselves. The pre-push cases remove the worktree the hook builds in, and a passing host reference run deletes its report folder. Each run used to leave both in the temp directory.

## Install

1. Install [Morphe Manager](https://github.com/MorpheApp/morphe-manager) 1.34.0 or newer.
2. Add HushPinterest as a patch source: https://morphe.software/add-source?github=SysAdminDoc%2FHushPinterest
3. Download Pinterest 14.41.0, version code `14418010`. APKMirror has it as an arm64-v8a bundle (`.apkm`) for Android 12L or newer. Pick that file in Manager and it merges the parts before patching.
4. Uninstall the stock Pinterest first, since Android won't put one over the other. Save anything you keep only on the phone before you do. Your boards and pins come back when you sign in.
5. Sign in with your email and a Pinterest password. If you joined through Google or Facebook, tap `Forgot your password?` on Pinterest's login page to set one first.
6. Right after your first patch, export Morphe Manager's signing key (Settings, then System, then Import & export, then Signing key) and keep it somewhere private. Updates only install over a Pinterest signed with that same key.

Already on HushPinterest? Skip steps 4 and 5. Patch 14.41.0 with the same key and install it over the one you have.

The `.mpp` download is a patch bundle, not a Pinterest APK. [Installation instructions](https://github.com/SysAdminDoc/HushPinterest#install). `SHA256SUMS.txt` is signed with the HushPinterest release key, fingerprint `FCE5 ECE3 182A 647B 3AF2  C5ED 2DC3 5E8D 5C00 E8A6`. [How to check a download](https://github.com/SysAdminDoc/HushPinterest#verify-a-release-download).

## Reported issues

- #2: Download pin now shows in the full-screen pin menu some accounts get from a pin's three dots, so it's there whichever menu Pinterest gives you.
- #11: Copy image and Share image under Download pin, the three long-press hide switches and Show posted date all came from this one.
- #12: Black comments covers the gray strip under the status bar now, on photo and video pins.
- #13: There's a new switch, Hide Search image label on pins, that takes the label off the lens button.
- #14: Hide suggested replies takes away the row of ready-made replies next to the comment box.

## Validation

All 232 patch tests and 1067 extension tests passed on this commit, none skipped. The bundle attached here was patched onto a real Pinterest 14.41.0 bundle from APKMirror with Morphe's desktop patcher, and all 32 patches applied without forcing. `release-receipt-0.0.12.json` records that result, the bundle's hash and what patching changed in the app's manifest.

Before release, these patches went on a signed-in phone running Pinterest 14.41.0, installed over 0.0.11 with the same key, so the sign-in and settings carried over. The new switches were tried there one at a time: Filter feed, Keep Home feed, Show posted date, Copy and Share image, the long-press hides, Hide suggested replies, Hide pins that say they're AI and the full-screen menu's Download rows. Black comments left no gray strip under the status bar, and Black bottom bar and Black pin menu stayed black on the new version. Copy media link put the smaller size's link on the clipboard right away and swapped in the original's once Pinterest answered. Queue selected stayed off until a pin was picked, Save list wrote its file, and the Feed page's new row opened Pinterest's own AI setting.

The Search image label switch is covered by tests but wasn't seen on the phone, since Pinterest only shows that label on the first two pins each day. Copy media link leaving a newer copy alone and Save list's 30 second limit are covered by tests too.  

Skipped:  
Patches: kveld9/kveld-extra-morphe-patches/patches-1.26.0.mpp    
