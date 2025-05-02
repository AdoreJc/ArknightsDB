# UniEquipShowState

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `UniEquipShowView _showViewPrefab`

- `RectTransform _viewContainer`

- `UniEquipShowStateBean m_stateBean`

- `UniEquipShowView m_uniEquipShowView`


## Methods

- `IEnumerator <>n__0(TransactionContext)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipShowState : PopupFadeState
{
	private UniEquipShowView _showViewPrefab; // 0x70
	private RectTransform _viewContainer; // 0x78
	private UniEquipShowStateBean m_stateBean; // 0x80
	private UniEquipShowView m_uniEquipShowView; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x22fb360 VA: 0x7594913360
	public override IStateBean GetCacheBean() { }
	// RVA: 0x22fb3c8 VA: 0x75949133c8
	protected override Void OnEnter() { }
	// RVA: 0x22fb4ec VA: 0x75949134ec
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x22fb680 VA: 0x7594913680
	public Void .ctor() { }
	// RVA: 0x22fb730 VA: 0x7594913730
	private IEnumerator <>n__0(TransactionContext context) { }
	// RVA: 0x22fb758 VA: 0x7594913758
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x22fb760 VA: 0x7594913760
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
}
```