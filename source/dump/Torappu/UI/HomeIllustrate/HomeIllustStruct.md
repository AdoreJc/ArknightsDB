# HomeIllustStruct

**Namespace:** `Torappu.UI.HomeIllustrate`


## Fields

- `Int32 instId`

- `CharUISkinStruct skin`


## Properties

- `Boolean isEmpty`


## Methods

- `Boolean get_isEmpty()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HomeIllustrate
public class HomeIllustStruct
{
	private const String INIT_CHAR_HOME; // 0x0
	public static readonly HomeIllustStruct EMPTY; // 0x0
	public Int32 instId; // 0x10
	public CharUISkinStruct skin; // 0x18

	public Boolean isEmpty { get; }

	// RVA: 0x27d8044 VA: 0x7594df0044
	public Boolean get_isEmpty() { }
	// RVA: 0x27d80b8 VA: 0x7594df00b8
	public static HomeIllustStruct GetSelfSecretaryHomeIllustStruct() { }
	// RVA: 0x27d6aec VA: 0x7594deeaec
	public static HomeIllustStruct GetSelfCharRotationHomeIllustStruct() { }
	// RVA: 0x27d8540 VA: 0x7594df0540
	public static HomeIllustStruct GetSelfCharRotationHomeIllustStruct(String instId) { }
	// RVA: 0x27d8148 VA: 0x7594df0148
	public static HomeIllustStruct GetSelfHomeIllustStruct(String charId, String skinId) { }
	// RVA: 0x27d8620 VA: 0x7594df0620
	public Void .ctor() { }
	// RVA: 0x27d8628 VA: 0x7594df0628
	private static Void .cctor() { }
}
```