# ClipInfos

**Namespace:** ` `


## Fields

- `Boolean isInterruptionActive`

- `Boolean isLastFrameOfInterruption`

- `Int32 clipInfoCount`

- `Int32 nextClipInfoCount`

- `Int32 interruptingClipInfoCount`

- `AnimatorStateInfo stateInfo`

- `AnimatorStateInfo nextStateInfo`

- `AnimatorStateInfo interruptingStateInfo`

- `Single interruptingClipTimeAddition`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : 
protected class ClipInfos
{
	public Boolean isInterruptionActive; // 0x10
	public Boolean isLastFrameOfInterruption; // 0x11
	public Int32 clipInfoCount; // 0x14
	public Int32 nextClipInfoCount; // 0x18
	public Int32 interruptingClipInfoCount; // 0x1c
	public readonly List`1 clipInfos; // 0x20
	public readonly List`1 nextClipInfos; // 0x28
	public readonly List`1 interruptingClipInfos; // 0x30
	public AnimatorStateInfo stateInfo; // 0x38
	public AnimatorStateInfo nextStateInfo; // 0x5c
	public AnimatorStateInfo interruptingStateInfo; // 0x80
	public Single interruptingClipTimeAddition; // 0xa4


	// RVA: 0x620a694 VA: 0x7598822694
	public Void .ctor() { }
}
```