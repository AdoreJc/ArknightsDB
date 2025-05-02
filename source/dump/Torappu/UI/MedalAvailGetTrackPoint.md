# MedalAvailGetTrackPoint

**Namespace:** `Torappu.UI`


## Fields

- `Boolean m_showFlag`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void UpdateState(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class MedalAvailGetTrackPoint : ITrackPointModel, IHotfixable
{
	private Boolean m_showFlag; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge __Hotfix0_GetShowFlag; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isShow { get; }

	// RVA: 0x2274060 VA: 0x759488c060
	public Boolean get_isShow() { }
	// RVA: 0x22740c8 VA: 0x759488c0c8
	public Void UpdateState(Object param) { }
	// RVA: 0x226ecec VA: 0x7594886cec
	public static Boolean GetShowFlag() { }
	// RVA: 0x227414c VA: 0x759488c14c
	public Void .ctor() { }
}
```