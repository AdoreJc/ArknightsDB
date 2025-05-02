# FriendShowCharacterState

**Namespace:** `Torappu.UI.Friend`


## Fields

- `FriendListStateBean _stateBean`

- `FriendStateControl _stateControl`

- `FriendCardView _cardView`


## Methods

- `Void LoadNecessarySprite(CharacterCardViewModel)`

- `Void BackToState()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendShowCharacterState : PopupFloatState
{
	private const Int32 CARDMAXNUM; // 0x0
	private FriendListStateBean _stateBean; // 0x70
	private Transform[] _cardContainer; // 0x78
	private FriendStateControl _stateControl; // 0x80
	private FriendCardView _cardView; // 0x88
	private List`1 m_cardViewList; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_LoadNecessarySprite; // 0x8
	private static DelegateBridge __Hotfix0_BackToState; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x28b53ec VA: 0x7594ecd3ec
	public override IStateBean GetCacheBean() { }
	// RVA: 0x28b5454 VA: 0x7594ecd454
	public Void LoadNecessarySprite(CharacterCardViewModel cardViewModel) { }
	// RVA: 0x28b5570 VA: 0x7594ecd570
	public Void BackToState() { }
	// RVA: 0x28b5654 VA: 0x7594ecd654
	protected override Void OnEnter() { }
	// RVA: 0x28b5990 VA: 0x7594ecd990
	public Void .ctor() { }
	// RVA: 0x28b5a54 VA: 0x7594ecda54
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```