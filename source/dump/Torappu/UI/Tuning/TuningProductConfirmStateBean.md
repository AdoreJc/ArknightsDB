# TuningProductConfirmStateBean

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `String m_inputProductId`

- `TuningProductConfirmProperty m_prop`

- `Int32 m_enterSequenceNum`

- `Boolean m_resultIsNew`


## Properties

- `TuningProductConfirmProperty prop`


## Methods

- `TuningProductConfirmProperty get_prop()`

- `Void InitData(String)`

- `Void SetInputProductId(String)`

- `Void SetResultNew(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductConfirmStateBean : IStateBean, IHotfixable
{
	private String m_inputProductId; // 0x10
	private TuningProductConfirmProperty m_prop; // 0x18
	private Int32 m_enterSequenceNum; // 0x20
	private Boolean m_resultIsNew; // 0x24
	private static DelegateBridge __Hotfix0_get_prop; // 0x0
	private static DelegateBridge __Hotfix0_InitData; // 0x8
	private static DelegateBridge __Hotfix0_SetInputProductId; // 0x10
	private static DelegateBridge __Hotfix0_SetResultNew; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public TuningProductConfirmProperty prop { get; }

	// RVA: 0x23455d0 VA: 0x759495d5d0
	public TuningProductConfirmProperty get_prop() { }
	// RVA: 0x2345354 VA: 0x759495d354
	public Void InitData(String actId) { }
	// RVA: 0x23477e8 VA: 0x759495f7e8
	public Void SetInputProductId(String iProductId) { }
	// RVA: 0x234786c VA: 0x759495f86c
	public Void SetResultNew(Boolean iResultIsNew) { }
	// RVA: 0x2345d8c VA: 0x759495dd8c
	public Void .ctor() { }
}
```