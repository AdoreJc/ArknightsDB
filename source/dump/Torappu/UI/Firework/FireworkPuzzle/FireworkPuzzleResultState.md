# FireworkPuzzleResultState

**Namespace:** `Torappu.UI.Firework.FireworkPuzzle`


## Fields

- `FireworkPuzzleResultView _view`

- `RectTransform _backTrans`

- `FireworkPuzzleResultStateBean m_stateBean`

- `Boolean m_hasInited`

- `FireworkPuzzlePage m_page`


## Methods

- `Void _InitIfNot()`

- `Boolean _IsUIStable()`

- `Void _CloseResult()`

- `IEnumerator _ReceiveItemCoroutine(List`1)`

- `Void EventOnBtnClose()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkPuzzle
public class FireworkPuzzleResultState : PopupFadeState
{
	private FireworkPuzzleResultView _view; // 0x70
	private RectTransform _backTrans; // 0x78
	private FireworkPuzzleResultStateBean m_stateBean; // 0x80
	private Boolean m_hasInited; // 0x88
	private FireworkPuzzlePage m_page; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__IsUIStable; // 0x18
	private static DelegateBridge __Hotfix0__CloseResult; // 0x20
	private static DelegateBridge __Hotfix0__ReceiveItemCoroutine; // 0x28
	private static DelegateBridge __Hotfix0_EventOnBtnClose; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x28ff680 VA: 0x7594f17680
	public override IStateBean GetCacheBean() { }
	// RVA: 0x28ff6e8 VA: 0x7594f176e8
	protected override Void OnEnter() { }
	// RVA: 0x28ff90c VA: 0x7594f1790c
	private Void _InitIfNot() { }
	// RVA: 0x28ffa1c VA: 0x7594f17a1c
	private Boolean _IsUIStable() { }
	// RVA: 0x28ffaf8 VA: 0x7594f17af8
	private Void _CloseResult() { }
	// RVA: 0x28ffd34 VA: 0x7594f17d34
	private IEnumerator _ReceiveItemCoroutine(List`1 rewardList) { }
	// RVA: 0x28ffe1c VA: 0x7594f17e1c
	public Void EventOnBtnClose() { }
	// RVA: 0x28ffe84 VA: 0x7594f17e84
	public Void .ctor() { }
	// RVA: 0x28fff30 VA: 0x7594f17f30
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```