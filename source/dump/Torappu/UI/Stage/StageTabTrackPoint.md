# StageTabTrackPoint

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Boolean m_haveRewardFlag`

- `Boolean m_isSelect`

- `Boolean m_isHasCheckTrack`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void UpdateState(Object)`

- `Boolean _TryFindRetroAvailFlag()`

- `Boolean _TryFindMiniAvailFlag()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageTabTrackPoint : ITrackPointModel, IHotfixable
{
	private Boolean m_haveRewardFlag; // 0x10
	private Boolean m_isSelect; // 0x11
	private Boolean m_isHasCheckTrack; // 0x12
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge __Hotfix0__TryFindRetroAvailFlag; // 0x10
	private static DelegateBridge __Hotfix0__TryFindMiniAvailFlag; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean isShow { get; }

	// RVA: 0x2fbe9dc VA: 0x75955d69dc
	public Boolean get_isShow() { }
	// RVA: 0x2fbea64 VA: 0x75955d6a64
	public Void UpdateState(Object param) { }
	// RVA: 0x2fbec78 VA: 0x75955d6c78
	private Boolean _TryFindRetroAvailFlag() { }
	// RVA: 0x2fbeee8 VA: 0x75955d6ee8
	private Boolean _TryFindMiniAvailFlag() { }
	// RVA: 0x2fbf320 VA: 0x75955d7320
	public Void .ctor() { }
}
```