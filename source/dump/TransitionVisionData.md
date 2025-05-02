# TransitionVisionData

**Namespace:** ` `


## Fields

- `Int32 visionNum`

- `String visionIconId`

- `String visionDesc`

- `String visionColorCode`


## Methods

- `Void LoadData(String, Vision)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TransitionVisionData : IHotfixable
{
	public Int32 visionNum; // 0x10
	public String visionIconId; // 0x18
	public String visionDesc; // 0x20
	public String visionColorCode; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2bb1fe8 VA: 0x75951c9fe8
	public Void LoadData(String topicId, Vision playerVision) { }
	// RVA: 0x2bb21f0 VA: 0x75951ca1f0
	public Void .ctor() { }
}
```