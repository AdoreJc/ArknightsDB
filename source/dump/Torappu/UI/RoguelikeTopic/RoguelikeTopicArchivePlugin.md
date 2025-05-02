# RoguelikeTopicArchivePlugin

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicArchivePlugin : ActArchivePlugin
{
	public const String KEY_IS_FROM_ROGUELIKE_ENTRY; // 0x0
	private static DelegateBridge __Hotfix0_GetArchiveEntryType; // 0x0
	private static DelegateBridge __Hotfix0_GetArchiveItemValidStatus; // 0x8
	private static DelegateBridge __Hotfix0_GetArchiveItemLockStatus; // 0x10
	private static DelegateBridge __Hotfix0_GetSceneParamToState; // 0x18
	private static DelegateBridge __Hotfix0_ConstructCompPlugin; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2633068 VA: 0x7594c4b068
	public override ActArchiveType GetArchiveEntryType() { }
	// RVA: 0x26330d0 VA: 0x7594c4b0d0
	public override Boolean GetArchiveItemValidStatus(String archiveId, String archiveItemId, ActArchiveType archiveItemType) { }
	// RVA: 0x2633230 VA: 0x7594c4b230
	public override Boolean GetArchiveItemLockStatus(String archiveId, String archiveItemId, ActArchiveType archiveItemType, out String lockedToast) { }
	// RVA: 0x26337e4 VA: 0x7594c4b7e4
	public override List`1 GetSceneParamToState(String archiveId) { }
	// RVA: 0x2633c70 VA: 0x7594c4bc70
	public override Void ConstructCompPlugin() { }
	// RVA: 0x2633ed8 VA: 0x7594c4bed8
	public Void .ctor() { }
}
```