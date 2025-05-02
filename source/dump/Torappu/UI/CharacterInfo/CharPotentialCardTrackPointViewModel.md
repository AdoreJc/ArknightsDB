# CharPotentialCardTrackPointViewModel

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Boolean m_potentialImprovable`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void UpdateState(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharPotentialCardTrackPointViewModel : ITrackPointModel, IHotfixable
{
	private Boolean m_potentialImprovable; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isShow { get; }

	// RVA: 0x2d8d588 VA: 0x75953a5588
	public Boolean get_isShow() { }
	// RVA: 0x2d8d5f0 VA: 0x75953a55f0
	public Void UpdateState(Object param) { }
	// RVA: 0x2d8d770 VA: 0x75953a5770
	public Void .ctor() { }
}
```