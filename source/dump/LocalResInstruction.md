# LocalResInstruction

**Namespace:** ` `


## Fields

- `Boolean m_isFinished`

- `HotUpdateWorkflow m_workflow`


## Methods

- `Void _GeneratePersistentInfo()`

- `Void _ErrorAlertAndMarkFinished(String)`

- `Void _MarkFinished(Boolean)`

- `Void <_ErrorAlertAndMarkFinished>b__6_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class LocalResInstruction : CustomYieldInstruction
{
	private Boolean m_isFinished; // 0x10
	private HotUpdateWorkflow m_workflow; // 0x18

	public override Boolean keepWaiting { get; }

	// RVA: 0x27c2f2c VA: 0x7594ddaf2c
	public override Boolean get_keepWaiting() { }
	// RVA: 0x27c2c58 VA: 0x7594ddac58
	public Void .ctor(HotUpdateViewController viewCtrl, HotUpdateWorkflow workflow) { }
	// RVA: 0x27c2f3c VA: 0x7594ddaf3c
	private Void _GeneratePersistentInfo() { }
	// RVA: 0x27c31e4 VA: 0x7594ddb1e4
	private Void _ErrorAlertAndMarkFinished(String errorInfo) { }
	// RVA: 0x27c3274 VA: 0x7594ddb274
	private Void _MarkFinished(Boolean suc) { }
	// RVA: 0x27c32ac VA: 0x7594ddb2ac
	private Void <_ErrorAlertAndMarkFinished>b__6_0() { }
}
```