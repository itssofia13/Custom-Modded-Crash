---- Minecraft Crash Report ----
// Hi. I'm Minecraft, and I'm a crashaholic.

Time: 3/22/21 2:08 PM
Description: Feature placement

java.lang.IllegalArgumentException: bound must be positive
	at java.util.Random.nextInt(Unknown Source) ~[?:1.8.0_281] {}
	at net.mcreator.theomaypatysamphibianmod.world.structure.GlowingStructure$1.generate(GlowingStructure.java:66) ~[the_omaypatys_amphibian_mod_:?] {re:classloading}
	at net.mcreator.theomaypatysamphibianmod.world.structure.GlowingStructure$1.func_241855_a(GlowingStructure.java:54) ~[the_omaypatys_amphibian_mod_:?] {re:classloading}
	at net.minecraft.world.gen.feature.ConfiguredFeature.func_242765_a(SourceFile:55) ~[?:?] {re:classloading}
	at net.minecraft.world.gen.feature.DecoratedFeature.func_242772_a(SourceFile:23) ~[?:?] {re:classloading}
	at java.util.stream.Streams$StreamBuilderImpl.forEachRemaining(Unknown Source) ~[?:1.8.0_281] {}
	at java.util.stream.ReferencePipeline$Head.forEach(Unknown Source) ~[?:1.8.0_281] {}
	at net.minecraft.world.gen.feature.DecoratedFeature.func_241855_a(SourceFile:22) ~[?:?] {re:classloading}
	at net.minecraft.world.gen.feature.DecoratedFeature.func_241855_a(SourceFile:14) ~[?:?] {re:classloading}
	at net.minecraft.world.gen.feature.ConfiguredFeature.func_242765_a(SourceFile:55) ~[?:?] {re:classloading}
	at net.minecraft.world.biome.Biome.func_242427_a(Biome.java:254) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:terraincognita.mixins.json:client.BiomeMixin,pl:mixin:A}
	at net.minecraft.world.gen.ChunkGenerator.func_230351_a_(SourceFile:220) ~[?:?] {re:mixin,re:computing_frames,re:classloading}
	at net.minecraft.world.chunk.ChunkStatus.func_222605_b(ChunkStatus.java:77) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:bettercaves.mixins.json:ChunkStatusMixin,pl:mixin:APP:byg.mixins.json:common.world.ChunkStatusMixin,pl:mixin:A}
	at net.minecraft.world.chunk.ChunkStatus.func_223198_a(ChunkStatus.java:198) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:bettercaves.mixins.json:ChunkStatusMixin,pl:mixin:APP:byg.mixins.json:common.world.ChunkStatusMixin,pl:mixin:A}
	at net.minecraft.world.server.ChunkManager.lambda$null$18(ChunkManager.java:675) ~[?:?] {re:classloading,xf:OptiFine:default}
	at com.mojang.datafixers.util.Either$Left.map(Either.java:38) ~[datafixerupper-4.0.26.jar:?] {re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading}
	at net.minecraft.world.server.ChunkManager.lambda$chunkGenerate$20(ChunkManager.java:673) ~[?:?] {re:classloading,xf:OptiFine:default}
	at java.util.concurrent.CompletableFuture.uniCompose(Unknown Source) ~[?:1.8.0_281] {}
	at java.util.concurrent.CompletableFuture$UniCompose.tryFire(Unknown Source) ~[?:1.8.0_281] {}
	at java.util.concurrent.CompletableFuture$Completion.run(Unknown Source) ~[?:1.8.0_281] {}
	at net.minecraft.world.chunk.ChunkTaskPriorityQueueSorter.func_219083_b(SourceFile:58) ~[?:?] {re:classloading}
	at net.minecraft.util.concurrent.DelegatedTaskExecutor.func_213148_e(SourceFile:94) ~[?:?] {re:classloading}
	at net.minecraft.util.concurrent.DelegatedTaskExecutor.func_213145_a(SourceFile:137) ~[?:?] {re:classloading}
	at net.minecraft.util.concurrent.DelegatedTaskExecutor.run(SourceFile:105) ~[?:?] {re:classloading}
	at java.util.concurrent.ForkJoinTask$RunnableExecuteAction.exec(Unknown Source) ~[?:1.8.0_281] {}
	at java.util.concurrent.ForkJoinTask.doExec(Unknown Source) ~[?:1.8.0_281] {}
	at java.util.concurrent.ForkJoinPool$WorkQueue.runTask(Unknown Source) ~[?:1.8.0_281] {}
	at java.util.concurrent.ForkJoinPool.runWorker(Unknown Source) ~[?:1.8.0_281] {re:computing_frames}
	at java.util.concurrent.ForkJoinWorkerThread.run(Unknown Source) ~[?:1.8.0_281] {}


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Thread: Server thread
Stacktrace:
	at java.util.Random.nextInt(Unknown Source) ~[?:1.8.0_281] {}
	at net.mcreator.theomaypatysamphibianmod.world.structure.GlowingStructure$1.generate(GlowingStructure.java:66) ~[the_omaypatys_amphibian_mod_:?] {re:classloading}
	at net.mcreator.theomaypatysamphibianmod.world.structure.GlowingStructure$1.func_241855_a(GlowingStructure.java:54) ~[the_omaypatys_amphibian_mod_:?] {re:classloading}
	at net.minecraft.world.gen.feature.ConfiguredFeature.func_242765_a(SourceFile:55) ~[?:?] {re:classloading}
	at net.minecraft.world.gen.feature.DecoratedFeature.func_242772_a(SourceFile:23) ~[?:?] {re:classloading}
	at java.util.stream.Streams$StreamBuilderImpl.forEachRemaining(Unknown Source) ~[?:1.8.0_281] {}
	at java.util.stream.ReferencePipeline$Head.forEach(Unknown Source) ~[?:1.8.0_281] {}
	at net.minecraft.world.gen.feature.DecoratedFeature.func_241855_a(SourceFile:22) ~[?:?] {re:classloading}
	at net.minecraft.world.gen.feature.DecoratedFeature.func_241855_a(SourceFile:14) ~[?:?] {re:classloading}
	at net.minecraft.world.gen.feature.ConfiguredFeature.func_242765_a(SourceFile:55) ~[?:?] {re:classloading}
