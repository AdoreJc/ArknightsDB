# RoguelikeActivitySeedModePanel

**Namespace:** `Torappu.UI.RoguelikeTopic.Activity.SeedMode`


## Fields

- `RectTransform _backRect`

- `RoguelikeActivitySeedModePanelView _view`

- `RoguelikeActivitySeedModePanelProperty m_prop`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `Int32 m_inputSeedDialogInst`

- `Int32 m_seedListDialogInst`


## Methods

- `Void _InitIfNot()`

- `Void _OnClickInputSeed()`

- `Void _OnClickDisableSeed()`

- `Void _OnClickEnableSeedGrade()`

- `Void _OnClickOpenSelectSeedDialog()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Activity.SeedMode
public class RoguelikeActivitySeedModePanel : RoguelikeTopicActivityPanel
{
	private const Int32 INPUT_SEED_MAX_CNT; // 0x0
	private RectTransform _backRect; // 0x28
	private RoguelikeActivitySeedModePanelView _view; // 0x30
	private RoguelikeActivitySeedModePanelProperty m_prop; // 0x38
	private Boolean m_isInited; // 0x40
	private UIPageFinder m_pageFinder; // 0x48
	private Int32 m_inputSeedDialogInst; // 0x58
	private Int32 m_seedListDialogInst; // 0x5c
	private static DelegateBridge __Hotfix0__InitPanel; // 0x0
	private static DelegateBridge __Hotfix0__UpdatePanel; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__OnClickInputSeed; // 0x18
	private static DelegateBridge __Hotfix0__OnClickDisableSeed; // 0x20
	private static DelegateBridge __Hotfix0__OnClickEnableSeedGrade; // 0x28
	private static DelegateBridge __Hotfix0__OnClickOpenSelectSeedDialog; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x26de57c VA: 0x7594cf657c
	protected override Void _InitPanel(String topicId, String rlActId) { }
	// RVA: 0x26de90c VA: 0x7594cf690c
	protected override Void _UpdatePanel() { }
	// RVA: 0x26de638 VA: 0x7594cf6638
	private Void _InitIfNot() { }
	// RVA: 0x26decb4 VA: 0x7594cf6cb4
	private Void _OnClickInputSeed() { }
	// RVA: 0x26df0cc VA: 0x7594cf70cc
	private Void _OnClickDisableSeed() { }
	// RVA: 0x26df3a8 VA: 0x7594cf73a8
	private Void _OnClickEnableSeedGrade() { }
	// RVA: 0x26df4e8 VA: 0x7594cf74e8
	private Void _OnClickOpenSelectSeedDialog() { }
	// RVA: 0x26df740 VA: 0x7594cf7740
	public Void .ctor() { }
}
```