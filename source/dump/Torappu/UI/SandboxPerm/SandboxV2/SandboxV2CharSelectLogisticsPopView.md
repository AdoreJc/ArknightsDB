# SandboxV2CharSelectLogisticsPopView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `CanvasGroup _tipsCanvasGroup`

- `Single _tipsShowDuration`

- `Boolean m_isInited`

- `FadeSwitchTween m_fadeSwitchTween`

- `UIStateFinder m_stateFinder`


## Methods

- `Void EventOnTipsCloseBtnClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CharSelectLogisticsPopView : SandboxV2AdminCharSelectAbstractPopView
{
	private CanvasGroup _tipsCanvasGroup; // 0x18
	private Single _tipsShowDuration; // 0x20
	private Boolean m_isInited; // 0x24
	private FadeSwitchTween m_fadeSwitchTween; // 0x28
	private UIStateFinder m_stateFinder; // 0x30
	private static DelegateBridge __Hotfix0_GetStateMode; // 0x0
	private static DelegateBridge __Hotfix0_Show; // 0x8
	private static DelegateBridge __Hotfix0_Hide; // 0x10
	private static DelegateBridge __Hotfix0_EventOnTipsCloseBtnClick; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2483c74 VA: 0x7594a9bc74
	public override SandboxV2AdminCharSelectStateMode GetStateMode() { }
	// RVA: 0x2483cdc VA: 0x7594a9bcdc
	public override Void Show(SandboxV2CharListViewModel charListViewModel) { }
	// RVA: 0x2483e54 VA: 0x7594a9be54
	public override Void Hide() { }
	// RVA: 0x2483ed4 VA: 0x7594a9bed4
	public Void EventOnTipsCloseBtnClick() { }
	// RVA: 0x2483d70 VA: 0x7594a9bd70
	private Void _InitIfNot() { }
	// RVA: 0x2483f88 VA: 0x7594a9bf88
	public Void .ctor() { }
}
```