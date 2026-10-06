# CS 415
Coursework for CS 415 (Game Development) at UIUC by Lucas Lombana Arias

Unreal assets are stored with Git LFS, so run `git lfs pull` after cloning.

MP1: Infinite Matrix, a Matrix-themed tunnel runner in Unreal Engine 5.6 Blueprints that builds on the Kodeco tutorial with health, score, health packs, projectiles, enemies and increasing speed, plus two creative mods: tunnel colors that follow the player's health and a saved high score. Demo video: `MP1/InfiniteMatrixStarter/MP1_recording.mp4`.

MP2: Level Design (Part 1), a floating-island platformer in Unreal Engine 5.6 Blueprints built on the Unreal Learning Kit, with a health bar and Game Over screen with restart, health packs, floating collectibles with a score, and a Pursuer enemy that patrols around its start point, chases the player on sight and walks back when the player escapes. Demo video: `MP2/UnrealLearningKit/MP2_recording.mp4`.

MP2: Level Design (Part 2), the full "Sky Islands" level: five sections (Start Meadow, Pursuer Plaza, Crusher Causeway, Mortar Isle, Sky Climb and Final Fortress) with 62 coins and 10 health packs. It adds a Mortar enemy that lobs gravity-arc shells whose blast damages and knocks back the player, and a custom Crusher enemy that hovers over a path and slams down when the player walks underneath. All enemies share the same contact rules: stomping from above destroys them, and touching them anywhere else costs health, knocks the player back and briefly removes control. Falling off the map or reaching 0 HP shows Game Over, the goal gate shows a Level Complete screen, and both restart the level. Design document: `MP2/MP2_Part2_Design.docx` (also `.pdf`). Demo video: `MP2/UnrealLearningKit/MP2_Part2_recording.mp4`.
