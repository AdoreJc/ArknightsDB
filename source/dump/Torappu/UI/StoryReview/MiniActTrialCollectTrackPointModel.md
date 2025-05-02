# MiniActTrialCollectTrackPointModel

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
public class MiniActTrialCollectTrackPointModel : ITrackPointModel, IHotfixable
{
	private Boolean m_showFlag; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge __Hotfix0_GetShowFlag; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isShow { get; }

	// RVA: 0x274c2a0 VA: 0x7594d642a0
	public Boolean get_isShow() { }
	// RVA: 0x274c308 VA: 0x7594d64308
	public Void UpdateState(Object param) { }
	// RVA: 0x274c3c4 VA: 0x7594d643c4
	public static Boolean GetShowFlag() { }
	// RVA: 0x274c85c VA: 0x7594d6485c
	public Void .ctor() { }
}
```