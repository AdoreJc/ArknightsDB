# SandboxV2AdminMainBottomView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `RectTransform _selectedMark`

- `GameObject _gradient`

- `Boolean m_inited`

- `SandboxV2AdminMainModelProperty m_cachedProp`

- `Tweener m_tween`


## Methods

- `IEnumerator _TweenSelectedMarkTo(SandboxV2AdminMainPanelType, Boolean)`

- `Void _UpdateTab(SandboxV2AdminMainPanelType, Boolean)`

- `Void _EventTabClick(SandboxV2AdminMainPanelType)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainBottomView : SandboxV2AdminMainViewBase
{
	private SandboxV2AdminMainBottomTab[] _tabs; // 0x28
	private RectTransform _selectedMark; // 0x30
	private GameObject _gradient; // 0x38
	private Boolean m_inited; // 0x40
	private SandboxV2AdminMainModelProperty m_cachedProp; // 0x48
	private Tweener m_tween; // 0x50
	private const Single TWEEN_DUR; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__TweenSelectedMarkTo; // 0x8
	private static DelegateBridge __Hotfix0__UpdateTab; // 0x10
	private static DelegateBridge __Hotfix0__EventTabClick; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x24d8968 VA: 0x7594af0968
	public override Void OnValueChanged(SandboxV2AdminMainModelProperty property) { }
	// RVA: 0x24d9080 VA: 0x7594af1080
	private IEnumerator _TweenSelectedMarkTo(SandboxV2AdminMainPanelType panelType, Boolean immediately) { }
	// RVA: 0x24d917c VA: 0x7594af117c
	private Void _UpdateTab(SandboxV2AdminMainPanelType panelType, Boolean immediately) { }
	// RVA: 0x24d928c VA: 0x7594af128c
	private Void _EventTabClick(SandboxV2AdminMainPanelType panelType) { }
	// RVA: 0x24d8be8 VA: 0x7594af0be8
	private Void _InitIfNot() { }
	// RVA: 0x24d9484 VA: 0x7594af1484
	public Void .ctor() { }
}
```