# SandboxV2RacerInventoryItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _panelNormal`

- `GameObject _panelTemp`

- `GameObject _panelMarked`

- `GameObject _panelNotMarked`

- `GameObject _panelSelected`

- `Image _iconRacer`

- `UIAnimationLocation _selectAnim`

- `SimpleLayoutContent _racerLevelContent`

- `Int32 m_racerLevel`

- `Adapter m_adapter`

- `Boolean m_hasInited`

- `UISwitchTween m_selectTween`

- `UIStateFinder m_stateFinder`

- `String m_cachedInstId`


## Methods

- `Void Render(SandboxV2RacerModel, Boolean)`

- `Void ResetSelectStatus()`

- `Void EventOnClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RacerInventoryItemView : MonoBehaviour, IHotfixable
{
	private GameObject _panelNormal; // 0x18
	private GameObject _panelTemp; // 0x20
	private GameObject _panelMarked; // 0x28
	private GameObject _panelNotMarked; // 0x30
	private GameObject _panelSelected; // 0x38
	private Image _iconRacer; // 0x40
	private Text[] _textName; // 0x48
	private UIAnimationLocation _selectAnim; // 0x50
	private SimpleLayoutContent _racerLevelContent; // 0x60
	private Int32 m_racerLevel; // 0x68
	private Adapter m_adapter; // 0x70
	private Boolean m_hasInited; // 0x78
	private UISwitchTween m_selectTween; // 0x80
	private UIStateFinder m_stateFinder; // 0x88
	private String m_cachedInstId; // 0x98
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_ResetSelectStatus; // 0x8
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x25e0958 VA: 0x7594bf8958
	public Void Render(SandboxV2RacerModel model, Boolean isSelected) { }
	// RVA: 0x25e0d9c VA: 0x7594bf8d9c
	public Void ResetSelectStatus() { }
	// RVA: 0x25e0e1c VA: 0x7594bf8e1c
	public Void EventOnClick() { }
	// RVA: 0x25e0bdc VA: 0x7594bf8bdc
	private Void _InitIfNot() { }
	// RVA: 0x25e0fa0 VA: 0x7594bf8fa0
	public Void .ctor() { }
}
```