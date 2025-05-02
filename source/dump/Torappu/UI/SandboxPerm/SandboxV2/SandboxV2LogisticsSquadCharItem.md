# SandboxV2LogisticsSquadCharItem

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Image _imgChar`

- `Image _imgProfession`

- `SandboxV2LogisticsCharBeanView _charBeanView`

- `GameObject _panelSelected`

- `GameObject _panelBlock`

- `GameObject _panelEmpty`

- `GameObject _panelChar`

- `CanvasGroup _canvasGroupEmpty`

- `Single _alphaNormal`

- `Single _alphaInactive`

- `UIStateFinder m_stateFinder`

- `Boolean m_isInited`

- `Int32 m_cachedIndex`


## Methods

- `Void Render(RenderParam)`

- `Void OnItemClicked()`

- `Void OnBlockItemClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2LogisticsSquadCharItem : MonoBehaviour, IHotfixable
{
	private Image _imgChar; // 0x18
	private Image _imgProfession; // 0x20
	private SandboxV2LogisticsCharBeanView _charBeanView; // 0x28
	private GameObject _panelSelected; // 0x30
	private GameObject _panelBlock; // 0x38
	private GameObject _panelEmpty; // 0x40
	private GameObject _panelChar; // 0x48
	private CanvasGroup _canvasGroupEmpty; // 0x50
	private Single _alphaNormal; // 0x58
	private Single _alphaInactive; // 0x5c
	private UIStateFinder m_stateFinder; // 0x60
	private Boolean m_isInited; // 0x70
	private Int32 m_cachedIndex; // 0x74
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnItemClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnBlockItemClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x25dc3d8 VA: 0x7594bf43d8
	public Void Render(RenderParam param) { }
	// RVA: 0x25dc624 VA: 0x7594bf4624
	public Void OnItemClicked() { }
	// RVA: 0x25dc72c VA: 0x7594bf472c
	public Void OnBlockItemClicked() { }
	// RVA: 0x25dc7e0 VA: 0x7594bf47e0
	public Void .ctor() { }
}
```