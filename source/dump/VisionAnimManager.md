# VisionAnimManager

**Namespace:** ` `


## Fields

- `RL03MenuVisionAndChaosObject m_closure`

- `Sequence m_sequence`


## Methods

- `Void AddNewVisionAnim(Int32, Int32, Int32)`

- `Void Clear()`

- `Void _TryToPick()`

- `Void _DoVisionAnim(Int32, Int32, Int32, Action)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class VisionAnimManager : IHotfixable
{
	private RL03MenuVisionAndChaosObject m_closure; // 0x10
	private Queue`1 m_pendingQueue; // 0x18
	private Sequence m_sequence; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_AddNewVisionAnim; // 0x8
	private static DelegateBridge __Hotfix0_Clear; // 0x10
	private static DelegateBridge __Hotfix0__TryToPick; // 0x18
	private static DelegateBridge __Hotfix0__DoVisionAnim; // 0x20


	// RVA: 0x2b9da7c VA: 0x75951b5a7c
	public Void .ctor(RL03MenuVisionAndChaosObject closure) { }
	// RVA: 0x2b9eb48 VA: 0x75951b6b48
	public Void AddNewVisionAnim(Int32 startSightNum, Int32 targetSightNum, Int32 maxSightNum) { }
	// RVA: 0x2b9e820 VA: 0x75951b6820
	public Void Clear() { }
	// RVA: 0x2b9f480 VA: 0x75951b7480
	private Void _TryToPick() { }
	// RVA: 0x2b9f5bc VA: 0x75951b75bc
	private Void _DoVisionAnim(Int32 startValue, Int32 offset, Int32 maxValue, Action callback) { }
}
```