# RoguelikeTopicBattlePassPurchaseRewardOverviewState

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `RoguelikeTopicBattlePassRewardOverviewView _overviewView`

- `StateBean m_stateBean`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicBattlePassPurchaseRewardOverviewState : PopupFloatState
{
	private RoguelikeTopicBattlePassRewardOverviewView _overviewView; // 0x70
	private StateBean m_stateBean; // 0x78
	private Boolean m_isInited; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x263b064 VA: 0x7594c53064
	public override IStateBean GetCacheBean() { }
	// RVA: 0x263b0cc VA: 0x7594c530cc
	protected override Void OnEnter() { }
	// RVA: 0x263b170 VA: 0x7594c53170
	private Void _InitIfNot() { }
	// RVA: 0x263b3c8 VA: 0x7594c533c8
	public Void .ctor() { }
	// RVA: 0x263b524 VA: 0x7594c53524
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```