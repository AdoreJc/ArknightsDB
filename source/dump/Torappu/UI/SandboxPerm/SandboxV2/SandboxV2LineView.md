# SandboxV2LineView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Image _imgLine`

- `Color _disabledColor`

- `CanvasGroup _showHandler`

- `UIAnimationLocation _enterAnim`

- `Boolean m_inited`

- `SandboxV2EnterAnimTween m_enterAnimTween`

- `FadeSwitchTween m_showTween`

- `Boolean m_asyncShown`

- `SeqNumChecker m_dungeonConstructChecker`

- `SeqNumChecker m_dungeonChangeChecker`

- `SeqNumChecker m_enterAnimChecker`


## Methods

- `Void _InitIfNot()`

- `Void _OnRecycle()`

- `Void AsyncSetData(RenderParam)`

- `Void _LineTo(Vector2, Vector2)`

- `Void AsyncShow()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2LineView : MonoBehaviour, IAsyncDataView`1, IAsyncShowEffect, IHotfixable
{
	private Image _imgLine; // 0x18
	private Color _disabledColor; // 0x20
	private CanvasGroup _showHandler; // 0x30
	private UIAnimationLocation _enterAnim; // 0x38
	private Boolean m_inited; // 0x48
	private SandboxV2EnterAnimTween m_enterAnimTween; // 0x50
	private FadeSwitchTween m_showTween; // 0x58
	private Boolean m_asyncShown; // 0x60
	private SeqNumChecker m_dungeonConstructChecker; // 0x68
	private SeqNumChecker m_dungeonChangeChecker; // 0x78
	private SeqNumChecker m_enterAnimChecker; // 0x88
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__OnRecycle; // 0x8
	private static DelegateBridge __Hotfix0_AsyncSetData; // 0x10
	private static DelegateBridge __Hotfix0__LineTo; // 0x18
	private static DelegateBridge __Hotfix0_AsyncShow; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2565c6c VA: 0x7594b7dc6c
	private Void _InitIfNot() { }
	// RVA: 0x2565dc0 VA: 0x7594b7ddc0
	private Void _OnRecycle() { }
	// RVA: 0x2565e38 VA: 0x7594b7de38
	public Void AsyncSetData(RenderParam param) { }
	// RVA: 0x25660cc VA: 0x7594b7e0cc
	private Void _LineTo(Vector2 srcPos, Vector2 dstPos) { }
	// RVA: 0x25662dc VA: 0x7594b7e2dc
	public Void AsyncShow() { }
	// RVA: 0x2566348 VA: 0x7594b7e348
	public Void .ctor() { }
}
```