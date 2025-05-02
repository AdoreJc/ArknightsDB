# CrisisV2CommentData

**Namespace:** `Torappu`


## Fields

- `String id`

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
public class CrisisV2CommentData : ICrisisV2CommentData, IHotfixable
{
	public String id; // 0x10
	public Int32 sortId; // 0x18
	public String desc; // 0x20
	private static DelegateBridge __Hotfix0_GetCommentDesc; // 0x0
	private static DelegateBridge __Hotfix0_GetCommentSortId; // 0x8
	private static DelegateBridge __Hotfix0_GetCommentId; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x349c4a8 VA: 0x7595ab44a8
	public String GetCommentDesc() { }
	// RVA: 0x349c510 VA: 0x7595ab4510
	public Int32 GetCommentSortId() { }
	// RVA: 0x349c578 VA: 0x7595ab4578
	public String GetCommentId() { }
	// RVA: 0x349c5e0 VA: 0x7595ab45e0
	public Void .ctor() { }
}
```