# EnemyDuelRoundEndState

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `EnemyDuelRoundEndView _view`

- `UIRenderTextureImage _rtImage`

- `EnemyDuelRoundEndProperty m_prop`

- `EnemyDuelBattlePage m_page`

- `Boolean m_inited`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelRoundEndState : EnemyDuelBattleState, IValueMsgReceiver
{
	private EnemyDuelRoundEndView _view; // 0x80
	private UIRenderTextureImage _rtImage; // 0x88
	public const Int32 MSG_GO_TO_RANK_STATE; // 0x0
	private EnemyDuelRoundEndProperty m_prop; // 0x90
	private EnemyDuelBattlePage m_page; // 0x98
	private Boolean m_inited; // 0xa0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnMessage; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_GetSupportedGameState; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x29912d0 VA: 0x7594fa92d0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2991334 VA: 0x7594fa9334
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x29915e8 VA: 0x7594fa95e8
	protected override Void OnEnter() { }
	// RVA: 0x299170c VA: 0x7594fa970c
	private Void _InitIfNot() { }
	// RVA: 0x299196c VA: 0x7594fa996c
	protected override EnemyDuelServiceGameState GetSupportedGameState() { }
	// RVA: 0x29919d4 VA: 0x7594fa99d4
	public Void .ctor() { }
	// RVA: 0x2991aec VA: 0x7594fa9aec
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```