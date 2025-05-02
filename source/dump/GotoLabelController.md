# GotoLabelController

**Namespace:** ` `


## Fields

- `Int32 m_gotoIndex`


## Methods

- `Void RegisterLabel(String, Int32)`

- `Void TryGotoLabel(String)`

- `Void Reset()`

- `Void PreprocessCommands(List`1)`

- `Int32 GotoCommandIndex()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class GotoLabelController : ICommandFlowController
{
	private Dictionary`2 m_labelMap; // 0x10
	private Int32 m_gotoIndex; // 0x18


	// RVA: 0x3e6f928 VA: 0x7596487928
	public Void RegisterLabel(String label, Int32 index) { }
	// RVA: 0x3e6f67c VA: 0x759648767c
	public Void TryGotoLabel(String label) { }
	// RVA: 0x3e6f4e8 VA: 0x75964874e8
	public Void Reset() { }
	// RVA: 0x3e6f9b8 VA: 0x75964879b8
	public Void PreprocessCommands(List`1 commands) { }
	// RVA: 0x3e6fad4 VA: 0x7596487ad4
	public Int32 GotoCommandIndex() { }
	// RVA: 0x3e6f888 VA: 0x7596487888
	public Void .ctor() { }
}
```