-- Feature --
Details:
	Id: minecraft:decorated
	Config: < DecoratedFeatureConfig [null | [minecraft:nope net.minecraft.world.gen.placement.NoPlacementConfig@12e1ebd8]] >
	Description: < DecoratedFeature [minecraft:decorated] >
Stacktrace:
	at net.minecraft.world.biome.Biome.func_242427_a(Biome.java:254) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:terraincognita.mixins.json:client.BiomeMixin,pl:mixin:A}


-- Generation --
Details:
	CenterX: -56
	CenterZ: -22
	Seed: 4535846015985347817
	Biome: net.minecraft.world.biome.Biome@4ed43343
Stacktrace:
	at net.minecraft.world.gen.ChunkGenerator.func_230351_a_(SourceFile:220) ~[?:?] {re:mixin,re:computing_frames,re:classloading}
	at net.minecraft.world.chunk.ChunkStatus.func_222605_b(ChunkStatus.java:77) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:bettercaves.mixins.json:ChunkStatusMixin,pl:mixin:APP:byg.mixins.json:common.world.ChunkStatusMixin,pl:mixin:A}
	at net.minecraft.world.chunk.ChunkStatus.func_223198_a(ChunkStatus.java:198) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:bettercaves.mixins.json:ChunkStatusMixin,pl:mixin:APP:byg.mixins.json:common.world.ChunkStatusMixin,pl:mixin:A}


-- Chunk to be generated --
Details:
	Location: -56,-22
	Position hash: -90194313272
	Generator: net.minecraft.world.gen.NoiseChunkGenerator@58da4a70
Stacktrace:
	at net.minecraft.world.server.ChunkManager.lambda$null$18(ChunkManager.java:675) ~[?:?] {re:classloading,xf:OptiFine:default}
	at com.mojang.datafixers.util.Either$Left.map(Either.java:38) ~[datafixerupper-4.0.26.jar:?] {re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading,re:classloading}
	at net.minecraft.world.server.ChunkManager.lambda$chunkGenerate$20(ChunkManager.java:673) ~[?:?] {re:classloading,xf:OptiFine:default}
	at java.util.concurrent.CompletableFuture.uniCompose(Unknown Source) ~[?:1.8.0_281] {}
	at java.util.concurrent.CompletableFuture$UniCompose.tryFire(Unknown Source) ~[?:1.8.0_281] {}
	at java.util.concurrent.CompletableFuture$Completion.run(Unknown Source) ~[?:1.8.0_281] {}
	at net.minecraft.world.chunk.ChunkTaskPriorityQueueSorter.func_219083_b(SourceFile:58) ~[?:?] {re:classloading}
	at net.minecraft.util.concurrent.DelegatedTaskExecutor.func_213148_e(SourceFile:94) ~[?:?] {re:classloading}
	at net.minecraft.util.concurrent.DelegatedTaskExecutor.func_213145_a(SourceFile:137) ~[?:?] {re:classloading}


