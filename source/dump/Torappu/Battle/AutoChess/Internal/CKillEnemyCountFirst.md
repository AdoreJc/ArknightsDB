# CKillEnemyCountFirst

**Namespace:** `Torappu.Battle.AutoChess.Internal`


## Fields

- `Int32 m_targetkillCount`

- `EnemyLevelMask m_enemyLevelMask`


## Methods

- `Int32 _TryCollectKillCount(EnemyLevelMask, List`1)`

- `Void <>xLuaBaseProxy_OnInit(AutoChessBattleCommentManager, Act1VAutoChessBattleCommentData)`

- `Boolean <>xLuaBaseProxy_TryGetComment(CommentContext, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.AutoChess.Internal
public class CKillEnemyCountFirst : BasicCommentReporter
{
	private Int32 m_targetkillCount; // 0x24
	private EnemyLevelMask m_enemyLevelMask; // 0x28
	private static DelegateBridge __Hotfix0_get_commentTypeMask; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_TryGetComment; // 0x10
	private static DelegateBridge __Hotfix0__TryCollectKillCount; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override CommentTypeMask commentTypeMask { get; }

	// RVA: 0x1c89404 VA: 0x75942a1404
	public override CommentTypeMask get_commentTypeMask() { }
	// RVA: 0x1c8946c VA: 0x75942a146c
	public override Void OnInit(AutoChessBattleCommentManager manager, Act1VAutoChessBattleCommentData data) { }
	// RVA: 0x1c89624 VA: 0x75942a1624
	public override Boolean TryGetComment(CommentContext context, out String message) { }
	// RVA: 0x1c898ac VA: 0x75942a18ac
	private Int32 _TryCollectKillCount(EnemyLevelMask enemyLevelMask, List`1 sourceKillData) { }
	// RVA: 0x1c899d8 VA: 0x75942a19d8
	public Void .ctor() { }
	// RVA: 0x1c89a44 VA: 0x75942a1a44
	private Void <>xLuaBaseProxy_OnInit(AutoChessBattleCommentManager P0, Act1VAutoChessBattleCommentData P1) { }
	// RVA: 0x1c89a48 VA: 0x75942a1a48
	private Boolean <>xLuaBaseProxy_TryGetComment(CommentContext P0, out String P1) { }
}
```