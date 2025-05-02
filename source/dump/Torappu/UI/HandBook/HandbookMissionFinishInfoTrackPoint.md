# HandbookMissionFinishInfoTrackPoint

**Namespace:** `Torappu.UI.HandBook`


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
// Namespace : Torappu.UI.HandBook
public class HandbookMissionFinishInfoTrackPoint : ITrackPointModel, IHotfixable
{
	private Boolean m_availFlag; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0__GetViewModelParam; // 0x8
	private static DelegateBridge __Hotfix0_UpdateState; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isShow { get; }

	// RVA: 0x2ebfa78 VA: 0x75954d7a78
	public Boolean get_isShow() { }
	// RVA: 0x2ebfae0 VA: 0x75954d7ae0
	private Dictionary`2 _GetViewModelParam() { }
	// RVA: 0x2ec0158 VA: 0x75954d8158
	public Void UpdateState(Object param) { }
	// RVA: 0x2ec0478 VA: 0x75954d8478
	public Void .ctor() { }
}
```