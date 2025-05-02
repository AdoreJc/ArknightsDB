# ArchiveCapsuleController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveCapsuleListDataBinder _capsuleDataBinder`

- `Image _imgBkg`


## Properties

- `String archiveId`


## Methods

- `Void set_onCapsuleItemClicked(Action`2)`

- `String get_archiveId()`

- `Void <>xLuaBaseProxy_OnItemClick(String)`

- `Void <>xLuaBaseProxy_Init(ActArchiveProxy)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveCapsuleController : ActArchiveController
{
	private ArchiveCapsuleListDataBinder _capsuleDataBinder; // 0x38
	private Image _imgBkg; // 0x40
	private Action`2 <onCapsuleItemClicked>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_onCapsuleItemClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onCapsuleItemClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_archiveId; // 0x10
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x18
	private static DelegateBridge __Hotfix0_InitAndAchieveDataBinders; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action`2 onCapsuleItemClicked { get; set; }
	public String archiveId { get; }

	// RVA: 0x303a714 VA: 0x7595652714
	private Action`2 get_onCapsuleItemClicked() { }
	// RVA: 0x303a77c VA: 0x759565277c
	public Void set_onCapsuleItemClicked(Action`2 value) { }
	// RVA: 0x303a800 VA: 0x7595652800
	public String get_archiveId() { }
	// RVA: 0x303a874 VA: 0x7595652874
	public override Void OnItemClick(String funcId) { }
	// RVA: 0x303a930 VA: 0x7595652930
	public List`1 InitAndAchieveDataBinders() { }
	// RVA: 0x303aae0 VA: 0x7595652ae0
	public override Void Init(ActArchiveProxy proxy) { }
	// RVA: 0x303ab94 VA: 0x7595652b94
	public Void .ctor() { }
	// RVA: 0x303ac04 VA: 0x7595652c04
	private Void <>xLuaBaseProxy_OnItemClick(String P0) { }
	// RVA: 0x303ac0c VA: 0x7595652c0c
	private Void <>xLuaBaseProxy_Init(ActArchiveProxy P0) { }
}
```