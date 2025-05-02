# ModuleAdapter

**Namespace:** ` `


## Fields

- `RoguelikeDungeonController m_controller`


## Properties

- `String topicId`


## Methods

- `String get_topicId()`

- `Int64 GetBGMInstId()`

- `RoguelikeDungeonPage GetPage()`

- `RoguelikeDungeonController GetController()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ModuleAdapter : IRoguelikeModuleHost
{
	private RoguelikeDungeonController m_controller; // 0x10

	public String topicId { get; }

	// RVA: 0x2aa8448 VA: 0x75950c0448
	public Void .ctor(RoguelikeDungeonController ctrller) { }
	// RVA: 0x2aad564 VA: 0x75950c5564
	public String get_topicId() { }
	// RVA: 0x2aad57c VA: 0x75950c557c
	public Int64 GetBGMInstId() { }
	// RVA: 0x2aad600 VA: 0x75950c5600
	public RoguelikeDungeonPage GetPage() { }
	// RVA: 0x2aad6d0 VA: 0x75950c56d0
	public RoguelikeDungeonController GetController() { }
}
```