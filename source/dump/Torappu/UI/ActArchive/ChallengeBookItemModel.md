# ChallengeBookItemModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String storyId`

- `String challengeName`

- `String storyName`

- `String textId`

- `Int32 sortId`

- `IActArchiveChallengeBookPlugin m_plugin`


## Methods

- `Int32 CompareTo(Object)`

- `String <>xLuaBaseProxy_GetTrackType(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ChallengeBookItemModel : ArchiveItemModel, IComparable
{
	public String storyId; // 0x30
	public String challengeName; // 0x38
	public String storyName; // 0x40
	public String textId; // 0x48
	public Int32 sortId; // 0x50
	private IActArchiveChallengeBookPlugin m_plugin; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetFuncId; // 0x8
	private static DelegateBridge __Hotfix0_GetDesc; // 0x10
	private static DelegateBridge __Hotfix0_GetTrackType; // 0x18
	private static DelegateBridge __Hotfix0_CompareTo; // 0x20


	// RVA: 0x303e9f8 VA: 0x75956569f8
	public Void .ctor(IActArchiveChallengeBookPlugin plugin) { }
	// RVA: 0x303ea8c VA: 0x7595656a8c
	public override String GetFuncId() { }
	// RVA: 0x303eaf4 VA: 0x7595656af4
	public override String GetDesc() { }
	// RVA: 0x303eb5c VA: 0x7595656b5c
	public override String GetTrackType(String archiveId) { }
	// RVA: 0x303ec68 VA: 0x7595656c68
	public Int32 CompareTo(Object obj) { }
	// RVA: 0x303ed64 VA: 0x7595656d64
	private String <>xLuaBaseProxy_GetTrackType(String P0) { }
}
```