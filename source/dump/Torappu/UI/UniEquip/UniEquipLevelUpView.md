# UniEquipLevelUpView

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `Image _imgEquip`

- `UniEquipLevelUpSwitchBoardView _switchBoardView`

- `RectTransform _switchBoardViewContainer`

- `SimpleLayoutContent _itemLayoutContent`

- `SimpleLayoutContent _pointLayoutContent`

- `Text _confirmInfoText`

- `AnimationWrapper _animationWrapper`

- `CanvasGroup _itemCanvasGroup`

- `Single _itemFadeDuration`

- `Boolean m_isInited`

- `ItemAdapter m_itemAdapter`

- `PointAdapter m_pointAdapter`

- `UniEquipLevelUpSwitchBoardView m_switchBoardView`

- `Boolean m_isAnimPlaying`

- `Tween m_itemFadeDotween`

- `UIPageFinder m_pageFinder`


## Methods

- `Boolean isAnimPlaying()`

- `Void _InitIfNot()`

- `Void _PlaySelectLevelItemFadeTween()`

- `Void PlayLevelUpAnim(Action)`

- `Single <_PlaySelectLevelItemFadeTween>b__24_0()`

- `Void <_PlaySelectLevelItemFadeTween>b__24_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipLevelUpView : DataBinder`1
{
	private const String ANIM_ITEM_OUT; // 0x0
	private const String ANIM_ITEM_IN; // 0x0
	private const Int32 AVG_FOCUS_ITEM_INDEX; // 0x0
	private Image _imgEquip; // 0x20
	private UniEquipLevelUpSwitchBoardView _switchBoardView; // 0x28
	private RectTransform _switchBoardViewContainer; // 0x30
	private SimpleLayoutContent _itemLayoutContent; // 0x38
	private SimpleLayoutContent _pointLayoutContent; // 0x40
	private Text _confirmInfoText; // 0x48
	private AnimationWrapper _animationWrapper; // 0x50
	private CanvasGroup _itemCanvasGroup; // 0x58
	private Single _itemFadeDuration; // 0x60
	private Boolean m_isInited; // 0x64
	private ItemAdapter m_itemAdapter; // 0x68
	private PointAdapter m_pointAdapter; // 0x70
	private UniEquipLevelUpSwitchBoardView m_switchBoardView; // 0x78
	private Boolean m_isAnimPlaying; // 0x80
	private Tween m_itemFadeDotween; // 0x88
	private UIPageFinder m_pageFinder; // 0x90
	private static DelegateBridge __Hotfix0_isAnimPlaying; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__PlaySelectLevelItemFadeTween; // 0x18
	private static DelegateBridge __Hotfix0_PlayLevelUpAnim; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x23026e0 VA: 0x759491a6e0
	public Boolean isAnimPlaying() { }
	// RVA: 0x2302748 VA: 0x759491a748
	public override Void OnValueChanged(LevelUpViewProperty property) { }
	// RVA: 0x2302954 VA: 0x759491a954
	private Void _InitIfNot() { }
	// RVA: 0x2302b28 VA: 0x759491ab28
	private Void _PlaySelectLevelItemFadeTween() { }
	// RVA: 0x2302cc0 VA: 0x759491acc0
	public Void PlayLevelUpAnim(Action reloadFunc) { }
	// RVA: 0x2302e94 VA: 0x759491ae94
	public Void .ctor() { }
	// RVA: 0x2303078 VA: 0x759491b078
	private Single <_PlaySelectLevelItemFadeTween>b__24_0() { }
	// RVA: 0x2303094 VA: 0x759491b094
	private Void <_PlaySelectLevelItemFadeTween>b__24_1(Single val) { }
}
```