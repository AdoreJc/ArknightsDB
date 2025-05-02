# UniEquipShowPage

**Namespace:** `Torappu.Scripts.UI.UniEquip`


## Fields

- `UniEquipShowView _showViewPrefab`

- `RectTransform _viewContainer`

- `EffectLightInstHolder _effectLightInstHolder`

- `UniEquipShowView m_uniEquipShowView`


## Properties

- `UniEquipShowView showView`


## Methods

- `UniEquipShowView get_showView()`

- `Void OnConfirmBtnClick()`

- `Void OnBlankClick()`

- `Void <>xLuaBaseProxy_OnStart()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(Boolean)`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Scripts.UI.UniEquip
public class UniEquipShowPage : UIPage
{
	private UniEquipShowView _showViewPrefab; // 0xd0
	private RectTransform _viewContainer; // 0xd8
	private EffectLightInstHolder _effectLightInstHolder; // 0xe0
	private UniEquipShowView m_uniEquipShowView; // 0xe8
	private static DelegateBridge __Hotfix0_get_showView; // 0x0
	private static DelegateBridge __Hotfix0_OnStart; // 0x8
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_OnConfirmBtnClick; // 0x20
	private static DelegateBridge __Hotfix0_OnBlankClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public UniEquipShowView showView { get; }

	// RVA: 0x376e2c8 VA: 0x7595d862c8
	public UniEquipShowView get_showView() { }
	// RVA: 0x376e3c4 VA: 0x7595d863c4
	protected override Void OnStart() { }
	// RVA: 0x376e490 VA: 0x7595d86490
	public override IEnumerator ShowCoroutine(Boolean isFromStack) { }
	// RVA: 0x376e580 VA: 0x7595d86580
	protected override IEnumerator HideCoroutine(Boolean isIntoStack) { }
	// RVA: 0x376e670 VA: 0x7595d86670
	public Void OnConfirmBtnClick() { }
	// RVA: 0x376e6dc VA: 0x7595d866dc
	public Void OnBlankClick() { }
	// RVA: 0x376e748 VA: 0x7595d86748
	public Void .ctor() { }
	// RVA: 0x376e7b8 VA: 0x7595d867b8
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x376e7c0 VA: 0x7595d867c0
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(Boolean P0) { }
	// RVA: 0x376e7cc VA: 0x7595d867cc
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(Boolean P0) { }
}
```