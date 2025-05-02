# UICharacterTabGroupAddtion

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UICharacterTabSwitchButton _additionInfoTab`

- `Transform _additionInfoTabDetailPanel`

- `Boolean _moveToFirst`

- `Boolean _refreshTransform`

- `EasyInstancePool _tabItemInstancePool`


## Properties

- `EasyInstancePool tabItemInstancePool`

- `UICharacterInfoPanel characterInfo`


## Methods

- `EasyInstancePool get_tabItemInstancePool()`

- `UICharacterInfoPanel get_characterInfo()`

- `Void OnInit(UIController)`

- `Void EnableTab(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UICharacterTabGroupAddtion : MonoBehaviour, IHotfixable
{
	private UICharacterTabSwitchButton _additionInfoTab; // 0x18
	private Transform _additionInfoTabDetailPanel; // 0x20
	private Boolean _moveToFirst; // 0x28
	private Boolean _refreshTransform; // 0x29
	private EasyInstancePool _tabItemInstancePool; // 0x30
	private static DelegateBridge __Hotfix0_get_tabItemInstancePool; // 0x0
	private static DelegateBridge __Hotfix0_get_characterInfo; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_EnableTab; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public EasyInstancePool tabItemInstancePool { get; }
	private UICharacterInfoPanel characterInfo { get; }

	// RVA: 0x203b028 VA: 0x7594653028
	public EasyInstancePool get_tabItemInstancePool() { }
	// RVA: 0x203b090 VA: 0x7594653090
	private UICharacterInfoPanel get_characterInfo() { }
	// RVA: 0x203b11c VA: 0x759465311c
	public Void OnInit(UIController uiController) { }
	// RVA: 0x203b400 VA: 0x7594653400
	public Void EnableTab(Boolean isActive) { }
	// RVA: 0x203b500 VA: 0x7594653500
	public Void .ctor() { }
}
```