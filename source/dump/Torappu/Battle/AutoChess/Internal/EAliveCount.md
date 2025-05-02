# EAliveCount

**Namespace:** `Torappu.Battle.AutoChess.Internal`


## Fields

- `Int32 m_targetCnt`


## Methods

- `Void <>xLuaBaseProxy_OnInit(AutoChessBattleCommentManager, Act1VAutoChessBattleCommentData)`

- `Boolean <>xLuaBaseProxy_TryGetComment(CommentContext, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.AutoChess.Internal
public class EAliveCount : BasicCommentReporter
{
	private Int32 m_targetCnt; // 0x24
	private static DelegateBridge __Hotfix0_get_commentTypeMask; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_TryGetComment; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override CommentTypeMask commentTypeMask { get; }

	// RVA: 0x1c8a328 VA: 0x75942a2328
	public override CommentTypeMask get_commentTypeMask() { }
	// RVA: 0x1c8a390 VA: 0x75942a2390
	public override Void OnInit(AutoChessBattleCommentManager manager, Act1VAutoChessBattleCommentData data) { }
	// RVA: 0x1c8a470 VA: 0x75942a2470
	public override Boolean TryGetComment(CommentContext context, out String message) { }
	// RVA: 0x1c8a64c VA: 0x75942a264c
	public Void .ctor() { }
	// RVA: 0x1c8a6b8 VA: 0x75942a26b8
	private Void <>xLuaBaseProxy_OnInit(AutoChessBattleCommentManager P0, Act1VAutoChessBattleCommentData P1) { }
	// RVA: 0x1c8a6bc VA: 0x75942a26bc
	private Boolean <>xLuaBaseProxy_TryGetComment(CommentContext P0, out String P1) { }
}
```