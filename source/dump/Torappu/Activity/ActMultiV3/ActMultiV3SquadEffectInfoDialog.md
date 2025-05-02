# ActMultiV3SquadEffectInfoDialog

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `ActMultiV3SquadEffectInfoView _infoViewPrefab`

- `Transform _infoViewContainer`

- `ActMultiV3SquadEffectItemView _effectItemViewPrefab`

- `RectTransform _backBtnRect`

- `Boolean m_isInited`

- `ActMultiV3SquadEffectInfoView m_infoView`

- `ViewModel m_viewModel`


## Methods

- `Void _InitIfNot()`

- `Void _OnItemClick(ActMultiV3SquadEffectModel, Param)`

- `Void _Refresh(ViewModel)`

- `Void Close()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3SquadEffectInfoDialog : UICompDialog`1
{
	private ActMultiV3SquadEffectInfoView _infoViewPrefab; // 0x48
	private Transform _infoViewContainer; // 0x50
	private ActMultiV3SquadEffectItemView _effectItemViewPrefab; // 0x58
	private Transform[] _effecItemContainers; // 0x60
	private RectTransform _backBtnRect; // 0x68
	private Boolean m_isInited; // 0x70
	private ActMultiV3SquadEffectItemView[] m_itemViews; // 0x78
	private ActMultiV3SquadEffectInfoView m_infoView; // 0x80
	private ViewModel m_viewModel; // 0x88
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__OnItemClick; // 0x10
	private static DelegateBridge __Hotfix0__Refresh; // 0x18
	private static DelegateBridge __Hotfix0_Close; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x30e5a34 VA: 0x75956fda34
	protected override Void OnRender(Option input) { }
	// RVA: 0x30e5b9c VA: 0x75956fdb9c
	private Void _InitIfNot() { }
	// RVA: 0x30e64d8 VA: 0x75956fe4d8
	private Void _OnItemClick(ActMultiV3SquadEffectModel effectModel, Param param) { }
	// RVA: 0x30e6318 VA: 0x75956fe318
	private Void _Refresh(ViewModel viewModel) { }
	// RVA: 0x30e6640 VA: 0x75956fe640
	public Void Close() { }
	// RVA: 0x30e6714 VA: 0x75956fe714
	public Void .ctor() { }
}
```