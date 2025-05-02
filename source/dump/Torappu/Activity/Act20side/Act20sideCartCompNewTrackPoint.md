# Act20sideCartCompNewTrackPoint

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `String m_compId`

- `Boolean m_haveNewFlag`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void UpdateState(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCartCompNewTrackPoint : ITrackPointModel, IHotfixable
{
	private String m_compId; // 0x10
	private Boolean m_haveNewFlag; // 0x18
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isShow { get; }

	// RVA: 0x32ecc28 VA: 0x7595904c28
	public Boolean get_isShow() { }
	// RVA: 0x32ecc90 VA: 0x7595904c90
	public Void UpdateState(Object param) { }
	// RVA: 0x32ecddc VA: 0x7595904ddc
	public Void .ctor() { }
}
```