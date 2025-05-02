# ChallengeBookCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ChallengeBookProperty challengeBook`


## Methods

- `Void SetSelectedStoryId(String)`

- `Boolean <>xLuaBaseProxy_HasNewItem()`

- `Boolean <>xLuaBaseProxy_NeedClosePageOnBack()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ChallengeBookCompInfo : ActArchiveCompInfo
{
	public ChallengeBookProperty challengeBook; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_SetSelectedStoryId; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x18
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x20
	private static DelegateBridge __Hotfix0_IsValid; // 0x28
	private static DelegateBridge __Hotfix0_HasNewItem; // 0x30
	private static DelegateBridge __Hotfix0_NeedClosePageOnBack; // 0x38


	// RVA: 0x303f960 VA: 0x7595657960
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x303f9e8 VA: 0x75956579e8
	public Void SetSelectedStoryId(String storyId) { }
	// RVA: 0x303facc VA: 0x7595657acc
	public override Void LoadData(String archiveId) { }
	// RVA: 0x303fc08 VA: 0x7595657c08
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x303fcb8 VA: 0x7595657cb8
	public override Void NotifyUpdate() { }
	// RVA: 0x303fd60 VA: 0x7595657d60
	public override Boolean IsValid() { }
	// RVA: 0x303fdec VA: 0x7595657dec
	public override Boolean HasNewItem() { }
	// RVA: 0x303ff24 VA: 0x7595657f24
	public override Boolean NeedClosePageOnBack() { }
	// RVA: 0x3040078 VA: 0x7595658078
	private Boolean <>xLuaBaseProxy_HasNewItem() { }
	// RVA: 0x3040080 VA: 0x7595658080
	private Boolean <>xLuaBaseProxy_NeedClosePageOnBack() { }
}
```