# CKillEnemyEachTime

**Namespace:** `Torappu.Battle.AutoChess.Internal`


## Fields

- `EnemyLevelMask m_enemyLevelMask`


## Methods

- `Void <>xLuaBaseProxy_OnInit(AutoChessBattleCommentManager, Act1VAutoChessBattleCommentData)`

- `Boolean <>xLuaBaseProxy_TryGetComment(CommentContext, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.AutoChess.Internal
public class CKillEnemyEachTime : BasicCommentReporter
{
	private EnemyLevelMask m_enemyLevelMask; // 0x24
	private static DelegateBridge __Hotfix0_get_commentTypeMask; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_TryGetComment; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override CommentTypeMask commentTypeMask { get; }

	// RVA: 0x1c89a4c VA: 0x75942a1a4c
	public override CommentTypeMask get_commentTypeMask() { }
	// RVA: 0x1c89ab4 VA: 0x75942a1ab4
	public override Void OnInit(AutoChessBattleCommentManager manager, Act1VAutoChessBattleCommentData data) { }
	// RVA: 0x1c89c30 VA: 0x75942a1c30
	public override Boolean TryGetComment(CommentContext context, out String message) { }
	// RVA: 0x1c89e38 VA: 0x75942a1e38
	public Void .ctor() { }
	// RVA: 0x1c89ea4 VA: 0x75942a1ea4
	private Void <>xLuaBaseProxy_OnInit(AutoChessBattleCommentManager P0, Act1VAutoChessBattleCommentData P1) { }
	// RVA: 0x1c89ea8 VA: 0x75942a1ea8
	private Boolean <>xLuaBaseProxy_TryGetComment(CommentContext P0, out String P1) { }
}
```