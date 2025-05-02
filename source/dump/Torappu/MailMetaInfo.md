# MailMetaInfo

**Namespace:** `Torappu`


## Fields

- `Int64 mailId`

- `String surveyMailId`

- `MailState state`

- `DateTime createTime`

- `Boolean hasItem`

- `MailFromInfo type`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class MailMetaInfo
{
	public Int64 mailId; // 0x10
	public String surveyMailId; // 0x18
	public MailState state; // 0x20
	public DateTime createTime; // 0x28
	public Boolean hasItem; // 0x30
	public MailFromInfo type; // 0x34


	// RVA: 0x32cc320 VA: 0x75958e4320
	public Void .ctor() { }
}
```