---
name: BanItem-3.4 error reporting
about: Hello, I have a PlayerInteractEntityEvent error when using BanItem-3.4, my
  version is 1.12.2, can you fix this error?
title: ''
labels: ''
assignees: ''

---

[01:56:49] [Server thread/ERROR]: Could not pass event PlayerInteractEntityEvent to BanItem v3.4
java.lang.NoSuchMethodError: org.bukkit.inventory.PlayerInventory.getItem(Lorg/bukkit/inventory/EquipmentSlot;)Lorg/bukkit/inventory/ItemStack;
        at fr.andross.banitem.BanListener.lambda$load$26(BanListener.java:376) ~[?:?]
        at org.bukkit.plugin.RegisteredListener.callEvent(RegisteredListener.java:62) ~[RegisteredListener.class:git-CatServer-1.12.2-ab28211f]
        at org.bukkit.plugin.SimplePluginManager.fireEvent(SimplePluginManager.java:503) [SimplePluginManager.class:git-CatServer-1.12.2-ab28211f]
        at org.bukkit.plugin.SimplePluginManager.callEvent(SimplePluginManager.java:488) [SimplePluginManager.class:git-CatServer-1.12.2-ab28211f]
        at net.minecraft.network.NetHandlerPlayServer.func_147340_a(NetHandlerPlayServer.java:1854) [pa.class:?]
        at net.minecraft.network.play.client.CPacketUseEntity.func_148833_a(SourceFile:69) [li.class:?]
        at net.minecraft.network.play.client.CPacketUseEntity.func_148833_a(SourceFile:13) [li.class:?]
        at net.minecraft.network.PacketThreadUtil$1.run(SourceFile:13) [hv$1.class:?]
        at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511) [?:?]
        at java.util.concurrent.FutureTask.run(FutureTask.java:266) [?:?]
        at net.minecraft.util.Util.func_181617_a(SourceFile:46) [h.class:?]
        at net.minecraft.server.MinecraftServer.func_71190_q(MinecraftServer.java:904) [MinecraftServer.class:?]
        at net.minecraft.server.dedicated.DedicatedServer.func_71190_q(DedicatedServer.java:475) [nz.class:?]
        at net.minecraft.server.MinecraftServer.func_71217_p(MinecraftServer.java:828) [MinecraftServer.class:?]
        at net.minecraft.server.MinecraftServer.run(MinecraftServer.java:687) [MinecraftServer.class:?]
        at java.lang.Thread.run(Thread.java:855) [?:?]
