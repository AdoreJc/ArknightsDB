# SandboxV2DevelopmentLineData

**Namespace:** `Torappu`


## Fields

- `String fromNodeId`

- `Int32 fromNodePosX`

- `Int32 fromNodePosY`

- `SandboxV2DevelopmentLineStyle lineStyle`

- `Int32 unlockBasementLevel`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SandboxV2DevelopmentLineData
{
	public String fromNodeId; // 0x10
	public List`1 toNodeIds; // 0x18
	public Int32 fromNodePosX; // 0x20
	public Int32 fromNodePosY; // 0x24
	public List`1 toNodePosXList; // 0x28
	public List`1 toNodePosYList; // 0x30
	public SandboxV2DevelopmentLineStyle lineStyle; // 0x38
	public Int32 unlockBasementLevel; // 0x3c


	// RVA: 0x34f2554 VA: 0x7595b0a554
	public Void .ctor() { }
}
```