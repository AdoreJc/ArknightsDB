# HiddenStageMapPluginTrackPointViewModel

**Namespace:** `Torappu.UI.HiddenStage`


## Fields

- `Boolean m_hasTrackPoint`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void UpdateState(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HiddenStage
public class HiddenStageMapPluginTrackPointViewModel : ITrackPointModel, IHotfixable
{
	private Boolean m_hasTrackPoint; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isShow { get; }

	// RVA: 0x285e354 VA: 0x7594e76354
	public Boolean get_isShow() { }
	// RVA: 0x285e3bc VA: 0x7594e763bc
	public Void UpdateState(Object param) { }
	// RVA: 0x285e474 VA: 0x7594e76474
	public Void .ctor() { }
}
```