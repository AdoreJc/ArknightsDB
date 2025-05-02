# InfoPolyTrackPoint

**Namespace:** `Torappu.UI`


## Fields

- `Boolean m_availFlag`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void UpdateState(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class InfoPolyTrackPoint : ITrackPointModel, IHotfixable
{
	private Dictionary`2 m_forceId2FavorDataListMap; // 0x10
	private Boolean m_availFlag; // 0x18
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isShow { get; }

	// RVA: 0x226eb40 VA: 0x7594886b40
	public Boolean get_isShow() { }
	// RVA: 0x226eba8 VA: 0x7594886ba8
	public Void UpdateState(Object param) { }
	// RVA: 0x226ef64 VA: 0x7594886f64
	public Void .ctor() { }
}
```