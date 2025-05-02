# PlayerParam

**Namespace:** ` `


## Fields

- `JObjectWrapper m_playerParam`

- `JObjectWrapper m_dataParam`

- `Boolean m_hasMust6`

- `Int32 m_must6Count`


## Methods

- `Void UpdateData(String)`

- `Boolean HasMust6()`

- `Int32 GetMust6Count()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class PlayerParam : IHotfixable
{
	private const String BOOL_MUST6; // 0x0
	private const String INT_6COUNT; // 0x0
	private JObjectWrapper m_playerParam; // 0x10
	private JObjectWrapper m_dataParam; // 0x18
	private Boolean m_hasMust6; // 0x20
	private Int32 m_must6Count; // 0x24
	private static DelegateBridge __Hotfix0_UpdateData; // 0x0
	private static DelegateBridge __Hotfix0_HasMust6; // 0x8
	private static DelegateBridge __Hotfix0_GetMust6Count; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2722610 VA: 0x7594d3a610
	public Void UpdateData(String poolId) { }
	// RVA: 0x27227dc VA: 0x7594d3a7dc
	public Boolean HasMust6() { }
	// RVA: 0x2722844 VA: 0x7594d3a844
	public Int32 GetMust6Count() { }
	// RVA: 0x2722958 VA: 0x7594d3a958
	public Void .ctor() { }
}
```