# HomeBackgroundChangeStateBean

**Namespace:** `Torappu.UI.Home`


## Fields

- `HomeBackgroundChangeViewProperty bgChangeProperty`

- `String presetInstId`

- `String presetBackgroundId`

- `Boolean canChangePos`


## Methods

- `Void LoadData(Boolean)`

- `Void ResortList(Boolean)`

- `Void SelectBg(String)`

- `Void ChangeHideState()`

- `Void _ConsumeNew(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeBackgroundChangeStateBean : IStateBean, IHotfixable
{
	public HomeBackgroundChangeViewProperty bgChangeProperty; // 0x10
	public String presetInstId; // 0x18
	public String presetBackgroundId; // 0x20
	public Boolean canChangePos; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_ResortList; // 0x8
	private static DelegateBridge __Hotfix0_SelectBg; // 0x10
	private static DelegateBridge __Hotfix0_ChangeHideState; // 0x18
	private static DelegateBridge __Hotfix0__CompareUpdateTimeAscend; // 0x20
	private static DelegateBridge __Hotfix0__CompareUpdateTimeDescend; // 0x28
	private static DelegateBridge __Hotfix0__ConsumeNew; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x280b474 VA: 0x7594e23474
	public Void LoadData(Boolean sortByAscend) { }
	// RVA: 0x280b92c VA: 0x7594e2392c
	public Void ResortList(Boolean ascend) { }
	// RVA: 0x280babc VA: 0x7594e23abc
	public Void SelectBg(String bgId) { }
	// RVA: 0x280bd34 VA: 0x7594e23d34
	public Void ChangeHideState() { }
	// RVA: 0x280bde8 VA: 0x7594e23de8
	private static Int32 _CompareUpdateTimeAscend(HomeBackgroundItemModel left, HomeBackgroundItemModel right) { }
	// RVA: 0x280bee4 VA: 0x7594e23ee4
	private static Int32 _CompareUpdateTimeDescend(HomeBackgroundItemModel left, HomeBackgroundItemModel right) { }
	// RVA: 0x280bcb4 VA: 0x7594e23cb4
	private Void _ConsumeNew(String bgId) { }
	// RVA: 0x280bfe0 VA: 0x7594e23fe0
	public Void .ctor() { }
}
```