# Act24sideMissionRewardPage

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Act24sideMissionRewardView _viewPrefab`

- `RectTransform _itemContainer`

- `Act24sideMissionRewardView m_view`


## Properties

- `Act24sideMissionRewardView view`


## Methods

- `Act24sideMissionRewardView get_view()`

- `Void _HideItemFloat()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(Boolean)`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMissionRewardPage : UIPage
{
	private Act24sideMissionRewardView _viewPrefab; // 0xd0
	private RectTransform _itemContainer; // 0xd8
	private Act24sideMissionRewardView m_view; // 0xe0
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x0
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x8
	private static DelegateBridge __Hotfix0_get_view; // 0x10
	private static DelegateBridge __Hotfix0__HideItemFloat; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Act24sideMissionRewardView view { get; }

	// RVA: 0x32b9eb4 VA: 0x75958d1eb4
	public override IEnumerator ShowCoroutine(Boolean isFromStack) { }
	// RVA: 0x32b9fa4 VA: 0x75958d1fa4
	protected override IEnumerator HideCoroutine(Boolean isIntoStack) { }
	// RVA: 0x32ba094 VA: 0x75958d2094
	public Act24sideMissionRewardView get_view() { }
	// RVA: 0x32ba280 VA: 0x75958d2280
	private Void _HideItemFloat() { }
	// RVA: 0x32ba2ec VA: 0x75958d22ec
	public Void .ctor() { }
	// RVA: 0x32ba35c VA: 0x75958d235c
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(Boolean P0) { }
	// RVA: 0x32ba368 VA: 0x75958d2368
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(Boolean P0) { }
}
```