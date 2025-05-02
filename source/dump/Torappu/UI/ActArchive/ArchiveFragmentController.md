# ArchiveFragmentController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveFragmentListView _fragmentList`

- `ArchiveFragmentInfoView _fragmentInfo`


## Methods

- `Void set_onItemClicked(Action`1)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveFragmentController : ActArchiveController, IHotfixable
{
	private ArchiveFragmentListView _fragmentList; // 0x38
	private ArchiveFragmentInfoView _fragmentInfo; // 0x40
	private Action`1 <onItemClicked>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_onItemClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_InitAndAchieveDataBinder; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onItemClicked { get; set; }

	// RVA: 0x3053600 VA: 0x759566b600
	private Action`1 get_onItemClicked() { }
	// RVA: 0x3053668 VA: 0x759566b668
	public Void set_onItemClicked(Action`1 value) { }
	// RVA: 0x30536ec VA: 0x759566b6ec
	public override Void OnEnter() { }
	// RVA: 0x30537fc VA: 0x759566b7fc
	public List`1 InitAndAchieveDataBinder() { }
	// RVA: 0x3053974 VA: 0x759566b974
	public Void .ctor() { }
	// RVA: 0x30539e4 VA: 0x759566b9e4
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```