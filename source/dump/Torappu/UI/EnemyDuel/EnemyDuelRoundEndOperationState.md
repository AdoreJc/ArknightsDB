# EnemyDuelRoundEndOperationState

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `EnemyDuelRoundEndOperationView _view`

- `UIRenderTextureImage _rtImage`

- `EnemyDuelRoundEndOperationProperty m_prop`

- `EnemyDuelBattlePage m_page`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPause()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelRoundEndOperationState : EnemyDuelBattleState
{
	private EnemyDuelRoundEndOperationView _view; // 0x80
	private UIRenderTextureImage _rtImage; // 0x88
	private EnemyDuelRoundEndOperationProperty m_prop; // 0x90
	private EnemyDuelBattlePage m_page; // 0x98
	private Boolean m_inited; // 0xa0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnPause; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_GetSupportedGameState; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x298e27c VA: 0x7594fa627c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x298e2e0 VA: 0x7594fa62e0
	protected override Void OnEnter() { }
	// RVA: 0x298e758 VA: 0x7594fa6758
	protected override Void OnPause() { }
	// RVA: 0x298e404 VA: 0x7594fa6404
	private Void _InitIfNot() { }
	// RVA: 0x298e844 VA: 0x7594fa6844
	protected override EnemyDuelServiceGameState GetSupportedGameState() { }
	// RVA: 0x298e8ac VA: 0x7594fa68ac
	public Void .ctor() { }
	// RVA: 0x298e9c4 VA: 0x7594fa69c4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x298e9cc VA: 0x7594fa69cc
	private Void <>xLuaBaseProxy_OnPause() { }
}
```