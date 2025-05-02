# CharacterInfoRightEvolvePotentialView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharacterInfoHomeEvolveView _evolveView`

- `CharacterInfoHomePotentialView _potentialView`

- `CharacterInfoHomePotentialDetailView _detailView`

- `GameObject _evolveButtonPanel`

- `GameObject _transButtonPanel`

- `Single _preferHeight`


## Methods

- `Void _OnHide()`

- `Void _OnShow()`

- `Void OnStateClick()`

- `Void OnClickHide()`

- `Void OnClickShow()`

- `Void <>xLuaBaseProxy_AllHide()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoRightEvolvePotentialView : CharacterInfoCommonObj, IHotfixable
{
	private CharacterInfoHomeEvolveView _evolveView; // 0x30
	private CharacterInfoHomePotentialView _potentialView; // 0x38
	private CharacterInfoHomePotentialDetailView _detailView; // 0x40
	private GameObject _evolveButtonPanel; // 0x48
	private GameObject _transButtonPanel; // 0x50
	private Single _preferHeight; // 0x58
	private static DelegateBridge __Hotfix0_AllHide; // 0x0
	private static DelegateBridge __Hotfix0_GetHeight; // 0x8
	private static DelegateBridge __Hotfix0_ApplyViewModel; // 0x10
	private static DelegateBridge __Hotfix0__OnHide; // 0x18
	private static DelegateBridge __Hotfix0__OnShow; // 0x20
	private static DelegateBridge __Hotfix0_OnStateClick; // 0x28
	private static DelegateBridge __Hotfix0_OnClickHide; // 0x30
	private static DelegateBridge __Hotfix0_OnClickShow; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2d80fb0 VA: 0x7595398fb0
	public override Void AllHide() { }
	// RVA: 0x2d81134 VA: 0x7595399134
	public override Single GetHeight() { }
	// RVA: 0x2d811c4 VA: 0x75953991c4
	public override Void ApplyViewModel(CharViewModel charViewModel) { }
	// RVA: 0x2d81084 VA: 0x7595399084
	private Void _OnHide() { }
	// RVA: 0x2d813ec VA: 0x75953993ec
	private Void _OnShow() { }
	// RVA: 0x2d81498 VA: 0x7595399498
	public Void OnStateClick() { }
	// RVA: 0x2d815f0 VA: 0x75953995f0
	public Void OnClickHide() { }
	// RVA: 0x2d81658 VA: 0x7595399658
	public Void OnClickShow() { }
	// RVA: 0x2d816c0 VA: 0x75953996c0
	public Void .ctor() { }
	// RVA: 0x2d8179c VA: 0x759539979c
	private Void <>xLuaBaseProxy_AllHide() { }
}
```