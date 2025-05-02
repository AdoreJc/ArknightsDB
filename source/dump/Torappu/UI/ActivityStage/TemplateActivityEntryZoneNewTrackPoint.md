# TemplateActivityEntryZoneNewTrackPoint

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `Boolean m_haveNewFlag`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void UpdateState(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivityEntryZoneNewTrackPoint : ITrackPointModel, IHotfixable
{
	private Boolean m_haveNewFlag; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isShow { get; }

	// RVA: 0x3096bbc VA: 0x75956aebbc
	public Boolean get_isShow() { }
	// RVA: 0x3096c24 VA: 0x75956aec24
	public Void UpdateState(Object param) { }
	// RVA: 0x3096d1c VA: 0x75956aed1c
	public Void .ctor() { }
}
```