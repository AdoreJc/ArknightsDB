# DebugPrinter

**Namespace:** ` `


## Fields

- `StringBuilder m_builder`


## Methods

- `String PrintLog(ref)`

- `Void _PrintRef(ref)`

- `Void _PrintExtraData(Object)`

- `Void _PrintModifierDelta(ref, Boolean)`

- `Void _PrintCommonModifier(ref, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DebugPrinter : IPrinter
{
	private StringBuilder m_builder; // 0x10


	// RVA: 0x3fe5840 VA: 0x75965fd840
	public String PrintLog(ref LogItem log) { }
	// RVA: 0x3fe5f9c VA: 0x75965fdf9c
	private Void _PrintRef(ref SourceOrTargetRef refItem) { }
	// RVA: 0x3fe61a4 VA: 0x75965fe1a4
	private Void _PrintExtraData(Object extraData) { }
	// RVA: 0x3fe61fc VA: 0x75965fe1fc
	private Void _PrintModifierDelta(ref ModifierDelta delta, Boolean showAbsDelta) { }
	// RVA: 0x3fe6354 VA: 0x75965fe354
	private Void _PrintCommonModifier(ref LogItem log, String token) { }
	// RVA: 0x3fe5ecc VA: 0x75965fdecc
	public Void .ctor() { }
}
```