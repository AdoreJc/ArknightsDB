# RoguelikeDungeonState

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeTransitionView _transitionView`

- `Boolean m_inited`

- `MenuAdapter m_menuAdapter`

- `Boolean m_isTransiting`

- `TransCoroutineStruct m_transCoroutineStruct`


## Methods

- `Void _InitIfNot()`

- `Void _OpenAvailInterDialog()`

- `Void _ConsumeDungeonGuideAutoShow()`

- `IEnumerator _ShowTransitionCoro(RoguelikeDungeonController)`

- `IEnumerator _TryDisplayTransition(RoguelikeDungeonController)`

- `TransOptions _CreateTransitionParam(RoguelikeDungeonZoneViewModel)`

- `Void _QuitTransition()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnPause()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeDungeonState : UIPopupState
{
	private RoguelikeTransitionView _transitionView; // 0x60
	private Boolean m_inited; // 0x68
	private MenuAdapter m_menuAdapter; // 0x70
	private Boolean m_isTransiting; // 0x78
	private TransCoroutineStruct m_transCoroutineStruct; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x8
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x18
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x20
	private static DelegateBridge __Hotfix0_OnEnter; // 0x28
	private static DelegateBridge __Hotfix0_OnResume; // 0x30
	private static DelegateBridge __Hotfix0_OnPause; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0__OpenAvailInterDialog; // 0x48
	private static DelegateBridge __Hotfix0__ConsumeDungeonGuideAutoShow; // 0x50
	private static DelegateBridge __Hotfix0__ShowTransitionCoro; // 0x58
	private static DelegateBridge __Hotfix0__TryDisplayTransition; // 0x60
	private static DelegateBridge __Hotfix0__CreateTransitionParam; // 0x68
	private static DelegateBridge __Hotfix0__QuitTransition; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x2a0177c VA: 0x759501977c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2a017e0 VA: 0x75950197e0
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2a01958 VA: 0x7595019958
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2a01ad0 VA: 0x7595019ad0
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x2a01bdc VA: 0x7595019bdc
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2a01ce8 VA: 0x7595019ce8
	protected override Void OnEnter() { }
	// RVA: 0x2a02040 VA: 0x759501a040
	protected override Void OnResume() { }
	// RVA: 0x2a023ac VA: 0x759501a3ac
	protected override Void OnPause() { }
	// RVA: 0x2a01e80 VA: 0x7595019e80
	private Void _InitIfNot() { }
	// RVA: 0x2a024b8 VA: 0x759501a4b8
	private Void _OpenAvailInterDialog() { }
	// RVA: 0x2a025a4 VA: 0x759501a5a4
	private Void _ConsumeDungeonGuideAutoShow() { }
	// RVA: 0x2a0216c VA: 0x759501a16c
	private IEnumerator _ShowTransitionCoro(RoguelikeDungeonController controller) { }
	// RVA: 0x2a026cc VA: 0x759501a6cc
	private IEnumerator _TryDisplayTransition(RoguelikeDungeonController controller) { }
	// RVA: 0x2a027c4 VA: 0x759501a7c4
	private TransOptions _CreateTransitionParam(RoguelikeDungeonZoneViewModel zoneModel) { }
	// RVA: 0x2a028e8 VA: 0x759501a8e8
	private Void _QuitTransition() { }
	// RVA: 0x2a02a6c VA: 0x759501aa6c
	public Void .ctor() { }
	// RVA: 0x2a02adc VA: 0x759501aadc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2a02ae4 VA: 0x759501aae4
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2a02aec VA: 0x759501aaec
	private Void <>xLuaBaseProxy_OnPause() { }
}
```