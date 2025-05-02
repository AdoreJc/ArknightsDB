# Act5D1RuneUnlockState

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Act5D1RuneUnlockStateBean _stateBean`

- `Text _priceText`

- `Act5D1RuneShowObj _showObj`

- `Transform _container`

- `GameObject _availPart`

- `GameObject _notAvailPart`

- `Button _unlockBtn`

- `Act5D1ResourceBar _resourceBar`

- `Act5D1RuneUnlockNotify _notify`

- `Text _price`

- `Act5D1RuneShowObj m_showObj`


## Methods

- `Void _InitIfNot()`

- `Void _CheckAvailInfo()`

- `Void OnClick()`

- `Void <OnEnter>b__12_0()`

- `Void <OnClick>b__16_0(Act5D1BuyRuneResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1RuneUnlockState : PopupFloatState
{
	private Act5D1RuneUnlockStateBean _stateBean; // 0x70
	private Text _priceText; // 0x78
	private Act5D1RuneShowObj _showObj; // 0x80
	private Transform _container; // 0x88
	private GameObject _availPart; // 0x90
	private GameObject _notAvailPart; // 0x98
	private Button _unlockBtn; // 0xa0
	private Act5D1ResourceBar _resourceBar; // 0xa8
	private Act5D1RuneUnlockNotify _notify; // 0xb0
	private Text _price; // 0xb8
	private Act5D1RuneShowObj m_showObj; // 0xc0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__CheckAvailInfo; // 0x18
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x20
	private static DelegateBridge __Hotfix0_OnClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x31d143c VA: 0x75957e943c
	private Void _InitIfNot() { }
	// RVA: 0x31d1540 VA: 0x75957e9540
	protected override Void OnEnter() { }
	// RVA: 0x31d1628 VA: 0x75957e9628
	protected override Void OnResume() { }
	// RVA: 0x31d169c VA: 0x75957e969c
	private Void _CheckAvailInfo() { }
	// RVA: 0x31d1878 VA: 0x75957e9878
	public override IStateBean GetCacheBean() { }
	// RVA: 0x31d18e0 VA: 0x75957e98e0
	public Void OnClick() { }
	// RVA: 0x31d1b24 VA: 0x75957e9b24
	public Void .ctor() { }
	// RVA: 0x31d1bd0 VA: 0x75957e9bd0
	private Void <OnEnter>b__12_0() { }
	// RVA: 0x31d1c24 VA: 0x75957e9c24
	private Void <OnClick>b__16_0(Act5D1BuyRuneResponse response) { }
	// RVA: 0x31d1cf4 VA: 0x75957e9cf4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x31d1cfc VA: 0x75957e9cfc
	private Void <>xLuaBaseProxy_OnResume() { }
}
```