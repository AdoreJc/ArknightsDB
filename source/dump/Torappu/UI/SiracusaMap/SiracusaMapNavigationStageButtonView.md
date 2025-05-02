# SiracusaMapNavigationStageButtonView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `GameObject _objEntryLock`

- `UICommonTrackPoint _trackPoint`

- `TrackPointViewProperty m_newProperty`

- `Boolean m_isInited`

- `SiracusaMapController <closure>k__BackingField`


## Properties

- `Boolean showNewIfNeed`

- `SiracusaMapController closure`


## Methods

- `Boolean get_showNewIfNeed()`

- `SiracusaMapController get_closure()`

- `Void set_closure(SiracusaMapController)`

- `Void _InitIfNot()`

- `Boolean _IsEntryLockedShowToast()`

- `String _TryGetLockTips()`

- `Void OnEntryClick()`

- `Void <>xLuaBaseProxy_Render(SiracusaMapNavigationDetailViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapNavigationStageButtonView : SiracusaMapNavigationButtonBaseView
{
	private GameObject _objEntryLock; // 0x38
	private UICommonTrackPoint _trackPoint; // 0x40
	private TrackPointViewProperty m_newProperty; // 0x48
	private Boolean m_isInited; // 0x50
	private SiracusaMapController <closure>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_showNewIfNeed; // 0x0
	private static DelegateBridge __Hotfix0_get_closure; // 0x8
	private static DelegateBridge __Hotfix0_set_closure; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0__IsEntryLockedShowToast; // 0x28
	private static DelegateBridge __Hotfix0__TryGetLockTips; // 0x30
	private static DelegateBridge __Hotfix0_OnEntryClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Boolean showNewIfNeed { get; }
	public SiracusaMapController closure { get; set; }

	// RVA: 0x23dbe34 VA: 0x75949f3e34
	public Boolean get_showNewIfNeed() { }
	// RVA: 0x23dbecc VA: 0x75949f3ecc
	public SiracusaMapController get_closure() { }
	// RVA: 0x23dbf34 VA: 0x75949f3f34
	public Void set_closure(SiracusaMapController value) { }
	// RVA: 0x23dbfb8 VA: 0x75949f3fb8
	private Void _InitIfNot() { }
	// RVA: 0x23dc0a0 VA: 0x75949f40a0
	public override Void Render(SiracusaMapNavigationDetailViewModel viewModel) { }
	// RVA: 0x23dc23c VA: 0x75949f423c
	private Boolean _IsEntryLockedShowToast() { }
	// RVA: 0x23dc3a4 VA: 0x75949f43a4
	private String _TryGetLockTips() { }
	// RVA: 0x23dc63c VA: 0x75949f463c
	public Void OnEntryClick() { }
	// RVA: 0x23dc7a0 VA: 0x75949f47a0
	public Void .ctor() { }
	// RVA: 0x23dc80c VA: 0x75949f480c
	private Void <>xLuaBaseProxy_Render(SiracusaMapNavigationDetailViewModel P0) { }
}
```