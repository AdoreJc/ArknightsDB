# TrainingCampTrackPointModel

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `Boolean m_isShow`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void UpdateState(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class TrainingCampTrackPointModel : ITrackPointModel, IHotfixable
{
	private Boolean m_isShow; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge __Hotfix0_GetShowFlag; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isShow { get; }

	// RVA: 0x2ebf640 VA: 0x75954d7640
	public Boolean get_isShow() { }
	// RVA: 0x2ebf6a8 VA: 0x75954d76a8
	public Void UpdateState(Object param) { }
	// RVA: 0x2ebf72c VA: 0x75954d772c
	public static Boolean GetShowFlag() { }
	// RVA: 0x2ebf7e8 VA: 0x75954d77e8
	public Void .ctor() { }
}
```