# ClimbTowerEndingTopState

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerEndingTopView _endingTopView`

- `ClimbTowerEndingTopStateBean m_stateBean`


## Methods

- `Void set_cachedCoroutine(List`1)`

- `Void OnClick()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnPause()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEndingTopState : PopupFloatState, IHotfixable
{
	private ClimbTowerEndingTopView _endingTopView; // 0x70
	private ClimbTowerEndingTopStateBean m_stateBean; // 0x78
	private List`1 <cachedCoroutine>k__BackingField; // 0x80
	private static DelegateBridge __Hotfix0_get_cachedCoroutine; // 0x0
	private static DelegateBridge __Hotfix0_set_cachedCoroutine; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnResume; // 0x20
	private static DelegateBridge __Hotfix0_OnPause; // 0x28
	private static DelegateBridge __Hotfix0_OnClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public List`1 cachedCoroutine { get; set; }

	// RVA: 0x2c9ea6c VA: 0x75952b6a6c
	public List`1 get_cachedCoroutine() { }
	// RVA: 0x2c9ead4 VA: 0x75952b6ad4
	private Void set_cachedCoroutine(List`1 value) { }
	// RVA: 0x2c9eb58 VA: 0x75952b6b58
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2c9ebc0 VA: 0x75952b6bc0
	protected override Void OnEnter() { }
	// RVA: 0x2c9f2e8 VA: 0x75952b72e8
	protected override Void OnResume() { }
	// RVA: 0x2c9f504 VA: 0x75952b7504
	protected override Void OnPause() { }
	// RVA: 0x2c9f654 VA: 0x75952b7654
	public Void OnClick() { }
	// RVA: 0x2c9f7d8 VA: 0x75952b77d8
	public Void .ctor() { }
	// RVA: 0x2c9f930 VA: 0x75952b7930
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2c9f938 VA: 0x75952b7938
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2c9f940 VA: 0x75952b7940
	private Void <>xLuaBaseProxy_OnPause() { }
}
```