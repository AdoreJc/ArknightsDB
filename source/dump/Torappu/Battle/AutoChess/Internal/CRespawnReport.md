# CRespawnReport

**Namespace:** `Torappu.Battle.AutoChess.Internal`


## Methods

- `Boolean <>xLuaBaseProxy_TryGetComment(CommentContext, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.AutoChess.Internal
public class CRespawnReport : BasicCommentReporter
{
	private static DelegateBridge __Hotfix0_get_commentTypeMask; // 0x0
	private static DelegateBridge __Hotfix0_TryGetComment; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override CommentTypeMask commentTypeMask { get; }

	// RVA: 0x1c8ad94 VA: 0x75942a2d94
	public override CommentTypeMask get_commentTypeMask() { }
	// RVA: 0x1c8adfc VA: 0x75942a2dfc
	public override Boolean TryGetComment(CommentContext context, out String message) { }
	// RVA: 0x1c8b084 VA: 0x75942a3084
	public Void .ctor() { }
	// RVA: 0x1c8b0f0 VA: 0x75942a30f0
	private Boolean <>xLuaBaseProxy_TryGetComment(CommentContext P0, out String P1) { }
}
```