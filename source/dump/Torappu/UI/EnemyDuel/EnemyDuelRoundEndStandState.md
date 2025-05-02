# EnemyDuelRoundEndStandState

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `EnemyDuelRoundEndStandView _view`

- `UIRenderTextureImage _rtImage`

- `EnemyDuelRoundEndStandProperty m_prop`

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
public class EnemyDuelRoundEndStandState : EnemyDuelBattleState
{
	private EnemyDuelRoundEndStandView _view; // 0x80
	private UIRenderTextureImage _rtImage; // 0x88
	private EnemyDuelRoundEndStandProperty m_prop; // 0x90
	private EnemyDuelBattlePage m_page; // 0x98
	private Boolean m_inited; // 0xa0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnPause; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_GetSupportedGameState; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x298fe00 VA: 0x7594fa7e00
	public override IStateBean GetCacheBean() { }
	// RVA: 0x298fe64 VA: 0x7594fa7e64
	protected override Void OnEnter() { }
	// RVA: 0x2990784 VA: 0x7594fa8784
	protected override Void OnPause() { }
	// RVA: 0x298ff88 VA: 0x7594fa7f88
	private Void _InitIfNot() { }
	// RVA: 0x2990870 VA: 0x7594fa8870
	protected override EnemyDuelServiceGameState GetSupportedGameState() { }
	// RVA: 0x29908d8 VA: 0x7594fa88d8
	public Void .ctor() { }
	// RVA: 0x29909f0 VA: 0x7594fa89f0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x29909f8 VA: 0x7594fa89f8
	private Void <>xLuaBaseProxy_OnPause() { }
}
```