# InfoEnemyHandbookAvailTrackPoint

**Namespace:** `Torappu.UI.Info`


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
// Namespace : Torappu.UI.Info
public class InfoEnemyHandbookAvailTrackPoint : ITrackPointModel, IHotfixable
{
	private Boolean m_availFlag; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isShow { get; }

	// RVA: 0x27bac68 VA: 0x7594dd2c68
	public Boolean get_isShow() { }
	// RVA: 0x27bacd0 VA: 0x7594dd2cd0
	public Void UpdateState(Object param) { }
	// RVA: 0x27baf54 VA: 0x7594dd2f54
	public Void .ctor() { }
}
```