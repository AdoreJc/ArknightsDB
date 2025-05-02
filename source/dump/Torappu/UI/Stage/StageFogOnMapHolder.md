# StageFogOnMapHolder

**Namespace:** `Torappu.UI.Stage`


## Fields

- `String _fogId`

- `StageFogOnMapBase _fog`


## Properties

- `String fogId`

- `StageFogOnMapBase fog`


## Methods

- `String get_fogId()`

- `StageFogOnMapBase get_fog()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageFogOnMapHolder : MonoBehaviour, IHotfixable
{
	private String _fogId; // 0x18
	private StageFogOnMapBase _fog; // 0x20
	private static DelegateBridge __Hotfix0_get_fogId; // 0x0
	private static DelegateBridge __Hotfix0_get_fog; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public String fogId { get; }
	public StageFogOnMapBase fog { get; }

	// RVA: 0x2fa55a0 VA: 0x75955bd5a0
	public String get_fogId() { }
	// RVA: 0x2fa5608 VA: 0x75955bd608
	public StageFogOnMapBase get_fog() { }
	// RVA: 0x2fa5670 VA: 0x75955bd670
	public Void .ctor() { }
}
```