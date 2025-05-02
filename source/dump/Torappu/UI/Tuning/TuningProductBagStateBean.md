# TuningProductBagStateBean

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `TuningProductBagProperty m_prop`


## Properties

- `TuningProductBagProperty prop`


## Methods

- `TuningProductBagProperty get_prop()`

- `Void InitData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductBagStateBean : IStateBean, IHotfixable
{
	private TuningProductBagProperty m_prop; // 0x10
	private static DelegateBridge __Hotfix0_get_prop; // 0x0
	private static DelegateBridge __Hotfix0_InitData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public TuningProductBagProperty prop { get; }

	// RVA: 0x2341690 VA: 0x7594959690
	public TuningProductBagProperty get_prop() { }
	// RVA: 0x23415d4 VA: 0x75949595d4
	public Void InitData(String actId) { }
	// RVA: 0x2341d00 VA: 0x7594959d00
	public Void .ctor() { }
}
```