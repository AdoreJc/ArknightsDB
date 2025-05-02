# MiniActTrialNewTrialTrackPointModel

**Namespace:** `Torappu.UI.StoryReview`


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
// Namespace : Torappu.UI.StoryReview
public class MiniActTrialNewTrialTrackPointModel : ITrackPointModel, IHotfixable
{
	private Boolean m_showFlag; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge __Hotfix0_GetShowFlag; // 0x10
	private static DelegateBridge __Hotfix0_SetAvailableTrialVisited; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean isShow { get; }

	// RVA: 0x274d5b0 VA: 0x7594d655b0
	public Boolean get_isShow() { }
	// RVA: 0x274d618 VA: 0x7594d65618
	public Void UpdateState(Object param) { }
	// RVA: 0x274d69c VA: 0x7594d6569c
	public static Boolean GetShowFlag() { }
	// RVA: 0x274d878 VA: 0x7594d65878
	public static Void SetAvailableTrialVisited() { }
	// RVA: 0x274dabc VA: 0x7594d65abc
	public Void .ctor() { }
}
```