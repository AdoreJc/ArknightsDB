# RL04FragmentGainView

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `RL04FragmentDetailCard _detailCardPrefab`

- `RectTransform _cardContainer`

- `GameObject _nextBtnObj`

- `GameObject _closeBtnObj`

- `UIAnimationLocation _anim`

- `ILoadAsset <loader>k__BackingField`

- `Action <onNextBtnClick>k__BackingField`

- `Action <onCloseBtnClick>k__BackingField`

- `Boolean m_hasInited`

- `Int32 m_cachedShowIndex`

- `RL04FragmentDetailCard m_detailCard`

- `Tween m_animTween`


## Properties

- `ILoadAsset loader`

- `Action onNextBtnClick`

- `Action onCloseBtnClick`


## Methods

- `ILoadAsset get_loader()`

- `Void set_loader(ILoadAsset)`

- `Void set_onNextBtnClick(Action)`

- `Action get_onNextBtnClick()`

- `Void set_onCloseBtnClick(Action)`

- `Action get_onCloseBtnClick()`

- `Void EventOnNextBtnClick()`

- `Void EventOnCloseBtnClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04FragmentGainView : DataBinder`1, IHotfixable
{
	private RL04FragmentDetailCard _detailCardPrefab; // 0x20
	private RectTransform _cardContainer; // 0x28
	private GameObject _nextBtnObj; // 0x30
	private GameObject _closeBtnObj; // 0x38
	private UIAnimationLocation _anim; // 0x40
	private ILoadAsset <loader>k__BackingField; // 0x50
	private Action <onNextBtnClick>k__BackingField; // 0x58
	private Action <onCloseBtnClick>k__BackingField; // 0x60
	private Boolean m_hasInited; // 0x68
	private Int32 m_cachedShowIndex; // 0x6c
	private RL04FragmentDetailCard m_detailCard; // 0x70
	private Tween m_animTween; // 0x78
	private static DelegateBridge __Hotfix0_get_loader; // 0x0
	private static DelegateBridge __Hotfix0_set_loader; // 0x8
	private static DelegateBridge __Hotfix0_set_onNextBtnClick; // 0x10
	private static DelegateBridge __Hotfix0_get_onNextBtnClick; // 0x18
	private static DelegateBridge __Hotfix0_set_onCloseBtnClick; // 0x20
	private static DelegateBridge __Hotfix0_get_onCloseBtnClick; // 0x28
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x30
	private static DelegateBridge __Hotfix0_EventOnNextBtnClick; // 0x38
	private static DelegateBridge __Hotfix0_EventOnCloseBtnClick; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private ILoadAsset loader { get; set; }
	private Action onNextBtnClick { get; set; }
	private Action onCloseBtnClick { get; set; }

	// RVA: 0x2b2339c VA: 0x759513b39c
	private ILoadAsset get_loader() { }
	// RVA: 0x2b22eb8 VA: 0x759513aeb8
	public Void set_loader(ILoadAsset value) { }
	// RVA: 0x2b22f3c VA: 0x759513af3c
	public Void set_onNextBtnClick(Action value) { }
	// RVA: 0x2b23404 VA: 0x759513b404
	private Action get_onNextBtnClick() { }
	// RVA: 0x2b22fc0 VA: 0x759513afc0
	public Void set_onCloseBtnClick(Action value) { }
	// RVA: 0x2b2346c VA: 0x759513b46c
	private Action get_onCloseBtnClick() { }
	// RVA: 0x2b234d4 VA: 0x759513b4d4
	public override Void OnValueChanged(RL04FragmentGainProperty property) { }
	// RVA: 0x2b23854 VA: 0x759513b854
	public Void EventOnNextBtnClick() { }
	// RVA: 0x2b238f0 VA: 0x759513b8f0
	public Void EventOnCloseBtnClick() { }
	// RVA: 0x2b236b4 VA: 0x759513b6b4
	private Void _InitIfNot() { }
	// RVA: 0x2b2398c VA: 0x759513b98c
	public Void .ctor() { }
}
```