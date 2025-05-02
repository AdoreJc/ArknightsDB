# RL02OuterBuffViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic.RL02`


## Fields

- `String selectNodeId`

- `Boolean isPlaying`

- `Int32 activatedNodeCount`

- `Int32 tokenCount`

- `String tokenItemName`

- `Boolean showNodeName`

- `String <topicId>k__BackingField`


## Properties

- `String topicId`

- `Boolean isAllNodeActivated`


## Methods

- `String get_topicId()`

- `Void set_topicId(String)`

- `Boolean get_isAllNodeActivated()`

- `Void LoadData(String)`

- `Void RefreshPlayerData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL02
public class RL02OuterBuffViewModel : IHotfixable
{
	public ListDict`2 nodeModel; // 0x10
	public List`1 lineModel; // 0x18
	public String selectNodeId; // 0x20
	public Boolean isPlaying; // 0x28
	public Int32 activatedNodeCount; // 0x2c
	public Int32 tokenCount; // 0x30
	public String tokenItemName; // 0x38
	public Boolean showNodeName; // 0x40
	private String <topicId>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_set_topicId; // 0x8
	private static DelegateBridge __Hotfix0_get_isAllNodeActivated; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public String topicId { get; set; }
	public Boolean isAllNodeActivated { get; }

	// RVA: 0x26bd3d4 VA: 0x7594cd53d4
	public String get_topicId() { }
	// RVA: 0x26c61f4 VA: 0x7594cde1f4
	private Void set_topicId(String value) { }
	// RVA: 0x26c0860 VA: 0x7594cd8860
	public Boolean get_isAllNodeActivated() { }
	// RVA: 0x26bb6d0 VA: 0x7594cd36d0
	public Void LoadData(String topicId) { }
	// RVA: 0x26bbc88 VA: 0x7594cd3c88
	public Void RefreshPlayerData() { }
	// RVA: 0x26c6358 VA: 0x7594cde358
	public Void .ctor() { }
}
```