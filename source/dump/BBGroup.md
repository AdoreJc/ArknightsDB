# BBGroup

**Namespace:** ` `


## Fields

- `String blackboardKey`

- `String increaseValueKey`

- `String maxValueKey`

- `FP m_increaseValue`

- `FP m_maxValue`

- `FP m_curValue`

- `FP m_originValue`


## Methods

- `Void InitGroup(Blackboard)`

- `Void IncreaseBBValue(Blackboard)`

- `Void ResetBlackboard(Blackboard)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BBGroup
{
	public String blackboardKey; // 0x10
	public String increaseValueKey; // 0x18
	public String maxValueKey; // 0x20
	private FP m_increaseValue; // 0x28
	private FP m_maxValue; // 0x30
	private FP m_curValue; // 0x38
	private FP m_originValue; // 0x40


	// RVA: 0x1d6d5bc VA: 0x75943855bc
	public Void InitGroup(Blackboard blackboard) { }
	// RVA: 0x1d6d980 VA: 0x7594385980
	public Void IncreaseBBValue(Blackboard blackboard) { }
	// RVA: 0x1d6d788 VA: 0x7594385788
	public Void ResetBlackboard(Blackboard blackboard) { }
	// RVA: 0x1d6db00 VA: 0x7594385b00
	public Void .ctor() { }
}
```