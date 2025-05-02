# SandboxV2NodeShadowView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `CanvasGroup _showHandler`

- `UIAnimationLocation _enterAnim`

- `SeqNumChecker m_dungeonConstructChecker`

- `SeqNumChecker m_enterAnimChecker`

- `Boolean m_inited`

- `SandboxV2EnterAnimTween m_enterAnimTween`

- `FadeSwitchTween m_showTween`

- `Boolean m_asyncShown`


## Methods

- `Void _InitIfNot()`

- `Void _OnRecycle()`

- `Void AsyncSetData(RenderParam)`

- `Void AsyncShow()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2NodeShadowView : MonoBehaviour, IAsyncDataView`1, IAsyncShowEffect, IHotfixable
{
	private CanvasGroup _showHandler; // 0x18
	private UIAnimationLocation _enterAnim; // 0x20
	private SeqNumChecker m_dungeonConstructChecker; // 0x30
	private SeqNumChecker m_enterAnimChecker; // 0x40
	private Boolean m_inited; // 0x50
	private SandboxV2EnterAnimTween m_enterAnimTween; // 0x58
	private FadeSwitchTween m_showTween; // 0x60
	private Boolean m_asyncShown; // 0x68
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__OnRecycle; // 0x8
	private static DelegateBridge __Hotfix0_AsyncSetData; // 0x10
	private static DelegateBridge __Hotfix0_AsyncShow; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x25678c4 VA: 0x7594b7f8c4
	private Void _InitIfNot() { }
	// RVA: 0x2567a18 VA: 0x7594b7fa18
	private Void _OnRecycle() { }
	// RVA: 0x2567a90 VA: 0x7594b7fa90
	public Void AsyncSetData(RenderParam param) { }
	// RVA: 0x2567c78 VA: 0x7594b7fc78
	public Void AsyncShow() { }
	// RVA: 0x2567ce4 VA: 0x7594b7fce4
	public Void .ctor() { }
}
```