# NodeInfoData

**Namespace:** ` `


## Fields

- `String nodeId`

- `NodeType nodeType`

- `Int32 sortId`

- `String placeId`

- `Boolean isPointPlace`

- `String chapterId`

- `TrackPointType trackPointType`

- `String unlockCondType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class NodeInfoData
{
	public String nodeId; // 0x10
	public NodeType nodeType; // 0x18
	public Int32 sortId; // 0x1c
	public String placeId; // 0x20
	public Boolean isPointPlace; // 0x28
	public String chapterId; // 0x30
	public TrackPointType trackPointType; // 0x38
	public String unlockCondType; // 0x40
	public List`1 unlockParams; // 0x48


	// RVA: 0x33b54c4 VA: 0x75959cd4c4
	public virtual Boolean ShouldSerializeunlockCondType() { }
	// RVA: 0x33b54d4 VA: 0x75959cd4d4
	public virtual Boolean ShouldSerializeunlockParams() { }
	// RVA: 0x33b5528 VA: 0x75959cd528
	public Void .ctor() { }
}
```