-- Affected level --
Details:
	All players: 1 total; [ServerPlayerEntity['_moonstxrs_'/306, l='ServerLevel[New World]', x=-988.22, y=71.80, z=-82.28]]
	Chunk stats: ServerChunkCache: 4845
	Level dimension: minecraft:overworld
	Level spawn location: World: (-96,71,192), Chunk: (at 0,4,0 in -6,12; contains blocks -96,0,192 to -81,255,207), Region: (-1,0; contains chunks -32,0 to -1,31, blocks -512,0,0 to -1,255,511)
	Level time: 26026 game time, 26026 day time
	Level name: New World
	Level game mode: Game mode: survival (ID 0). Hardcore: false. Cheats: false
	Level weather: Rain time: 76163 (now: false), thunder time: 47941 (now: false)
	Known server brands: forge
	Level was modded: true
	Level storage version: 0x04ABD - Anvil
Stacktrace:
	at net.minecraft.server.MinecraftServer.func_71190_q(MinecraftServer.java:854) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:upstream.mixins.json:MixinMinecraftServer,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A}
	at net.minecraft.server.MinecraftServer.func_71217_p(MinecraftServer.java:787) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:upstream.mixins.json:MixinMinecraftServer,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A}
	at net.minecraft.server.integrated.IntegratedServer.func_71217_p(IntegratedServer.java:118) ~[?:?] {re:classloading,xf:OptiFine:default}
	at net.minecraft.server.MinecraftServer.func_240802_v_(MinecraftServer.java:642) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:upstream.mixins.json:MixinMinecraftServer,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A}
	at net.minecraft.server.MinecraftServer.func_240783_a_(MinecraftServer.java:232) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:upstream.mixins.json:MixinMinecraftServer,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A}
	at java.lang.Thread.run(Unknown Source) [?:1.8.0_281] {}


