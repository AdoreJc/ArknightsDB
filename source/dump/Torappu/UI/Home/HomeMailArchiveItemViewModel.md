# HomeMailArchiveItemViewModel

**Namespace:** `Torappu.UI.Home`


## Fields

- `ViewType type`

- `Int32 year`

- `String yearText`

- `Int32 index`

- `String itemId`

- `Int32 sortId`

- `String title`

- `String content`

- `String senderId`

- `Int64 receiveTime`

- `String receiveTimeText`


## Methods

- `Int32 CompareTo(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMailArchiveItemViewModel : IHotfixable, IComparable
{
	public ViewType type; // 0x10
	public Int32 year; // 0x14
	public String yearText; // 0x18
	public Int32 index; // 0x20
	public String itemId; // 0x28
	public Int32 sortId; // 0x30
	public String title; // 0x38
	public String content; // 0x40
	public String senderId; // 0x48
	public Int64 receiveTime; // 0x50
	public String receiveTimeText; // 0x58
	public List`1 rewardItem; // 0x60
	private static DelegateBridge __Hotfix0_CompareTo; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x281fbcc VA: 0x7594e37bcc
	public Int32 CompareTo(Object obj) { }
	// RVA: 0x281fd78 VA: 0x7594e37d78
	public Void .ctor() { }
}
```