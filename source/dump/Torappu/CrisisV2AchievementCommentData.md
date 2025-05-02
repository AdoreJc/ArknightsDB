# CrisisV2AchievementCommentData

**Namespace:** `Torappu`


## Fields

- `String commentId`

- `Int32 sortId`

- `String desc`


## Methods

- `String GetCommentDesc()`

- `Int32 GetCommentSortId()`

- `String GetCommentId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CrisisV2AchievementCommentData : ICrisisV2CommentData, IHotfixable
{
	public String commentId; // 0x10
	public Int32 sortId; // 0x18
	public String desc; // 0x20
	private static DelegateBridge __Hotfix0_GetCommentDesc; // 0x0
	private static DelegateBridge __Hotfix0_GetCommentSortId; // 0x8
	private static DelegateBridge __Hotfix0_GetCommentId; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x349d010 VA: 0x7595ab5010
	public String GetCommentDesc() { }
	// RVA: 0x349d078 VA: 0x7595ab5078
	public Int32 GetCommentSortId() { }
	// RVA: 0x349d0e0 VA: 0x7595ab50e0
	public String GetCommentId() { }
	// RVA: 0x349d148 VA: 0x7595ab5148
	public Void .ctor() { }
}
```