-- System Details --
Details:
	Minecraft Version: 1.16.5
	Minecraft Version ID: 1.16.5
	Operating System: Windows 10 (amd64) version 10.0
	Java Version: 1.8.0_281, Oracle Corporation
	Java VM Version: Java HotSpot(TM) 64-Bit Server VM (mixed mode), Oracle Corporation
	Memory: 5194621344 bytes (4953 MB) / 11398021120 bytes (10870 MB) up to 11398021120 bytes (10870 MB)
	CPUs: 16
	JVM Flags: 3 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xms11110m -Xmx11238m
	ModLauncher: 8.0.9+86+master.3cf110c
	ModLauncher launch target: fmlclient
	ModLauncher naming: srg
	ModLauncher services: 
		/mixin-0.8.2.jar mixin PLUGINSERVICE 
		/eventbus-4.0.0.jar eventbus PLUGINSERVICE 
		/forge-1.16.5-36.1.2-launcher.jar object_holder_definalize PLUGINSERVICE 
		/forge-1.16.5-36.1.2-launcher.jar runtime_enum_extender PLUGINSERVICE 
		/accesstransformers-3.0.1.jar accesstransformer PLUGINSERVICE 
		/forge-1.16.5-36.1.2-launcher.jar capability_inject_definalize PLUGINSERVICE 
		/forge-1.16.5-36.1.2-launcher.jar runtimedistcleaner PLUGINSERVICE 
		/mixin-0.8.2.jar mixin TRANSFORMATIONSERVICE 
		/OptiFine_1.16.5_HD_U_G7%20(1).jar OptiFine TRANSFORMATIONSERVICE 
		/forge-1.16.5-36.1.2-launcher.jar fml TRANSFORMATIONSERVICE 
	FML: 36.1
	Forge: net.minecraftforge:36.1.2
	FML Language Providers: 
		javafml@36.1
		minecraft@1
	Mod List: 
		The+Omaypaty's+ambhibian+age+mod+V.2.jar          |The OmayPaty's amphibian mod  |the_omaypatys_amphibian_mod_  |1.0.0               |DONE      |NOSIGNATURE
		QuarkOddities-1.16.3.jar                          |Quark Oddities                |quarkoddities                 |1.16.3              |DONE      |NOSIGNATURE
		torchslabmod-1.16.4_v1.6.18.jar                   |Torch Slab Mod                |torchslabmod                  |1.6.18              |DONE      |NOSIGNATURE
		potiondescriptions-1.16.3-1.5.1.jar               |Potion Descriptions           |potiondescriptions            |1.16.3-1.5.1        |DONE      |NOSIGNATURE
		infernal-expansion-forge-1.3.jar                  |Infernal Expansion            |infernalexp                   |Release 1.3         |DONE      |NOSIGNATURE
		craftingstation-4.1.1.jar                         |Crafting Station              |craftingstation               |4.1.1               |DONE      |NOSIGNATURE
		jei-1.16.4-7.6.1.71.jar                           |Just Enough Items             |jei                           |7.6.1.71            |DONE      |NOSIGNATURE
		Druidcraft-1.16.5-0.4.52.jar                      |Druidcraft                    |druidcraft                    |0.4.52              |DONE      |NOSIGNATURE
		DoggyTalents-1.16.4-2.0.1.3.jar                   |Doggy Talents 2               |doggytalents                  |2.0.1.3             |DONE      |NOSIGNATURE
		abnormals_core-1.16.5-3.1.1.jar                   |Abnormals Core                |abnormals_core                |3.1.1               |DONE      |NOSIGNATURE
		buzzier_bees-1.16.5-3.0.1.jar                     |Buzzier Bees                  |buzzier_bees                  |3.0.1               |DONE      |NOSIGNATURE
		Enhanced-Mushrooms-1.16.5-3.0.6.jar               |Enhanced Mushrooms            |enhanced_mushrooms            |1.16.5-3.0.6        |DONE      |NOSIGNATURE
		strawgolem-1.16-1.9.jar                           |Straw Golem                   |strawgolem                    |1.16-1.9            |DONE      |NOSIGNATURE
		BetterCaves-Forge-1.16.4-1.1.1.jar                |YUNG's Better Caves           |bettercaves                   |1.16.4-1.1.1        |DONE      |NOSIGNATURE
		Waystones_1.16.5-7.4.0.jar                        |Waystones                     |waystones                     |7.4.0               |DONE      |NOSIGNATURE
		journeymap-1.16.5-5.7.1.jar                       |Journeymap                    |journeymap                    |5.7.1               |DONE      |NOSIGNATURE
		Placebo-1.16.4-4.4.1.jar                          |Placebo                       |placebo                       |4.4.1               |DONE      |NOSIGNATURE
		Organics-1.16.4-0.1.4.jar                         |Organics                      |organics                      |0.1.4               |DONE      |NOSIGNATURE
		citadel-1.6.2.jar                                 |Citadel                       |citadel                       |1.6.2               |DONE      |NOSIGNATURE
		alexsmobs-1.7.1.jar                               |Alex's Mobs                   |alexsmobs                     |1.7.1               |DONE      |NOSIGNATURE
		NaturesCompass-1.16.5-1.8.6.jar                   |Nature's Compass              |naturescompass                |1.16.5-1.8.6        |DONE      |NOSIGNATURE
		YungsApi-1.16.4-Forge-4.jar                       |YUNG's API                    |yungsapi                      |1.16.4-Forge-4      |DONE      |NOSIGNATURE
		decorative_blocks-1.16.4-1.7.2.jar                |Decorative Blocks             |decorative_blocks             |1.7.2               |DONE      |NOSIGNATURE
		upstream-1.0.jar                                  |Upstream                      |upstream                      |1.0                 |DONE      |NOSIGNATURE
		fantasy-forge-1.1.1.jar                           |Fantasy Mounts                |fantasy                       |1.0                 |DONE      |NOSIGNATURE
		gemsnjewels-1.16.4-0.21.0.jar                     |Gems & Jewels                 |gemsnjewels                   |0.21.0              |DONE      |NOSIGNATURE
		betteranimalsplus-1.16.4-10.1.0.jar               |Better Animals Plus           |betteranimalsplus             |10.1.0              |DONE      |NOSIGNATURE
		Bookshelf-1.16.5-10.0.1.jar                       |Bookshelf                     |bookshelf                     |10.0.1              |DONE      |eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		TinyMobFarm-1.16.4-1.1.1.jar                      |Tiny Mob Farm                 |tinymobfarm                   |1.1.1               |DONE      |NOSIGNATURE
		Omni-1.16.5-1.2.2.jar                             |Omni                          |omni                          |version             |DONE      |NOSIGNATURE
		Hwyla-forge-1.10.11-B78_1.16.2.jar                |Waila                         |waila                         |1.10.11-B78_1.16.2  |DONE      |NOSIGNATURE
		dads_sewing-6.0.jar                               |Dad's Sewing                  |dads_sewing                   |6.0                 |DONE      |NOSIGNATURE
		tablechair-1.16.5.jar                             |TableChair                    |tablechair                    |1.0                 |DONE      |NOSIGNATURE
		forge-1.16.5-36.1.2-universal.jar                 |Forge                         |forge                         |36.1.2              |DONE      |22:af:21:d8:19:82:7f:93:94:fe:2b:ac:b7:e4:41:57:68:39:87:b1:a7:5c:c6:44:f9:25:74:21:14:f5:0d:90
		scuba-gear-1.16.5-1.0.3.jar                       |Scuba Gear                    |scuba_gear                    |1.0.3               |DONE      |NOSIGNATURE
		PattysMoreStuff-Stable-1.16.4-1.3.0a.jar          |pattysmorestuff               |pattysmorestuff               |1.3.0a              |DONE      |NOSIGNATURE
		untitledduckmod-0.1.2-forge.jar                   |Untitled Duck Mod             |untitledduckmod               |0.1.2               |DONE      |NOSIGNATURE
		supplementaries-1.16.5-0.10.4b.jar                |Supplementaries               |supplementaries               |1.16.5-0.10.4       |DONE      |NOSIGNATURE
		Buddycards-1.16.5-2.1.0.jar                       |Buddycards                    |buddycards                    |1.16.5-2.1.0        |DONE      |NOSIGNATURE
		vsushi+1.16.4_v0.2.jar                            |Vanilla Sushi                 |vsushi                        |1.0.0               |DONE      |NOSIGNATURE
		cuneiform-1.16.3-1.2.3.1.jar                      |Cuneiform                     |cuneiform                     |1.16.3-1.2.3.1      |DONE      |NOSIGNATURE
		neapolitan-1.16.5-2.1.0.jar                       |Neapolitan                    |neapolitan                    |2.1.0               |DONE      |NOSIGNATURE
		ironchest-1.16.4-11.2.10.jar                      |Iron Chests                   |ironchest                     |1.16.4-11.2.10      |DONE      |NOSIGNATURE
		corpse-1.16.5-1.0.1.jar                           |Corpse                        |corpse                        |1.16.5-1.0.1        |DONE      |NOSIGNATURE
		forge-1.16.5-36.1.2-client.jar                    |Minecraft                     |minecraft                     |1.16.5              |DONE      |NOSIGNATURE
		FarmersDelight-1.16.3-0.3.2.jar                   |Farmer's Delight              |farmersdelight                |1.16.3-0.3.2        |DONE      |NOSIGNATURE
		delicateanddainty-0.1.4-1.16.4.jar                |Delicate and Dainty!          |delicateanddainty             |0.1.4-1.16.4        |DONE      |NOSIGNATURE
		EnchantmentDescriptions-1.16.5-7.0.2.jar          |EnchantmentDescriptions       |enchdesc                      |7.0.2               |DONE      |eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		pandoras_creatures-1.16.3-2.0.1.jar               |Pandoras Creatures            |pandoras_creatures            |1.16.3-2.0.1        |DONE      |NOSIGNATURE
		AmbientSounds_v3.1.5_mc1.16.5.jar                 |Ambient Sounds                |ambientsounds                 |3.0.3               |DONE      |NOSIGNATURE
		morevanillalib-1.16.4-1.4.0.jar                   |MoreVanillaLib                |morevanillalib                |1.4.0               |DONE      |NOSIGNATURE
		ironfurnaces-1.16.5-2.6.4.jar                     |Iron Furnaces                 |ironfurnaces                  |2.6.4               |DONE      |NOSIGNATURE
		CreativeCore_v2.1.0_mc1.16.5.jar                  |CreativeCore                  |creativecore                  |2.0.0               |DONE      |NOSIGNATURE
		mcw-fences-1.0.0-mc1.16.5.jar                     |Macaw's Fences and Walls      |mcwfences                     |1.0.0               |DONE      |NOSIGNATURE
		towers_of_the_wild-1.16.4-2.0.1.jar               |Towers Of The Wild            |towers_of_the_wild            |1.16.4-2.0.1        |DONE      |NOSIGNATURE
		fairylights-4.0.5-1.16.5.jar                      |Fairy Lights                  |fairylights                   |4.0.5               |DONE      |NOSIGNATURE
		farmersdelightintegration-1.16.5-1.0.3.jar        |Farmer's Delight Integration  |farmersdelightintegration     |1.16.5-1.0.3        |DONE      |NOSIGNATURE
		atmospheric-1.16.4-3.0.0.jar                      |Atmospheric                   |atmospheric                   |3.0.0               |DONE      |NOSIGNATURE
		CNB-1.16.3_4-1.2.10.jar                           |Creatures and Beasts          |cnb                           |1.2.10              |DONE      |NOSIGNATURE
		curios-forge-1.16.5-4.0.5.0.jar                   |Curios API                    |curios                        |1.16.5-4.0.5.0      |DONE      |NOSIGNATURE
		eidolon-0.2.7.jar                                 |Eidolon                       |eidolon                       |0.2.7               |DONE      |NOSIGNATURE
		Artifacts-1.16.5-2.8.3.jar                        |Artifacts                     |artifacts                     |1.16.5-2.8.3        |DONE      |NOSIGNATURE
		Patchouli-1.16.4-50.jar                           |Patchouli                     |patchouli                     |1.16.4-50           |DONE      |NOSIGNATURE
		ExtraSpace+1.0.6+1.16.5.jar                       |extraspace                    |extraspace                    |1.0.6               |DONE      |NOSIGNATURE
		AutoRegLib-1.6-47.jar                             |AutoRegLib                    |autoreglib                    |1.6-47              |DONE      |NOSIGNATURE
		abnormals_delight-1.16.5-1.0.1.jar                |Abnormals Delight             |abnormals_delight             |1.0.1               |DONE      |NOSIGNATURE
		OreExcavation-1.8.155.jar                         |Ore Excavation                |oreexcavation                 |1.8.155             |DONE      |e7:68:1c:0d:b9:7e:cf:f8:f3:40:9c:84:c5:39:d7:a4:59:78:b0:6b:c3:fd:b7:4f:69:18:a3:88:e3:76:8c:3f
		vanillahammers-1.16.4-2.2.0.jar                   |Vanilla Hammers               |vanillahammers                |2.2.0               |DONE      |NOSIGNATURE
		EnigmaticLegacy-2.11.2.jar                        |Enigmatic Legacy              |enigmaticlegacy               |2.11.2              |DONE      |NOSIGNATURE
		buildersaddition-1.16.4-20210214a.jar             |Builders Crafts & Addition    |buildersaddition              |1.16.4-20210214a    |DONE      |NOSIGNATURE
		fins-1.4.0.jar                                    |Fins and Tails                |fins                          |1.4.0               |DONE      |NOSIGNATURE
		mcw-furniture-2.0.1-mc1.16.5.jar                  |Macaw's Furniture             |mcwfurnitures                 |2.0.1               |DONE      |NOSIGNATURE
		Craftable_NameTag+1.16.x.jar                      |Craftable Name Tag            |bkcraftablenametag            |[1.16,)             |DONE      |NOSIGNATURE
		byg-1.1.12.jar                                    |Oh The Biomes You'll Go       |byg                           |1.1.11              |DONE      |NOSIGNATURE
		Aquaculture-1.16.5-2.1.16.jar                     |Aquaculture 2                 |aquaculture                   |1.16.5-2.1.16       |DONE      |NOSIGNATURE
		charm-forge-1.16.4-2.1.1-hotfix3.jar              |Charm                         |charm                         |2.1.1               |DONE      |NOSIGNATURE
		Quark-r2.4-308.jar                                |Quark                         |quark                         |r2.4-308            |DONE      |NOSIGNATURE
		terraincognita-1.16.3-1.6.1.1.jar                 |Terra Incognita               |terraincognita                |1.16.3-1.6.1        |DONE      |NOSIGNATURE
		Apotheosis-1.16.3-4.4.1.jar                       |Apotheosis                    |apotheosis                    |4.4.1               |DONE      |NOSIGNATURE
		BetterMineshafts-Forge-1.16.4-2.0.2.jar           |YUNG's Better Mineshafts      |bettermineshafts              |1.16.4-2.0.2        |DONE      |NOSIGNATURE
		geckolib-forge-1.16.5-3.0.15.jar                  |GeckoLib                      |geckolib3                     |3.0.15              |DONE      |NOSIGNATURE
		Cutecore+1.2 (2).jar                              |Cutecore                      |cutecore                      |1.0.0               |DONE      |NOSIGNATURE
	Crash Report UUID: af752886-18f0-4d93-aa43-c6eeed67dcbe
	Patchouli open book context: n/a
	OptiFine Version: OptiFine_1.16.5_HD_U_G7
	OptiFine Build: 20210305-003221
	Render Distance Chunks: 15
	Mipmaps: 4
	Anisotropic Filtering: 1
	Antialiasing: 0
	Multitexture: false
	Shaders: BSL+v6.2.zip
	OpenGlVersion: 4.6.0 NVIDIA 460.93
	OpenGlRenderer: GeForce RTX 2060/PCIe/SSE2
	OpenGlVendor: NVIDIA Corporation
	CpuCount: 16
	Player Count: 1 / 8; [ServerPlayerEntity['_moonstxrs_'/306, l='ServerLevel[New World]', x=-988.22, y=71.80, z=-82.28]]
	Data Packs: vanilla, mod:the_omaypatys_amphibian_mod_, mod:quarkoddities (incompatible), mod:torchslabmod (incompatible), mod:potiondescriptions, mod:infernalexp (incompatible), mod:craftingstation (incompatible), mod:jei, mod:druidcraft (incompatible), mod:doggytalents (incompatible), mod:abnormals_core, mod:buzzier_bees, mod:enhanced_mushrooms, mod:strawgolem, mod:bettercaves (incompatible), mod:waystones (incompatible), mod:journeymap (incompatible), mod:placebo (incompatible), mod:organics, mod:citadel (incompatible), mod:alexsmobs, mod:naturescompass (incompatible), mod:yungsapi, mod:decorative_blocks, mod:upstream, mod:fantasy, mod:gemsnjewels (incompatible), mod:betteranimalsplus (incompatible), mod:bookshelf, mod:tinymobfarm (incompatible), mod:omni, mod:waila, mod:dads_sewing, mod:tablechair, mod:forge, mod:scuba_gear (incompatible), mod:pattysmorestuff (incompatible), mod:untitledduckmod, mod:supplementaries, mod:buddycards, mod:vsushi, mod:cuneiform, mod:neapolitan, mod:ironchest (incompatible), mod:corpse, mod:farmersdelight, mod:delicateanddainty, mod:enchdesc, mod:pandoras_creatures (incompatible), mod:ambientsounds, mod:morevanillalib, mod:ironfurnaces, mod:creativecore, mod:mcwfences, mod:towers_of_the_wild, mod:fairylights, mod:farmersdelightintegration, mod:atmospheric, mod:cnb, mod:curios, mod:eidolon, mod:artifacts, mod:extraspace, mod:autoreglib (incompatible), mod:abnormals_delight, mod:oreexcavation, mod:vanillahammers, mod:buildersaddition (incompatible), mod:fins, mod:mcwfurnitures, mod:bkcraftablenametag, mod:byg, mod:aquaculture (incompatible), mod:charm (incompatible), mod:quark (incompatible), mod:terraincognita, mod:apotheosis (incompatible), mod:bettermineshafts, mod:geckolib3 (incompatible), mod:cutecore, mod:patchouli (incompatible), mod:enigmaticlegacy
	Type: Integrated Server (map_client.txt)
	Is Modded: Definitely; Client brand changed to 'forge'
