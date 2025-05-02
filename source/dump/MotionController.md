# MotionController

**Namespace:** ` `


## Fields

- `Single _waitDuration`

- `Single _moveDuration`

- `Single _scalingTarget`

- `Single m_motionTargetX`

- `Single m_scaleFactor`

- `Single m_waitTimeFactor`


## Methods

- `Void _Init()`

- `Single GetTotalDuration()`

- `Void SetMotionTargetIndex(Int32)`

- `Void SetScaleFactor(Single)`

- `Void SetWaitFactor(Single)`

- `Void SetMotionPos(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class MotionController
{
	private RectTransform[] _targetTrans; // 0x10
	private RectTransform[] _moveTrans; // 0x18
	private RectTransform[] _targetScaleTrans; // 0x20
	private Single _waitDuration; // 0x28
	private Single _moveDuration; // 0x2c
	private Single _scalingTarget; // 0x30
	private Single[] m_targetInitPosX; // 0x38
	private Single m_motionTargetX; // 0x40
	private Single m_scaleFactor; // 0x44
	private Single m_waitTimeFactor; // 0x48


	// RVA: 0x2d6df6c VA: 0x7595385f6c
	private Void _Init() { }
	// RVA: 0x2d6e058 VA: 0x7595386058
	public Single GetTotalDuration() { }
	// RVA: 0x2d6e06c VA: 0x759538606c
	public Void SetMotionTargetIndex(Int32 targetIndex) { }
	// RVA: 0x2d6e0c0 VA: 0x75953860c0
	public Void SetScaleFactor(Single f) { }
	// RVA: 0x2d6e0c8 VA: 0x75953860c8
	public Void SetWaitFactor(Single f) { }
	// RVA: 0x2d6e0d0 VA: 0x75953860d0
	public Void SetMotionPos(Single time) { }
	// RVA: 0x2d6e258 VA: 0x7595386258
	public Void .ctor() { }
}
```