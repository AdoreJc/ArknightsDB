# CharUniEquipCardTrackPointViewModel

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Boolean m_haveUniEquip`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void UpdateState(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharUniEquipCardTrackPointViewModel : ITrackPointModel, IHotfixable
{
	private Boolean m_haveUniEquip; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isShow { get; }

	// RVA: 0x2d8d7e0 VA: 0x75953a57e0
	public Boolean get_isShow() { }
	// RVA: 0x2d8d848 VA: 0x75953a5848
	public Void UpdateState(Object param) { }
	// RVA: 0x2d8d928 VA: 0x75953a5928
	public Void .ctor() { }
}
```