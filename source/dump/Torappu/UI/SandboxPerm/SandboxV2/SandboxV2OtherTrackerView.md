# SandboxV2OtherTrackerView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SimpleLayoutContent _content`

- `ScrollRect _scrollRect`

- `Boolean m_isInited`

- `Adapter m_adapter`

- `SandboxV2OtherTrackerViewModel m_cachedViewModel`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2OtherTrackerView : DataBinder`1, IHotfixable
{
	private SimpleLayoutContent _content; // 0x20
	private ScrollRect _scrollRect; // 0x28
	private Boolean m_isInited; // 0x30
	private Adapter m_adapter; // 0x38
	private SandboxV2OtherTrackerViewModel m_cachedViewModel; // 0x40
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2556eec VA: 0x7594b6eeec
	public override Void OnValueChanged(SandboxV2OtherTrackerViewModelProperty property) { }
	// RVA: 0x2556fb8 VA: 0x7594b6efb8
	private Void _InitIfNot() { }
	// RVA: 0x255711c VA: 0x7594b6f11c
	public Void .ctor() { }
}
```