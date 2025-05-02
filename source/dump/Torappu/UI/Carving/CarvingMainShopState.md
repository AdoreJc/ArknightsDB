# CarvingMainShopState

**Namespace:** `Torappu.UI.Carving`


## Fields

- `CarvingMainShopView _shopView`

- `CarvingMainCardDetailBlocker _cardDetailBlocker`

- `UIAnimationLocation _showAnimLocation`

- `UIAnimationLocation _hideAnimLocation`

- `CanvasGroup _rootGroup`

- `Boolean m_isInited`

- `String m_actId`

- `Boolean m_fromAutoPopInfoState`

- `UIPageFinder m_pageFinder`

- `Tween m_showTween`

- `Tween m_hideTween`

- `Int32 m_dialogueInstId`


## Methods

- `Void _FromChallengeInfo(IStateBean)`

- `Void _InitIfNot(CarvingMainPage)`

- `Boolean _TriggerTutorialAVG()`

- `Void _PlayShowAnim()`

- `Void _TryOpenIntroDialogue(Story)`

- `Void <HideCoroutine>b__23_0()`

- `IEnumerator <>n__0(TransactionContext)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnPreResume(Boolean)`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_HideImmediately(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainShopState : PopupFadeState, IHotfixable
{
	private CarvingMainShopView _shopView; // 0x70
	private CarvingMainCardDetailBlocker _cardDetailBlocker; // 0x78
	private UIAnimationLocation _showAnimLocation; // 0x80
	private UIAnimationLocation _hideAnimLocation; // 0x90
	private CanvasGroup _rootGroup; // 0xa0
	private Boolean m_isInited; // 0xa8
	private String m_actId; // 0xb0
	private Boolean m_fromAutoPopInfoState; // 0xb8
	private UIPageFinder m_pageFinder; // 0xc0
	private Tween m_showTween; // 0xd0
	private Tween m_hideTween; // 0xd8
	private Int32 m_dialogueInstId; // 0xe0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnPreResume; // 0x18
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x20
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x28
	private static DelegateBridge __Hotfix0__FromChallengeInfo; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0__TriggerTutorialAVG; // 0x40
	private static DelegateBridge __Hotfix0__PlayShowAnim; // 0x48
	private static DelegateBridge __Hotfix0__TryOpenIntroDialogue; // 0x50
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x58
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x2db7810 VA: 0x75953cf810
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2db7874 VA: 0x75953cf874
	protected override Void OnEnter() { }
	// RVA: 0x2db7e08 VA: 0x75953cfe08
	protected override Void OnResume() { }
	// RVA: 0x2db7fa8 VA: 0x75953cffa8
	protected override Void OnPreResume(Boolean isFromStack) { }
	// RVA: 0x2db838c VA: 0x75953d038c
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x2db8408 VA: 0x75953d0408
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x2db8580 VA: 0x75953d0580
	private Void _FromChallengeInfo(IStateBean sb) { }
	// RVA: 0x2db7aa0 VA: 0x75953cfaa0
	private Void _InitIfNot(CarvingMainPage page) { }
	// RVA: 0x2db80f0 VA: 0x75953d00f0
	private Boolean _TriggerTutorialAVG() { }
	// RVA: 0x2db7c18 VA: 0x75953cfc18
	private Void _PlayShowAnim() { }
	// RVA: 0x2db8254 VA: 0x75953d0254
	private Void _TryOpenIntroDialogue(Story story) { }
	// RVA: 0x2db8654 VA: 0x75953d0654
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2db87c0 VA: 0x75953d07c0
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2db8928 VA: 0x75953d0928
	public Void .ctor() { }
	// RVA: 0x2db8998 VA: 0x75953d0998
	private Void <HideCoroutine>b__23_0() { }
	// RVA: 0x2db89b4 VA: 0x75953d09b4
	private IEnumerator <>n__0(TransactionContext context) { }
	// RVA: 0x2db89dc VA: 0x75953d09dc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2db89e4 VA: 0x75953d09e4
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2db89ec VA: 0x75953d09ec
	private Void <>xLuaBaseProxy_OnPreResume(Boolean P0) { }
	// RVA: 0x2db89f8 VA: 0x75953d09f8
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x2db8a00 VA: 0x75953d0a00
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
	// RVA: 0x2db8a08 VA: 0x75953d0a08
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext P0) { }
	// RVA: 0x2db8a30 VA: 0x75953d0a30
	private Void <>xLuaBaseProxy_HideImmediately(TransactionContext P0) { }
}
```