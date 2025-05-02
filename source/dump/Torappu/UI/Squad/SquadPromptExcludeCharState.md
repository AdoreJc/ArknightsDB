# SquadPromptExcludeCharState

**Namespace:** `Torappu.UI.Squad`


## Fields

- `SquadHomeStateBean _squadHomeStatebean`

- `SimpleLayoutContent _layout`

- `CancelDragIfFits _cancelDragIfFits`

- `StateBean m_stateBean`

- `CardListAdapter m_cardList`


## Methods

- `Void _ResetStateBean()`

- `Void _LoadNecessarySpritesForSquad()`

- `Void EventOnConfirm()`

- `Void EventOnCancel()`

- `Void OnEnable()`

- `Void <OnEnable>b__14_0()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadPromptExcludeCharState : PopupFloatState
{
	private SquadHomeStateBean _squadHomeStatebean; // 0x70
	private SimpleLayoutContent _layout; // 0x78
	private CancelDragIfFits _cancelDragIfFits; // 0x80
	private StateBean m_stateBean; // 0x88
	private List`1 m_excludedSquad; // 0x90
	private CardListAdapter m_cardList; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__ResetStateBean; // 0x10
	private static DelegateBridge __Hotfix0__LoadNecessarySpritesForSquad; // 0x18
	private static DelegateBridge __Hotfix0_EventOnConfirm; // 0x20
	private static DelegateBridge __Hotfix0_EventOnCancel; // 0x28
	private static DelegateBridge __Hotfix0_OnEnable; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x238a2a4 VA: 0x75949a22a4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x238a30c VA: 0x75949a230c
	protected override Void OnEnter() { }
	// RVA: 0x238a40c VA: 0x75949a240c
	private Void _ResetStateBean() { }
	// RVA: 0x238a528 VA: 0x75949a2528
	private Void _LoadNecessarySpritesForSquad() { }
	// RVA: 0x238a7ec VA: 0x75949a27ec
	public Void EventOnConfirm() { }
	// RVA: 0x238a874 VA: 0x75949a2874
	public Void EventOnCancel() { }
	// RVA: 0x238a8f8 VA: 0x75949a28f8
	private Void OnEnable() { }
	// RVA: 0x238a9c8 VA: 0x75949a29c8
	public Void .ctor() { }
	// RVA: 0x238ab34 VA: 0x75949a2b34
	private Void <OnEnable>b__14_0() { }
	// RVA: 0x238abb8 VA: 0x75949a2bb8
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```