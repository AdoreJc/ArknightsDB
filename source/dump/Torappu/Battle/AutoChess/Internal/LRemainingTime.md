# LRemainingTime

**Namespace:** `Torappu.Battle.AutoChess.Internal`


## Fields

- `FP m_targetRemainingTime`


## Methods

- `Void <>xLuaBaseProxy_OnInit(AutoChessBattleCommentManager, Act1VAutoChessBattleCommentData)`

- `Boolean <>xLuaBaseProxy_TryGetComment(CommentContext, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.AutoChess.Internal
public class LRemainingTime : BasicCommentReporter
{
	private FP m_targetRemainingTime; // 0x28
	private static DelegateBridge __Hotfix0_get_commentTypeMask; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_TryGetComment; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override CommentTypeMask commentTypeMask { get; }

	// RVA: 0x1c8a6c0 VA: 0x75942a26c0
	public override CommentTypeMask get_commentTypeMask() { }
	// RVA: 0x1c8a728 VA: 0x75942a2728
	public override Void OnInit(AutoChessBattleCommentManager manager, Act1VAutoChessBattleCommentData data) { }
	// RVA: 0x1c8a834 VA: 0x75942a2834
	public override Boolean TryGetComment(CommentContext context, out String message) { }
	// RVA: 0x1c8aa0c VA: 0x75942a2a0c
	public Void .ctor() { }
	// RVA: 0x1c8aa78 VA: 0x75942a2a78
	private Void <>xLuaBaseProxy_OnInit(AutoChessBattleCommentManager P0, Act1VAutoChessBattleCommentData P1) { }
	// RVA: 0x1c8aa7c VA: 0x75942a2a7c
	private Boolean <>xLuaBaseProxy_TryGetComment(CommentContext P0, out String P1) { }
}
```