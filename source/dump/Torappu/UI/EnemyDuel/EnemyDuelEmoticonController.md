# EnemyDuelEmoticonController

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `UIPageFinder m_pageFinder`

- `Single m_chatCd`

- `Boolean m_inited`

- `EnemyDuelBattleCoolDownController m_coolDownController`

- `StateEngine <bindStateEngine>k__BackingField`


## Properties

- `StateEngine bindStateEngine`


## Methods

- `Void _InitIfNot()`

- `StateEngine get_bindStateEngine()`

- `Void set_bindStateEngine(StateEngine)`

- `Void OnShowEmoticonPanel()`

- `Void OnBtnCloseEmoticonClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelEmoticonController : EmoticonPagerPanelBaseController
{
	private UIPageFinder m_pageFinder; // 0x68
	private Single m_chatCd; // 0x78
	private Boolean m_inited; // 0x7c
	private EnemyDuelBattleCoolDownController m_coolDownController; // 0x80
	private StateEngine <bindStateEngine>k__BackingField; // 0x88
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_get_bindStateEngine; // 0x8
	private static DelegateBridge __Hotfix0_set_bindStateEngine; // 0x10
	private static DelegateBridge __Hotfix0_OnShowEmoticonPanel; // 0x18
	private static DelegateBridge __Hotfix0__OnSendEmoji; // 0x20
	private static DelegateBridge __Hotfix0_OnBtnCloseEmoticonClicked; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public StateEngine bindStateEngine { get; set; }

	// RVA: 0x2984088 VA: 0x7594f9c088
	private Void _InitIfNot() { }
	// RVA: 0x2984190 VA: 0x7594f9c190
	public StateEngine get_bindStateEngine() { }
	// RVA: 0x29841f8 VA: 0x7594f9c1f8
	public Void set_bindStateEngine(StateEngine value) { }
	// RVA: 0x298427c VA: 0x7594f9c27c
	public Void OnShowEmoticonPanel() { }
	// RVA: 0x2984450 VA: 0x7594f9c450
	protected override Void _OnSendEmoji(String themeId, String emojiItem) { }
	// RVA: 0x29846c4 VA: 0x7594f9c6c4
	public Void OnBtnCloseEmoticonClicked() { }
	// RVA: 0x2984738 VA: 0x7594f9c738
	public Void .ctor() { }
}
```