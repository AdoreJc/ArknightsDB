# TuningPlayStateBean

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `TuningPlayProperty m_prop`

- `Int32 m_enterSequenceNum`

- `Int32 m_eyeShowSequenceNum`

- `Int32 m_cardChangeSequenceNum`

- `String m_inputProductTypeId`


## Properties

- `TuningPlayProperty prop`


## Methods

- `TuningPlayProperty get_prop()`

- `Void InitData(String)`

- `Void UpdateData(Boolean)`

- `Void SetSelectProductTypeId(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningPlayStateBean : IStateBean, IHotfixable
{
	private TuningPlayProperty m_prop; // 0x10
	private Int32 m_enterSequenceNum; // 0x18
	private Int32 m_eyeShowSequenceNum; // 0x1c
	private Int32 m_cardChangeSequenceNum; // 0x20
	private String m_inputProductTypeId; // 0x28
	private static DelegateBridge __Hotfix0_get_prop; // 0x0
	private static DelegateBridge __Hotfix0_InitData; // 0x8
	private static DelegateBridge __Hotfix0_UpdateData; // 0x10
	private static DelegateBridge __Hotfix0_SetSelectProductTypeId; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public TuningPlayProperty prop { get; }

	// RVA: 0x2330264 VA: 0x7594948264
	public TuningPlayProperty get_prop() { }
	// RVA: 0x232fe1c VA: 0x7594947e1c
	public Void InitData(String actId) { }
	// RVA: 0x2330180 VA: 0x7594948180
	public Void UpdateData(Boolean isResumeFromStack) { }
	// RVA: 0x23336e0 VA: 0x759494b6e0
	public Void SetSelectProductTypeId(String inputProductTypeId) { }
	// RVA: 0x2331384 VA: 0x7594949384
	public Void .ctor() { }
}
```