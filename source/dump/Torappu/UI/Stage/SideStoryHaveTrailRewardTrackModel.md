# SideStoryHaveTrailRewardTrackModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Boolean m_isShow`

- `Boolean m_isSelect`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void UpdateState(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SideStoryHaveTrailRewardTrackModel : ITrackPointModel, IHotfixable
{
	private Boolean m_isShow; // 0x10
	private Boolean m_isSelect; // 0x11
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isShow { get; }

	// RVA: 0x2f18b68 VA: 0x7595530b68
	public Boolean get_isShow() { }
	// RVA: 0x2f18be8 VA: 0x7595530be8
	public Void UpdateState(Object param) { }
	// RVA: 0x2f18e60 VA: 0x7595530e60
	public Void .ctor() { }
}
```