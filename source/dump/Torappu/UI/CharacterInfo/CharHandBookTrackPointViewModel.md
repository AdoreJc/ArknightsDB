# CharHandBookTrackPointViewModel

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Boolean m_handbookInfoTrackPoint`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void UpdateState(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharHandBookTrackPointViewModel : ITrackPointModel, IHotfixable
{
	private Boolean m_handbookInfoTrackPoint; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isShow { get; }

	// RVA: 0x2d8d998 VA: 0x75953a5998
	public Boolean get_isShow() { }
	// RVA: 0x2d8da00 VA: 0x75953a5a00
	public Void UpdateState(Object param) { }
	// RVA: 0x2d8dae0 VA: 0x75953a5ae0
	public Void .ctor() { }
}
```