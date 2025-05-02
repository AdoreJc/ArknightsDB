# InfoHandbookAvailTrackPoint

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
public class InfoHandbookAvailTrackPoint : ITrackPointModel, IHotfixable
{
	private Boolean m_availFlag; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge __Hotfix0_GetAvailState; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isShow { get; }

	// RVA: 0x27bafc4 VA: 0x7594dd2fc4
	public Boolean get_isShow() { }
	// RVA: 0x27bb02c VA: 0x7594dd302c
	public Void UpdateState(Object param) { }
	// RVA: 0x27bb0b0 VA: 0x7594dd30b0
	public static Boolean GetAvailState() { }
	// RVA: 0x27bb718 VA: 0x7594dd3718
	public Void .ctor() { }
}
```