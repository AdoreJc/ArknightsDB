# SandboxV2BasementUpgradeView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Text _textUnlockFunc`

- `SimpleLayoutContent _funcContent`

- `Text _curLevel`

- `Text _nextLevel`

- `Text _detailNextLevel`

- `GameObject _conditionPanel`

- `SimpleLayoutContent _unlockItemContent`

- `Single _itemScaler`

- `Button _upgradeBtn`

- `AnimationWrapper _animWrapper`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `SandboxV2BasementUpgradeFuncGroupAdapter m_groupAdapter`

- `SandboxV2BasementUpgradeItemAdapter m_itemAdapter`

- `SandboxV2BasementUpgradeViewModel m_cachedViewModel`

- `Boolean m_isInited`

- `String m_topicId`

- `Boolean m_upgradeAble`


## Properties

- `AnimationWrapper animWrapper`


## Methods

- `Void _InitIfNot()`

- `Void _Render(SandboxV2BasementUpgradeViewModel)`

- `Void _PlayEntryAnim()`

- `Void _ItemClickEvent(Int32)`

- `Void _CloseState()`

- `Void EventOnUpgradeBtnClick()`

- `Void EventOnUpgradeDetailBackClick()`

- `AnimationWrapper get_animWrapper()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2BasementUpgradeView : DataBinder`1
{
	private Text _textUnlockFunc; // 0x20
	private SimpleLayoutContent _funcContent; // 0x28
	private Text _curLevel; // 0x30
	private Text _nextLevel; // 0x38
	private Text _detailNextLevel; // 0x40
	private Text[] _upgradeConditions; // 0x48
	private GameObject _conditionPanel; // 0x50
	private SimpleLayoutContent _unlockItemContent; // 0x58
	private Single _itemScaler; // 0x60
	private Button _upgradeBtn; // 0x68
	private AnimationWrapper _animWrapper; // 0x70
	private const String ANIM_ENTRY; // 0x0
	private const String ANIM_UPGRADE_FINISH; // 0x0
	private UIPageFinder m_pageFinder; // 0x78
	private UIStateFinder m_stateFinder; // 0x88
	private SandboxV2BasementUpgradeFuncGroupAdapter m_groupAdapter; // 0x98
	private SandboxV2BasementUpgradeItemAdapter m_itemAdapter; // 0xa0
	private SandboxV2BasementUpgradeViewModel m_cachedViewModel; // 0xa8
	private Boolean m_isInited; // 0xb0
	private String m_topicId; // 0xb8
	private Boolean m_upgradeAble; // 0xc0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__Render; // 0x10
	private static DelegateBridge __Hotfix0__PlayEntryAnim; // 0x18
	private static DelegateBridge __Hotfix0__ItemClickEvent; // 0x20
	private static DelegateBridge __Hotfix0__CloseState; // 0x28
	private static DelegateBridge __Hotfix0_EventOnUpgradeBtnClick; // 0x30
	private static DelegateBridge __Hotfix0_EventOnUpgradeDetailBackClick; // 0x38
	private static DelegateBridge __Hotfix0_get_animWrapper; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public AnimationWrapper animWrapper { get; }

	// RVA: 0x250f4c0 VA: 0x7594b274c0
	public override Void OnValueChanged(SandboxV2BasementUpgradeProperty property) { }
	// RVA: 0x250f614 VA: 0x7594b27614
	private Void _InitIfNot() { }
	// RVA: 0x250f868 VA: 0x7594b27868
	private Void _Render(SandboxV2BasementUpgradeViewModel viewModel) { }
	// RVA: 0x2510010 VA: 0x7594b28010
	private Void _PlayEntryAnim() { }
	// RVA: 0x2510328 VA: 0x7594b28328
	private Void _ItemClickEvent(Int32 idx) { }
	// RVA: 0x2510120 VA: 0x7594b28120
	private Void _CloseState() { }
	// RVA: 0x2510420 VA: 0x7594b28420
	public Void EventOnUpgradeBtnClick() { }
	// RVA: 0x251052c VA: 0x7594b2852c
	public Void EventOnUpgradeDetailBackClick() { }
	// RVA: 0x250d674 VA: 0x7594b25674
	public AnimationWrapper get_animWrapper() { }
	// RVA: 0x25105d4 VA: 0x7594b285d4
	public Void .ctor() { }
}
```