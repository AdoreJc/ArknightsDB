# EnemyDuelBetTopBarView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Text _textPing`

- `Text _textRoomName`

- `Int64 _refreshPingInterval`

- `UIAnimationLocation _animEmojiSwitch`

- `EnemyDuelBetTopBarEmoticonBtn _pnlEmoticonBtn`

- `CountDownTask m_countDownTask`

- `Boolean m_inited`

- `UIStateFinder m_stateFinder`

- `UIPageFinder m_pageFinder`

- `UISwitchTween m_emojiDisableSwitchTween`

- `Int32 m_cachedLoadSeqNum`


## Methods

- `Void _InitIfNot()`

- `Void Render(EnemyDuelTopBarViewModel)`

- `Void _UpdatePingInterval()`

- `Void Update()`

- `Void OnExitBtnClicked()`

- `Void OnBtnDisableEmoticonClicked()`

- `Void _RecordGameAnalytics()`

- `Void OnBtnEmoticonClicked()`

- `Void <_InitIfNot>b__13_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelBetTopBarView : MonoBehaviour, IHotfixable
{
	private const String FORMAT_PING; // 0x0
	private Text _textPing; // 0x18
	private Text _textRoomName; // 0x20
	private Int64 _refreshPingInterval; // 0x28
	private UIAnimationLocation _animEmojiSwitch; // 0x30
	private EnemyDuelBetTopBarEmoticonBtn _pnlEmoticonBtn; // 0x40
	private List`1 m_cachedPingConds; // 0x48
	private CountDownTask m_countDownTask; // 0x50
	private Boolean m_inited; // 0x58
	private UIStateFinder m_stateFinder; // 0x60
	private UIPageFinder m_pageFinder; // 0x70
	private UISwitchTween m_emojiDisableSwitchTween; // 0x80
	private Int32 m_cachedLoadSeqNum; // 0x88
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__UpdatePingInterval; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge __Hotfix0_OnExitBtnClicked; // 0x20
	private static DelegateBridge __Hotfix0_OnBtnDisableEmoticonClicked; // 0x28
	private static DelegateBridge __Hotfix0__RecordGameAnalytics; // 0x30
	private static DelegateBridge __Hotfix0_OnBtnEmoticonClicked; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x297f270 VA: 0x7594f97270
	private Void _InitIfNot() { }
	// RVA: 0x297f410 VA: 0x7594f97410
	public Void Render(EnemyDuelTopBarViewModel topBarViewModel) { }
	// RVA: 0x297f52c VA: 0x7594f9752c
	private Void _UpdatePingInterval() { }
	// RVA: 0x297f650 VA: 0x7594f97650
	private Void Update() { }
	// RVA: 0x297f6cc VA: 0x7594f976cc
	public Void OnExitBtnClicked() { }
	// RVA: 0x297f770 VA: 0x7594f97770
	public Void OnBtnDisableEmoticonClicked() { }
	// RVA: 0x297f898 VA: 0x7594f97898
	private Void _RecordGameAnalytics() { }
	// RVA: 0x297fa20 VA: 0x7594f97a20
	public Void OnBtnEmoticonClicked() { }
	// RVA: 0x297fad4 VA: 0x7594f97ad4
	public Void .ctor() { }
	// RVA: 0x297fb4c VA: 0x7594f97b4c
	private Void <_InitIfNot>b__13_0() { }
}
```