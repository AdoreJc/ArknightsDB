# MiniActTrialSingleCollectTrialTrackPointModel

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
public class MiniActTrialSingleCollectTrialTrackPointModel : ITrackPointModel, IHotfixable
{
	private Boolean m_showFlag; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge __Hotfix0_GetShowFlag; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isShow { get; }

	// RVA: 0x274db2c VA: 0x7594d65b2c
	public Boolean get_isShow() { }
	// RVA: 0x274db94 VA: 0x7594d65b94
	public Void UpdateState(Object param) { }
	// RVA: 0x274c5a0 VA: 0x7594d645a0
	public static Boolean GetShowFlag(String actId) { }
	// RVA: 0x274dc5c VA: 0x7594d65c5c
	public Void .ctor() { }
}
```