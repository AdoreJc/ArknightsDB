# RoguelikeTaskCompleteState

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RectTransform _viewContainer`

- `RectTransform _backRt`

- `Boolean m_hasInited`

- `RoguelikeDungeonPage m_page`

- `String m_topicId`

- `MenuAdapter m_adapter`

- `RoguelikeTaskCompleteView m_completeView`

- `RoguelikeTaskCompleteStateBean m_stateBean`


## Methods

- `Void _InitIfNot()`

- `Void _OnGetTaskReward()`

- `Void OnBtnQuit()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeTaskCompleteState : PopupFadeState
{
	private RectTransform _viewContainer; // 0x70
	private RectTransform _backRt; // 0x78
	private Boolean m_hasInited; // 0x80
	private RoguelikeDungeonPage m_page; // 0x88
	private String m_topicId; // 0x90
	private MenuAdapter m_adapter; // 0x98
	private RoguelikeTaskCompleteView m_completeView; // 0xa0
	private RoguelikeTaskCompleteStateBean m_stateBean; // 0xa8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__OnGetTaskReward; // 0x18
	private static DelegateBridge __Hotfix0_OnBtnQuit; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2af8be8 VA: 0x7595110be8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2af8c50 VA: 0x7595110c50
	protected override Void OnEnter() { }
	// RVA: 0x2af8e88 VA: 0x7595110e88
	private Void _InitIfNot() { }
	// RVA: 0x2af9554 VA: 0x7595111554
	private Void _OnGetTaskReward() { }
	// RVA: 0x2af97f8 VA: 0x75951117f8
	public Void OnBtnQuit() { }
	// RVA: 0x2af986c VA: 0x759511186c
	public Void .ctor() { }
	// RVA: 0x2af99c4 VA: 0x75951119c4
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```