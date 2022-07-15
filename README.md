# Common Emulator Development Bugs

This list is intended to help emulator devlopers share knowledge of bugs they encountered during development. Please add any entries that you think would be helpful :)

### Game Boy Advance
| Title | Bug Description | Image (Optional) | Context/Solution |
| - | - | - | - |
| 007 - Everything or Nothing (USA, Europe) | No music or sound during gameplay | | https://github.com/nba-emu/NanoBoyAdvance/issues/96 |
| 007 - NightFire (USA, Europe) (En,Fr,De) | Buzzing sound | | https://github.com/nba-emu/NanoBoyAdvance/issues/97 |
| Acrobat Kid (Japan) | Does not boot (white screen) | | https://github.com/nba-emu/NanoBoyAdvance/issues/92 |
| Acrobat Kid (Japan) | Black line flashing across menu | ![](https://cloud.githubusercontent.com/assets/2506953/26331956/25bdc3b4-3f54-11e7-90a6-922b94133ff0.png) | https://github.com/mgba-emu/mgba/issues/743 |
| Acrobat Kid | Menu blending problems (text is faded) | ![](https://user-images.githubusercontent.com/29958696/103411391-fe031500-4b6f-11eb-9603-3a2284730852.png) | https://github.com/jsmolka/eggvance/issues/9 |
| Advance Guardian Heroes (Europe) | Shadows flicker | | https://github.com/nba-emu/NanoBoyAdvance/issues/95 |
| Alien Hominids | Crashes after logo screen | | https://github.com/DaveTCode/GBADotnet/issues/37 |
| Baldur's Gate: Dark Alliance | Saving does not work | | https://github.com/nba-emu/NanoBoyAdvance/issues/108 |
| Banjo-Kazooie: Grunty's Revenge | Crashes after invalid opcode | ![](https://user-images.githubusercontent.com/47043333/162996614-bce96dfa-63a9-4bdc-82cb-bd2b55e440a4.png) | https://github.com/ITotalJustice/notorious_beeg/issues/44 |
| Beyblade V-Force - Ultimate Blader Jam (USA) | Audio clicks and pops | | https://github.com/nba-emu/NanoBoyAdvance/issues/101 |
| BIOS (Official) | Sounds distorted / metallic | | https://github.com/jsmolka/eggvance/issues/16 |
| Broken Sword: The Shadow of the Templars | Horizontal line through screen | ![](https://user-images.githubusercontent.com/1358414/162592252-e4ae5014-7665-4226-b241-f76f1fde4baa.png) | https://github.com/DaveTCode/GBADotnet/issues/69 |
| Castlevania: Aria of Sorrow | Garbage values when entering the menu | ![](https://user-images.githubusercontent.com/29958696/103435927-52f96680-4c16-11eb-95d7-18516f7616bf.png) | https://github.com/jsmolka/eggvance/issues/11 |
| Celeste | Audio cracking on right side | | https://github.com/jsmolka/eggvance/issues/18 |
| Donkey Kong Country | Background layers are incorrect | ![](https://user-images.githubusercontent.com/1358414/160438533-c2d22c8a-75b9-4fd4-b9d8-6d75d6c91af5.png) | https://github.com/DaveTCode/GBADotnet/issues/46 |
| Dragonball Z - The Legacy of Goku II (Eurasia release) | Hanging during intro | ![](https://user-images.githubusercontent.com/13669774/79025528-54fe2f80-7b86-11ea-9ea2-af252351a2fd.png) | https://github.com/nba-emu/NanoBoyAdvance/issues/83 |
| Golden Sun | Characters render below carpet (OAM priority hijacking) | ![](https://user-images.githubusercontent.com/2696404/82008338-fd7c4380-969e-11ea-9a35-3a5d15caf287.PNG) | https://github.com/nba-emu/NanoBoyAdvance/issues/99 |
| Golden Sun | Characters render below carpet (OAM priority hijacking) | ![](https://user-images.githubusercontent.com/13669774/84211999-f806f300-aabc-11ea-8b2b-931d5795d1a5.png) | https://github.com/jsmolka/eggvance/issues/3 |
| Golden Sun | Resets if any key is pressed | | https://github.com/nba-emu/NanoBoyAdvance/issues/133 |
| Golden Sun | Entering battles and overworld break game | | https://github.com/mattrberry/crab/commit/7444832 |
| Golden Sun | Overworld shakes and flashes wildly | | https://github.com/mattrberry/crab/commit/71131ac |
| Golden Sun | Intro bleep sounds bad | | https://github.com/jsmolka/eggvance/issues/14 |
| Gradius Galaxies | Black screen on boot | ![](https://user-images.githubusercontent.com/1358414/162591803-acefc6a5-29b8-4e27-bab7-f5f8bd6c4615.png) | https://github.com/DaveTCode/GBADotnet/issues/66 |
| Gradius Galaxies | Locks up after start message | | https://github.com/DaveTCode/GBADotnet/issues/82 |
| Gunstar Super Heroes | Layering issue between enemy and icons | ![](https://user-images.githubusercontent.com/2696404/82006731-09fe9d00-969b-11ea-93cf-5dc1c33ea79c.PNG) | https://github.com/nba-emu/NanoBoyAdvance/issues/98 |
| Gunstar Super Heroes | Sprite priority issues | ![](https://user-images.githubusercontent.com/13669774/84210895-3ea71e00-aaba-11ea-93f2-a0e154605e6e.png) | https://github.com/jsmolka/eggvance/issues/2 |
| Final Fantasy VI Advance | Continuous typing sound during intro | | https://github.com/jsmolka/eggvance/issues/15 |
| Fire Emblem | Logo blending is wrong | ![](https://user-images.githubusercontent.com/1358414/163053233-72128388-5f15-4003-97ef-42f830e0980a.png) | https://github.com/DaveTCode/GBADotnet/issues/77 |
| Fire Emblem: The Sacred Stones | Blue line at top of screen in cutscenes | ![](https://user-images.githubusercontent.com/13669774/133418382-d45cbcf2-312f-493c-b909-7addff75e6b4.png) | https://github.com/nba-emu/NanoBoyAdvance/issues/175 |
| Hamtaro Rainbow Rescue | Freezes on Spanish language selection | | https://github.com/nba-emu/NanoBoyAdvance/issues/91 |
| Iridion 3D | Intro line glitches | ![](https://user-images.githubusercontent.com/13669774/133425829-fc5f8176-db4e-4680-88bd-e1c8471b7280.png) | https://github.com/nba-emu/NanoBoyAdvance/issues/176 |
| Kirby: Nightmare in Dream Land | Audio clicks | | https://github.com/mattrberry/crab/commit/6c57508 |
| Lara Croft Tomb Raider - Legends (USA) | Stuck on black screen | | https://github.com/nba-emu/NanoBoyAdvance/issues/183 |
| Mario & Luigi: Superstar Saga | Random hangs in intro and elsewhere | ![](https://user-images.githubusercontent.com/13669774/66221167-bbcdf800-e6ce-11e9-916a-4d1ef3971c55.png) | https://github.com/nba-emu/NanoBoyAdvance/issues/64 |
| Mario & Luigi: Superstar Saga | Text not appearing in the intro | | https://github.com/nba-emu/NanoBoyAdvance/issues/64 |
| Mario & Luigi: Superstar Saga | Random white noise | | https://github.com/jsmolka/eggvance/issues/19 |
| Mario Kart: Super Circuit | Bottom half of screen doesn't render | ![](https://user-images.githubusercontent.com/47043333/163018288-0f72acea-6ac5-41a5-b29d-6bd57b76746d.png) | https://github.com/ITotalJustice/notorious_beeg/issues/45 |
| Mario Kart: Super Circuit | Track doesn't render | ![](https://user-images.githubusercontent.com/1358414/162591717-ef168c25-9cab-497f-b9a8-2f2c3f88944a.png) | https://github.com/DaveTCode/GBADotnet/issues/65 |
| Mario Kart: Super Circuit | Sprites don't render properly on character selection | ![](https://user-images.githubusercontent.com/1358414/162591665-de2e9b8e-ce71-476f-b519-dd5c325af7fd.png) | https://github.com/DaveTCode/GBADotnet/issues/64 |
| Mario Kart: Super Circuit | Track doesn't render properly | ![](https://user-images.githubusercontent.com/1358414/164802235-100832ad-77d2-470b-b55a-e137299d65a7.png) | https://github.com/DaveTCode/GBADotnet/issues/78 |
| Mario Kart: Super Circuit | Track doesn't render properly | | https://github.com/mattrberry/crab/commit/a2ccafe |
| Mario vs. Donkey Kong (USA, Australia) | Sprites glitch near doors or other objects | ![](https://user-images.githubusercontent.com/2696404/82133445-d2b8f900-981e-11ea-80cf-130ce68dcb92.PNG) | https://github.com/nba-emu/NanoBoyAdvance/issues/106 |
| Mega Man Zero (U) | Title cut off on title screen | ![](https://user-images.githubusercontent.com/39786450/172510869-168060f4-c442-436d-8702-936af27cfab9.png) | https://github.com/nba-emu/NanoBoyAdvance/issues/223 |
| Mega Man Zero | No sound | | https://github.com/jsmolka/eggvance/issues/13 |
| Metal Max 2 Kai (Japan) | Flashing text | | https://github.com/nba-emu/NanoBoyAdvance/issues/89 |
| Mother 3 | Softlock when sleeping | ![](https://user-images.githubusercontent.com/29958696/113520158-7de6b400-9591-11eb-9173-2d2efa132ee9.png) | https://github.com/jsmolka/eggvance/issues/20 |
| Mother 3 | White bars in intro don't animate into frame | ![](https://user-images.githubusercontent.com/29958696/115428866-1f613d00-a203-11eb-842f-daaf937a1b25.png) | https://github.com/jsmolka/eggvance/issues/22 |
| OpenLara | Flickers on the bottom half of the screen | | https://github.com/DaveTCode/GBADotnet/issues/29 |
| OpenLara | Flickers on the bottom half of the screen | | https://github.com/mattrberry/crab/issues/4 |
| Phantasy Star | Text and lines flash during intro | | https://github.com/nba-emu/NanoBoyAdvance/issues/109 |
| Phoenix Wright: Ace Attorney | Text missing on second line of NPC dialog | ![](https://user-images.githubusercontent.com/47043333/161538504-55217438-ed2c-4f04-8c5a-bdd8cb427e05.png) | https://github.com/ITotalJustice/notorious_beeg/issues/27 |
| Pinball Tycoon (USA) | Scoreboard doesn't render | ![](https://user-images.githubusercontent.com/2696404/81907935-18957780-95fb-11ea-85c9-36c0b8fdf226.PNG) | https://github.com/nba-emu/NanoBoyAdvance/issues/90 |
| Pinball Tycoon (USA) | Scoreboard renders incorrectly | ![](https://user-images.githubusercontent.com/13669774/133426666-5adbf5fc-fd34-4e16-909c-85c3e934ee89.png) | https://github.com/nba-emu/NanoBoyAdvance/issues/177 |
| Pokémon Emerald | Sprites in title screen are partially rendered | ![](https://user-images.githubusercontent.com/13669774/112904697-98c8ac80-90e9-11eb-9650-f3ec2792a12a.png) | https://github.com/nba-emu/NanoBoyAdvance/issues/146 |
| Pokémon Emerald | Fog and underwater don't blend | ![](https://media.discordapp.net/attachments/465586361731121162/805716419638460426/unknown.png) | https://github.com/mattrberry/crab/commit/805e860 |
| Pokémon Emerald | Improper cloud "wave" effect | ![](https://user-images.githubusercontent.com/22038970/175495377-87d02295-0d2c-4851-ba4a-cdddb7ca1d44.mp4) | https://github.com/paoda/zba/issues/1 |
| Pokémon Emerald | Stripes over logo on title screen | | https://github.com/mattrberry/crab/commit/26b521a |
| Pokémon FireRed | Oak's feet are visible in gender selection screen | ![](https://user-images.githubusercontent.com/1358414/159525196-0870947c-e374-4f6e-88dd-4cdcb8df5f3c.png) | https://github.com/DaveTCode/GBADotnet/issues/20 |
| Pokémon FireRed | Logo is brightened incorrectly | ![](https://user-images.githubusercontent.com/1358414/159719262-c21a6b69-f88e-4c36-b283-50f0645e783e.png) | https://github.com/DaveTCode/GBADotnet/issues/24 |
| Pokémon Pinball: Ruby & Sapphire | Tiles are displayed incorrectly during play | ![](https://user-images.githubusercontent.com/1358414/159676732-1a6664e1-97be-4a7e-8c19-34658b448afd.png) | https://github.com/DaveTCode/GBADotnet/issues/23 |
| Pokémon Pinball: Ruby & Sapphire | Alpha blending is wrong on field select screen | ![](https://user-images.githubusercontent.com/1358414/160607600-ad302756-347b-4341-86f4-d561754f6c52.png) | https://github.com/DaveTCode/GBADotnet/issues/49 |
| Pokémon Ruby | Black lines at top during new game sequence | ![](https://user-images.githubusercontent.com/29958696/103409711-51716500-4b68-11eb-9a69-2ddbe7b0a3b2.png) | https://github.com/jsmolka/eggvance/issues/7 |
| Pokémon Sapphire | Black lines at top during new game sequence | ![](https://user-images.githubusercontent.com/29958696/103409711-51716500-4b68-11eb-9a69-2ddbe7b0a3b2.png) | https://github.com/jsmolka/eggvance/issues/7 |
| Pokémon Sapphire | Hangs at end of intro | ![](https://user-images.githubusercontent.com/13669774/87096772-d7f55b80-c243-11ea-8ab2-69d5eb955bc1.png) | https://github.com/jsmolka/eggvance/issues/4 |
| Racing Gears Advance | Crashes due to undefined instruction during championship load | | https://github.com/DaveTCode/GBADotnet/issues/22 |
| Rhythm Tengoku | Crashes during boot | | https://github.com/DaveTCode/GBADotnet/issues/35 |
| Sennen Kazoku | Freezes before going to the intro | | https://github.com/jsmolka/eggvance/issues/12 |
| Sennen Kazoku | The clock equipment is broken | ![](https://user-images.githubusercontent.com/53250236/99110851-4fb90580-25eb-11eb-98b8-3c9beab15bcd.png) | https://github.com/nba-emu/NanoBoyAdvance/issues/136 |
| Sonic Advance | Breaks when skipping bios | | https://github.com/ITotalJustice/notorious_beeg/issues/67 |
| Sonic Advance | Doesn't boot | ![](https://user-images.githubusercontent.com/1358414/160031842-c39ec433-022c-4713-9252-95e11776f465.png) | https://github.com/DaveTCode/GBADotnet/issues/39 |
| Sonic Advance 2 | Doesn't boot | ![](https://user-images.githubusercontent.com/1358414/160031710-5ef2ec7b-5321-4138-adc8-c10e75c1fd9b.png) | https://github.com/DaveTCode/GBADotnet/issues/39 |
| SpongeBob SquarePants (Volume 1) | "not compatible with Game Boy Player" screen repeats ad infinitum | | https://github.com/nba-emu/NanoBoyAdvance/issues/152 |
| Spyro - Season of Ice (U)(GBA) | Glitchy line in text box | ![](https://user-images.githubusercontent.com/2696404/81910035-0963f900-95fe-11ea-8622-8945a7137215.PNG) | https://github.com/nba-emu/NanoBoyAdvance/issues/94 |
| Spyro | Shows wrong priorities in game | ![](https://user-images.githubusercontent.com/1358414/160235146-87ecca66-bfe3-42d4-a933-60a4980a6914.png) | https://github.com/DaveTCode/GBADotnet/issues/41 |
| Star Wars Episode II | Lines across scrolling text | ![](https://user-images.githubusercontent.com/2696404/81909561-5abfb880-95fd-11ea-9ec7-f9567626555e.PNG) | https://github.com/nba-emu/NanoBoyAdvance/issues/93 |
| Super Monkey Ball Jr. (USA) | Saving does not work | ![](https://user-images.githubusercontent.com/2696404/83508244-35d3ac80-a4fc-11ea-96e6-f29ab323a4bd.png) | https://github.com/nba-emu/NanoBoyAdvance/issues/110 |
| Tactics Ogre | Odd tile effect during startup | ![](https://user-images.githubusercontent.com/1358414/159805043-84cd81f0-5787-49ce-8b85-ed9c4fbf8486.png) | https://github.com/DaveTCode/GBADotnet/issues/27 |
| Tactics Ogre | Blending not working with windows | ![](https://user-images.githubusercontent.com/1358414/160657978-70070596-5c24-4f9c-a1a5-07fdec0052eb.png) | https://github.com/DaveTCode/GBADotnet/issues/50 |
| Tales of Phantasia | Text box scrolls with the background | ![](https://user-images.githubusercontent.com/47043333/163222649-f16f9bb2-798a-4b7b-ba46-598c8344d380.mp4) | https://github.com/ITotalJustice/notorious_beeg/issues/48 |
| The Legend of Zelda: A Link to the Past | Flickering background in choose game screen | ![](https://user-images.githubusercontent.com/29958696/103410557-26891000-4b6c-11eb-9c0e-8e09aad391b4.png) | https://github.com/jsmolka/eggvance/issues/8 |
| The Legend of Zelda: The Minish Cap | Mising "Roll" object text | ![](https://user-images.githubusercontent.com/47043333/162972337-a99c85e6-dfb5-4b22-8f33-02a77980c97d.png) | https://github.com/ITotalJustice/notorious_beeg/issues/41 |
| The Legend of Zelda: The Minish Cap | Freezes at title screen and in game | ![](https://user-images.githubusercontent.com/47043333/160712469-5ba7959a-0ed3-4111-aef2-058dc00e96f4.png) | https://github.com/ITotalJustice/notorious_beeg/issues/12 |
| The Legend of Zelda: The Minish Cap | Black screen after intro | | https://github.com/DaveTCode/GBADotnet/issues/71 |
| Tonc: bld_demo | Blending not working for semi-transparent objects | ![](https://user-images.githubusercontent.com/29958696/115150112-3e2acc80-a067-11eb-9a93-5a0bd33d4098.png) | https://github.com/jsmolka/eggvance/issues/21 |
| Tony Hawk's Pro Skater 2 | Black screen on boot | ![](https://user-images.githubusercontent.com/1358414/160031361-bb896884-38d5-43ad-969d-780626d51bb8.png) | https://github.com/DaveTCode/GBADotnet/issues/38 |
| Tony Hawk's Pro Skater 2 | Freezes on startup | ![](https://user-images.githubusercontent.com/47043333/161389892-16e0254d-3c02-424a-8f43-c5829dd88f09.png) | https://github.com/ITotalJustice/notorious_beeg/issues/18 |
| Tony Hawk's Pro Skater 2 | Text missing from intro | ![](https://user-images.githubusercontent.com/47043333/161536366-03567a7a-0930-465d-82b3-f67ba6dd3840.png) | https://github.com/ITotalJustice/notorious_beeg/issues/26 |
| Tony Hawk's Pro Skater 3 | Pink screen on boot | ![](https://user-images.githubusercontent.com/1358414/160031409-7c9f1309-cd24-4a18-9168-ea261af682d0.png) | https://github.com/DaveTCode/GBADotnet/issues/38 |
| Tony Hawk's Pro Skater 4 | Pink screen on boot | | https://github.com/DaveTCode/GBADotnet/issues/38 |
| Top Gun: Combat Zones | Cannot pick any options in main menu | | https://github.com/nba-emu/NanoBoyAdvance/issues/105 |
| Top Gup: Combat Zones | 'A' button doesn't work in menu | ![](https://user-images.githubusercontent.com/29958696/109382967-cef4ef80-78e3-11eb-86fc-1ede3cb289e3.png) | https://github.com/jsmolka/eggvance/issues/17 |
| V-Rally 3 | Black screen on boot | | https://github.com/ITotalJustice/notorious_beeg/issues/53 |
| V-Rally 3 | Sky flashes while racing | ![](https://user-images.githubusercontent.com/47043333/164571435-302cdf81-9392-49f5-a324-b9a66b4dfcf6.mp4) | https://github.com/ITotalJustice/notorious_beeg/issues/54 |
| V-Rally 3 | Sky is black | ![](https://user-images.githubusercontent.com/1358414/162641857-a1b7b138-2bf2-47c3-a5ba-d0fe0013cd05.png) | https://github.com/DaveTCode/GBADotnet/issues/74 |
| Wario Land 4 (USA, Europe) | Sound clicks | | https://github.com/nba-emu/NanoBoyAdvance/issues/104 |
| Wario Land 4 | Audio gets distorted after playing intro | | https://github.com/skylersaleh/SkyEmu/issues/11 |
| Who Wants to Be a Millionaire (Europe) | Crackling sound | | https://github.com/nba-emu/NanoBoyAdvance/issues/100 |
| Yggdra Union | Hangs on title screen | ![](https://user-images.githubusercontent.com/1358414/162641157-2657c782-c660-4e9e-81e8-58e5be6563fa.png) | https://github.com/DaveTCode/GBADotnet/issues/72 |
| Yggdra Union | Hangs during intro | ![](https://user-images.githubusercontent.com/1358414/163144230-80c0ed53-b950-4f9c-8598-9699c147f11a.png) | https://github.com/DaveTCode/GBADotnet/issues/72 |
| Yu-Gi-Oh! Destiny Board Traveler | Black screen on boot | | https://github.com/ITotalJustice/notorious_beeg/issues/52 |
| Yu-Gi-Oh! | Vertical lines rendered down screen | ![](https://user-images.githubusercontent.com/1358414/162641286-84c16f32-54af-4664-97fd-ed34c7719a15.png) | https://github.com/DaveTCode/GBADotnet/issues/73 |
