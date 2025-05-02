# MailArchiveItemData

**Namespace:** `Torappu`


## Fields

- `String id`

- `MailArchiveItemType type`

- `Int32 sortId`

- `Int64 displayReceiveTs`

- `Int32 year`

- `Int32 dateDelta`

- `String senderId`

- `String title`

- `String content`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class MailArchiveItemData
{
	public String id; // 0x10
	public MailArchiveItemType type; // 0x18
	public Int32 sortId; // 0x1c
	public Int64 displayReceiveTs; // 0x20
	public Int32 year; // 0x28
	public Int32 dateDelta; // 0x2c
	public String senderId; // 0x30
	public String title; // 0x38
	public String content; // 0x40
	public List`1 rewardList; // 0x48


	// RVA: 0x349dd90 VA: 0x7595ab5d90
	public Void .ctor() { }
}
```