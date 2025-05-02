# ELevelProgress

**Namespace:** `Torappu.Battle.AutoChess.Internal`


## Fields

- `FP m_targetProgress`


## Methods

- `Void <>xLuaBaseProxy_OnInit(AutoChessBattleCommentManager, Act1VAutoChessBattleCommentData)`

- `Boolean <>xLuaBaseProxy_TryGetComment(CommentContext, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.AutoChess.Internal
public class ELevelProgress : BasicCommentReporter
{
	private FP m_targetProgress; // 0x28
	private static DelegateBridge __Hotfix0_get_commentTypeMask; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_TryGetComment; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override CommentTypeMask commentTypeMask { get; }

	// RVA: 0x1c89eac VA: 0x75942a1eac
	public override CommentTypeMask get_commentTypeMask() { }
	// RVA: 0x1c89f14 VA: 0x75942a1f14
	public override Void OnInit(AutoChessBattleCommentManager manager, Act1VAutoChessBattleCommentData data) { }
	// RVA: 0x1c8a020 VA: 0x75942a2020
	public override Boolean TryGetComment(CommentContext context, out String message) { }
	// RVA: 0x1c8a2b4 VA: 0x75942a22b4
	public Void .ctor() { }
	// RVA: 0x1c8a320 VA: 0x75942a2320
	private Void <>xLuaBaseProxy_OnInit(AutoChessBattleCommentManager P0, Act1VAutoChessBattleCommentData P1) { }
	// RVA: 0x1c8a324 VA: 0x75942a2324
	private Boolean <>xLuaBaseProxy_TryGetComment(CommentContext P0, out String P1) { }
}
```