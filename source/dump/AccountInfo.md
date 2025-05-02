# AccountInfo

**Namespace:** ` `


## Fields

- `Int64 lastUse`

- `Boolean isGuest`

- `LoginResult info`

- `String platformUid`

- `String userName`

- `String account`


## Properties

- `String uid`


## Methods

- `String get_uid()`

- `String GetDisplayName()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AccountInfo
{
	public Int64 lastUse; // 0x10
	public Boolean isGuest; // 0x18
	public LoginResult info; // 0x20
	public String platformUid; // 0x38
	public String userName; // 0x40
	public String account; // 0x48

	public String uid { get; }

	// RVA: 0x3753ccc VA: 0x7595d6bccc
	public String get_uid() { }
	// RVA: 0x37544c0 VA: 0x7595d6c4c0
	public String GetDisplayName() { }
	// RVA: 0x3753cc4 VA: 0x7595d6bcc4
	public Void .ctor() { }
}
```