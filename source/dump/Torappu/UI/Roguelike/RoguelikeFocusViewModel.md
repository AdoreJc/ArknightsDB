# RoguelikeFocusViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeDungeonNode focusNode`

- `PlayerNodeForesightType foresightType`

- `RoguelikeEventType renderType`

- `DetailInfo detailInfo`

- `String topicId`

- `String zoneId`

- `String focusStageId`

- `String activeCapsuleId`


## Methods

- `String GetActiveFocusStageId()`

- `Void Clear()`

- `Void LoadCapsule(String)`

- `Void LoadFocusNode(RoguelikeDungeonNode, String)`

- `Void LoadFocusStage(RoguelikeDungeonNode, String, String)`

- `Void LoadDetailContent(RoguelikeDungeonNode)`

- `Void _LoadFocusStageRenderType(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeFocusViewModel : IHotfixable
{
	public RoguelikeDungeonNode focusNode; // 0x10
	public PlayerNodeForesightType foresightType; // 0x18
	public RoguelikeEventType renderType; // 0x1c
	public DetailInfo detailInfo; // 0x20
	public String topicId; // 0x28
	public String zoneId; // 0x30
	public String focusStageId; // 0x38
	public String activeCapsuleId; // 0x40
	private static DelegateBridge __Hotfix0_GetActiveFocusStageId; // 0x0
	private static DelegateBridge __Hotfix0_Clear; // 0x8
	private static DelegateBridge __Hotfix0_LoadCapsule; // 0x10
	private static DelegateBridge __Hotfix0_LoadFocusNode; // 0x18
	private static DelegateBridge __Hotfix0_LoadFocusStage; // 0x20
	private static DelegateBridge __Hotfix0_LoadDetailContent; // 0x28
	private static DelegateBridge __Hotfix0__LoadFocusStageRenderType; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2a196fc VA: 0x75950316fc
	public String GetActiveFocusStageId() { }
	// RVA: 0x2a19788 VA: 0x7595031788
	public Void Clear() { }
	// RVA: 0x2a19818 VA: 0x7595031818
	public Void LoadCapsule(String capsuleId) { }
	// RVA: 0x2a1989c VA: 0x759503189c
	public Void LoadFocusNode(RoguelikeDungeonNode node, String zoneId) { }
	// RVA: 0x2a19cd8 VA: 0x7595031cd8
	public Void LoadFocusStage(RoguelikeDungeonNode node, String focusStageId, String zoneId) { }
	// RVA: 0x2a199c0 VA: 0x75950319c0
	public Void LoadDetailContent(RoguelikeDungeonNode node) { }
	// RVA: 0x2a19e18 VA: 0x7595031e18
	private Void _LoadFocusStageRenderType(String topicId, String focusStageId) { }
	// RVA: 0x2a19ffc VA: 0x7595031ffc
	public Void .ctor() { }
}
```