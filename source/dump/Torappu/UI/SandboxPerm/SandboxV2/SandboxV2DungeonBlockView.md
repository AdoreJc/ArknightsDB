# SandboxV2DungeonBlockView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Graphic _graphicBlock`

- `CanvasGroup _canvasGroupBlock`

- `Color _defaultColor`

- `Boolean m_isInited`

- `FadeSwitchTween m_fadeSwitchTween`


## Methods

- `Void SetColor(Color)`

- `Void _SetBlockColorByParam(ShowParam)`

- `Void _Show(Boolean)`

- `Void _Hide(Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonBlockView : SandboxV2DungeonPushMessageElement
{
	private Graphic _graphicBlock; // 0x28
	private CanvasGroup _canvasGroupBlock; // 0x30
	private List`1 _blockColorBindList; // 0x38
	private Color _defaultColor; // 0x40
	private Boolean m_isInited; // 0x50
	private FadeSwitchTween m_fadeSwitchTween; // 0x58
	private static DelegateBridge __Hotfix0_SetColor; // 0x0
	private static DelegateBridge __Hotfix0_SetShowStatus; // 0x8
	private static DelegateBridge __Hotfix0__SetBlockColorByParam; // 0x10
	private static DelegateBridge __Hotfix0__Show; // 0x18
	private static DelegateBridge __Hotfix0__Hide; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x257056c VA: 0x7594b8856c
	public Void SetColor(Color blockColor) { }
	// RVA: 0x2570630 VA: 0x7594b88630
	public override Void SetShowStatus(ShowParam showParam) { }
	// RVA: 0x25706f0 VA: 0x7594b886f0
	private Void _SetBlockColorByParam(ShowParam showParam) { }
	// RVA: 0x2570858 VA: 0x7594b88858
	private Void _Show(Boolean isFastMode) { }
	// RVA: 0x2570904 VA: 0x7594b88904
	private Void _Hide(Boolean isFastMode) { }
	// RVA: 0x25709b0 VA: 0x7594b889b0
	private Void _InitIfNot() { }
	// RVA: 0x2570a9c VA: 0x7594b88a9c
	public Void .ctor() { }
}
```