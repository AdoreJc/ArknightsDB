# ActivityInitMeta

**Namespace:** ` `


## Fields

- `String targetZoneId`

- `String targetStageId`

- `DataBundle actInitMeta`


## Methods

- `Boolean ConsumeAct(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ActivityInitMeta
{
	public String targetZoneId; // 0x10
	public String targetStageId; // 0x18
	public DataBundle actInitMeta; // 0x20
	private ListSet`1 m_consumedActIds; // 0x28


	// RVA: 0x2f57ec0 VA: 0x759556fec0
	public Boolean ConsumeAct(String actId) { }
	// RVA: 0x2f5bcb4 VA: 0x7595573cb4
	public Void .ctor() { }
}
```