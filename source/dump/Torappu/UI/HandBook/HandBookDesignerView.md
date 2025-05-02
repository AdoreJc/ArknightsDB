# HandBookDesignerView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `Text _designerName`

- `Text _drawerName`

- `CanvasGroup _panelCanvasGroup`

- `Boolean m_isInited`

- `FadeSwitchTween m_tween`


## Methods

- `Void _InitIfNot()`

- `Void Show()`

- `Void Hide()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookDesignerView : DataBinder`1
{
	private const Single FADE_DURATION; // 0x0
	private Text _designerName; // 0x20
	private Text _drawerName; // 0x28
	private CanvasGroup _panelCanvasGroup; // 0x30
	private Boolean m_isInited; // 0x38
	private FadeSwitchTween m_tween; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_Show; // 0x10
	private static DelegateBridge __Hotfix0_Hide; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2eac0e4 VA: 0x75954c40e4
	private Void _InitIfNot() { }
	// RVA: 0x2eac278 VA: 0x75954c4278
	public override Void OnValueChanged(HandBookDesignerViewProperty property) { }
	// RVA: 0x2ea4c04 VA: 0x75954bcc04
	public Void Show() { }
	// RVA: 0x2eac358 VA: 0x75954c4358
	public Void Hide() { }
	// RVA: 0x2eac3d4 VA: 0x75954c43d4
	public Void .ctor() { }
}
```