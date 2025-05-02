# TemplateTrapAllTrackViewModel

**Namespace:** `Torappu.UI.TemplateTrap`


## Fields

- `String domainId`

- `Boolean isShowFlag`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void UpdateState(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateTrap
public class TemplateTrapAllTrackViewModel : ITrackPointModel, IHotfixable
{
	public String domainId; // 0x10
	public Boolean isShowFlag; // 0x18
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isShow { get; }

	// RVA: 0x23505b8 VA: 0x75949685b8
	public Boolean get_isShow() { }
	// RVA: 0x2350620 VA: 0x7594968620
	public Void UpdateState(Object param) { }
	// RVA: 0x235092c VA: 0x759496892c
	public Void .ctor() { }
}
```