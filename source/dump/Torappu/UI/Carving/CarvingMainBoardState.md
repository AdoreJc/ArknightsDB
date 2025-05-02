# CarvingMainBoardState

**Namespace:** `Torappu.UI.Carving`


## Fields

- `CarvingMainBoardView _boardView`

- `CarvingMainCardDeskView _cardDeskView`

- `Single _cardSlotShowAnimDelay`

- `UIAnimationLocation _showAnimLocation`

- `CarvingMainCardDetailBlocker _cardDetailBlocker`

- `UIPageFinder m_pageFinder`

- `CarvingMainBoardStateBean m_stateBean`

- `Int32 m_showAnimSeqNum`

- `Tween m_showTween`

- `String m_actId`

- `Boolean m_isInited`

- `Int32 m_dialogueInstId`


## Methods

- `Boolean _TriggerTutorialAVG()`

- `Void _TryOpenIntroDialogue(Story)`

- `Void _InitIfNot(CarvingMainPage)`

- `Void _PlayShowAnim()`

- `Void <RegisterFromDataListener>b__25_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPreResume(Boolean)`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainBoardState : UIPopupState, IHotfixable
{
	private CarvingMainBoardView _boardView; // 0x60
	private CarvingMainCardDeskView _cardDeskView; // 0x68
	private Single _cardSlotShowAnimDelay; // 0x70
	private UIAnimationLocation _showAnimLocation; // 0x78
	private CarvingMainCardDetailBlocker _cardDetailBlocker; // 0x88
	private UIPageFinder m_pageFinder; // 0x90
	private CarvingMainBoardStateBean m_stateBean; // 0xa0
	private Int32 m_showAnimSeqNum; // 0xa8
	private Tween m_showTween; // 0xb0
	private String m_actId; // 0xb8
	private Boolean m_isInited; // 0xc0
	private Int32 m_dialogueInstId; // 0xc4
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnPreResume; // 0x10
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x18
	private static DelegateBridge __Hotfix0_OnResume; // 0x20
	private static DelegateBridge __Hotfix0__TriggerTutorialAVG; // 0x28
	private static DelegateBridge __Hotfix0__TryOpenIntroDialogue; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0__PlayShowAnim; // 0x40
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x48
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x50
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x58
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x60
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x2d9a040 VA: 0x75953b2040
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d9a0a8 VA: 0x75953b20a8
	protected override Void OnEnter() { }
	// RVA: 0x2d9a71c VA: 0x75953b271c
	protected override Void OnPreResume(Boolean isFromStack) { }
	// RVA: 0x2d9aec4 VA: 0x75953b2ec4
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x2d9af40 VA: 0x75953b2f40
	protected override Void OnResume() { }
	// RVA: 0x2d9a974 VA: 0x75953b2974
	private Boolean _TriggerTutorialAVG() { }
	// RVA: 0x2d9ab2c VA: 0x75953b2b2c
	private Void _TryOpenIntroDialogue(Story story) { }
	// RVA: 0x2d9a2e0 VA: 0x75953b22e0
	private Void _InitIfNot(CarvingMainPage page) { }
	// RVA: 0x2d9a490 VA: 0x75953b2490
	private Void _PlayShowAnim() { }
	// RVA: 0x2d9b134 VA: 0x75953b3134
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2d9b2ac VA: 0x75953b32ac
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2d9b424 VA: 0x75953b3424
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x2d9b530 VA: 0x75953b3530
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2d9b63c VA: 0x75953b363c
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x2d9b7b4 VA: 0x75953b37b4
	public Void .ctor() { }
	// RVA: 0x2d9b86c VA: 0x75953b386c
	private Void <RegisterFromDataListener>b__25_0(IStateBean sb) { }
	// RVA: 0x2d9b884 VA: 0x75953b3884
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2d9b88c VA: 0x75953b388c
	private Void <>xLuaBaseProxy_OnPreResume(Boolean P0) { }
	// RVA: 0x2d9b898 VA: 0x75953b3898
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x2d9b8a0 VA: 0x75953b38a0
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2d9b8a8 VA: 0x75953b38a8
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
}
```