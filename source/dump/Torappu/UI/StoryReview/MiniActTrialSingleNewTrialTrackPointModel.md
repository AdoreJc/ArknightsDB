# MiniActTrialSingleNewTrialTrackPointModel

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
public class MiniActTrialSingleNewTrialTrackPointModel : ITrackPointModel, IHotfixable
{
	private Boolean m_showFlag; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge __Hotfix0_GetShowFlag; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isShow { get; }

	// RVA: 0x274dccc VA: 0x7594d65ccc
	public Boolean get_isShow() { }
	// RVA: 0x274dd34 VA: 0x7594d65d34
	public Void UpdateState(Object param) { }
	// RVA: 0x274a124 VA: 0x7594d62124
	public static Boolean GetShowFlag(String actId) { }
	// RVA: 0x274ddec VA: 0x7594d65dec
	public Void .ctor() { }
}
```