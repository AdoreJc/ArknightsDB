# TimerRecordScrollController

**Namespace:** ` `


## Fields

- `Single gap`

- `Single midLine`

- `Int32 maxDisplay`

- `Boolean isDownward`

- `Single speed`

- `Single targetDelta`

- `Boolean targetDeltaFinished`


## Properties

- `Int32 entityCount`

- `Single fadeThreshold`


## Methods

- `Int32 get_entityCount()`

- `Single get_fadeThreshold()`

- `Void Reset(Int32)`

- `Void Scroll(Single, Single)`

- `Void Scroll(Single, Int32)`

- `Void Update(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TimerRecordScrollController
{
	public Single gap; // 0x10
	public Single midLine; // 0x14
	public Int32 maxDisplay; // 0x18
	public Boolean isDownward; // 0x1c
	public List`1 transformList; // 0x20
	public Single speed; // 0x28
	public Single targetDelta; // 0x2c
	public Boolean targetDeltaFinished; // 0x30

	private Int32 entityCount { get; }
	private Single fadeThreshold { get; }

	// RVA: 0x1b29e48 VA: 0x7594141e48
	private Int32 get_entityCount() { }
	// RVA: 0x1b29e90 VA: 0x7594141e90
	private Single get_fadeThreshold() { }
	// RVA: 0x1b29ec8 VA: 0x7594141ec8
	public Void .ctor(Single gap, Single midLine, Int32 maxDisplay, List`1 transformList, Boolean isDownward) { }
	// RVA: 0x1b29f38 VA: 0x7594141f38
	public Void Reset(Int32 displayCount) { }
	// RVA: 0x1b2a140 VA: 0x7594142140
	public Void Scroll(Single speed, Single targetDelta) { }
	// RVA: 0x1b2a168 VA: 0x7594142168
	public Void Scroll(Single speed, Int32 steps) { }
	// RVA: 0x1b2a1e0 VA: 0x75941421e0
	public Void Update(Single deltaTime) { }
}
```