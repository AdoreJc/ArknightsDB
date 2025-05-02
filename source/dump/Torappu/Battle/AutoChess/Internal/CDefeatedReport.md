# CDefeatedReport

**Namespace:** `Torappu.Battle.AutoChess.Internal`


## Methods

- `Boolean <>xLuaBaseProxy_TryGetComment(CommentContext, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.AutoChess.Internal
public class CDefeatedReport : BasicCommentReporter
{
	private static DelegateBridge __Hotfix0_get_commentTypeMask; // 0x0
	private static DelegateBridge __Hotfix0_TryGetComment; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override CommentTypeMask commentTypeMask { get; }

	// RVA: 0x1c8aa80 VA: 0x75942a2a80
	public override CommentTypeMask get_commentTypeMask() { }
	// RVA: 0x1c8aae8 VA: 0x75942a2ae8
	public override Boolean TryGetComment(CommentContext context, out String message) { }
	// RVA: 0x1c8ad24 VA: 0x75942a2d24
	public Void .ctor() { }
	// RVA: 0x1c8ad90 VA: 0x75942a2d90
	private Boolean <>xLuaBaseProxy_TryGetComment(CommentContext P0, out String P1) { }
}
```