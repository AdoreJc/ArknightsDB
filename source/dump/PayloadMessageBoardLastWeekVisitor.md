# PayloadMessageBoardLastWeekVisitor

**Namespace:** ` `


## Fields

- `String uid`

- `String nickName`

- `String nickNumber`

- `AvatarInfo avatar`

- `Int64 lastVisitTs`


## Properties

- `AvatarInfo avatarInfo`


## Methods

- `AvatarInfo get_avatarInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PayloadMessageBoardLastWeekVisitor : IMessageBoardVisitorData
{
	public String uid; // 0x10
	public String nickName; // 0x18
	public String nickNumber; // 0x20
	public AvatarInfo avatar; // 0x28
	public Int64 lastVisitTs; // 0x30

	public AvatarInfo avatarInfo { get; }

	// RVA: 0x32c9e74 VA: 0x75958e1e74
	public AvatarInfo get_avatarInfo() { }
	// RVA: 0x32c9e7c VA: 0x75958e1e7c
	public Void .ctor() { }
}
```