# CrisisV2AchievementCommentViewModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `String commentDesc`

- `Int32 sortId`

- `String commentId`


## Methods

- `Int32 CompareTo(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2AchievementCommentViewModel : IHotfixable, IComparable
{
	public String commentDesc; // 0x10
	public Int32 sortId; // 0x18
	public String commentId; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_CompareTo; // 0x8


	// RVA: 0x2be2f30 VA: 0x75951faf30
	public Void .ctor(ICrisisV2CommentData data) { }
	// RVA: 0x2be3104 VA: 0x75951fb104
	public Int32 CompareTo(Object obj) { }
}
```