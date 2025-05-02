# TuningOrcheModel

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `String m_orcheId`

- `String m_orcheName`

- `String m_orcheDesc`

- `Int32 m_sortId`


## Properties

- `String orcheId`

- `String orcheName`

- `String orcheDesc`

- `Int32 sortId`


## Methods

- `String get_orcheId()`

- `String get_orcheName()`

- `String get_orcheDesc()`

- `Int32 get_sortId()`

- `Void LoadData(Act29SideOrcheData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningOrcheModel : IHotfixable
{
	private String m_orcheId; // 0x10
	private String m_orcheName; // 0x18
	private String m_orcheDesc; // 0x20
	private Int32 m_sortId; // 0x28
	private static DelegateBridge __Hotfix0_get_orcheId; // 0x0
	private static DelegateBridge __Hotfix0_get_orcheName; // 0x8
	private static DelegateBridge __Hotfix0_get_orcheDesc; // 0x10
	private static DelegateBridge __Hotfix0_get_sortId; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public String orcheId { get; }
	public String orcheName { get; }
	public String orcheDesc { get; }
	public Int32 sortId { get; }

	// RVA: 0x233dfd4 VA: 0x7594955fd4
	public String get_orcheId() { }
	// RVA: 0x233e03c VA: 0x759495603c
	public String get_orcheName() { }
	// RVA: 0x233e0a4 VA: 0x75949560a4
	public String get_orcheDesc() { }
	// RVA: 0x233d7c0 VA: 0x75949557c0
	public Int32 get_sortId() { }
	// RVA: 0x233e10c VA: 0x759495610c
	public Void LoadData(Act29SideOrcheData orcheData) { }
	// RVA: 0x233e1c4 VA: 0x75949561c4
	public Void .ctor() { }
}
```