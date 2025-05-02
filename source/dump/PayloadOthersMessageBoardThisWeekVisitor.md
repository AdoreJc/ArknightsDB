# PayloadOthersMessageBoardThisWeekVisitor

**Namespace:** ` `


## Fields

- `String uid`

- `String nickName`

- `String nickNumber`

- `AvatarInfo avatar`

- `Int32 level`

- `Int64 lastVisitTs`


## Properties

- `AvatarInfo avatarInfo`


## Methods

- `AvatarInfo get_avatarInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PayloadOthersMessageBoardThisWeekVisitor : IMessageBoardVisitorData
{
	public String uid; // 0x10
	public String nickName; // 0x18
	public String nickNumber; // 0x20
	public AvatarInfo avatar; // 0x28
	public Int32 level; // 0x30
	public Int64 lastVisitTs; // 0x38

	public AvatarInfo avatarInfo { get; }

	// RVA: 0x32c9e98 VA: 0x75958e1e98
	public AvatarInfo get_avatarInfo() { }
	// RVA: 0x32c9ea0 VA: 0x75958e1ea0
	public Void .ctor() { }
}
```