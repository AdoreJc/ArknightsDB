# DisplayHandler

**Namespace:** ` `


## Fields

- `HomeIllustView m_closure`

- `Coroutine m_loadCoroutine`

- `DisplayConfig m_curOperatingConfig`


## Methods

- `Void ModifyDisplayConfig(Int64, DisplayConfig)`

- `Void RemoveDisplayConfig(Int64)`

- `Void SyncIllustView()`

- `Void _CoShowOrHideIllustView(DisplayConfig)`

- `IEnumerator _CoShowIllustViewWithFade(HomeIllustStruct, DisplayConfig, Boolean)`

- `Void _ShowDefaultIllustView()`

- `Void _StopPrevLoadCoroutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DisplayHandler : IHotfixable
{
	private HomeIllustView m_closure; // 0x10
	private ListDict`2 m_illustDisplayStack; // 0x18
	private Coroutine m_loadCoroutine; // 0x20
	private DisplayConfig m_curOperatingConfig; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ModifyDisplayConfig; // 0x8
	private static DelegateBridge __Hotfix0_RemoveDisplayConfig; // 0x10
	private static DelegateBridge __Hotfix0_SyncIllustView; // 0x18
	private static DelegateBridge __Hotfix0__CoShowOrHideIllustView; // 0x20
	private static DelegateBridge __Hotfix0__CoShowIllustViewWithFade; // 0x28
	private static DelegateBridge __Hotfix0__ShowDefaultIllustView; // 0x30
	private static DelegateBridge __Hotfix0__StopPrevLoadCoroutine; // 0x38


	// RVA: 0x28391f0 VA: 0x7594e511f0
	public Void .ctor(HomeIllustView closure) { }
	// RVA: 0x283ab94 VA: 0x7594e52b94
	public Void ModifyDisplayConfig(Int64 instID, DisplayConfig displayConfig) { }
	// RVA: 0x283ac74 VA: 0x7594e52c74
	public Void RemoveDisplayConfig(Int64 instId) { }
	// RVA: 0x283ad90 VA: 0x7594e52d90
	public Void SyncIllustView() { }
	// RVA: 0x283aef0 VA: 0x7594e52ef0
	private Void _CoShowOrHideIllustView(DisplayConfig config) { }
	// RVA: 0x283b2f0 VA: 0x7594e532f0
	private IEnumerator _CoShowIllustViewWithFade(HomeIllustStruct homeIllust, DisplayConfig config, Boolean fadeBeforeReload) { }
	// RVA: 0x283b128 VA: 0x7594e53128
	private Void _ShowDefaultIllustView() { }
	// RVA: 0x283b23c VA: 0x7594e5323c
	private Void _StopPrevLoadCoroutine() { }
}
```