# RoguelikeDungeonZoneViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeDungeonZone curZone`

- `Int32 curDepth`

- `Int32 curIndex`

- `Boolean isZoneChanged`

- `Boolean showAutoTransition`

- `Boolean showManualTransition`

- `String topicId`

- `Boolean isVariation`

- `Boolean isSpecialZone`


## Properties

- `RoguelikeDungeonNode curNode`


## Methods

- `RoguelikeDungeonNode get_curNode()`

- `Void LoadData(String, Boolean)`

- `Void _CheckAndSetZoneSpecial()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeDungeonZoneViewModel : IHotfixable
{
	public RoguelikeDungeonZone curZone; // 0x10
	public Int32 curDepth; // 0x18
	public Int32 curIndex; // 0x1c
	public Boolean isZoneChanged; // 0x20
	public Boolean showAutoTransition; // 0x21
	public Boolean showManualTransition; // 0x22
	public String topicId; // 0x28
	public Boolean isVariation; // 0x30
	public List`1 variationIdList; // 0x38
	public Boolean isSpecialZone; // 0x40
	private static DelegateBridge __Hotfix0_get_curNode; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0__CheckAndSetZoneSpecial; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public RoguelikeDungeonNode curNode { get; }

	// RVA: 0x2a1912c VA: 0x759503112c
	public RoguelikeDungeonNode get_curNode() { }
	// RVA: 0x2a191ac VA: 0x75950311ac
	public Void LoadData(String topicId, Boolean accessedInitState) { }
	// RVA: 0x2a19420 VA: 0x7595031420
	private Void _CheckAndSetZoneSpecial() { }
	// RVA: 0x2a195cc VA: 0x75950315cc
	public Void .ctor() { }
}
```