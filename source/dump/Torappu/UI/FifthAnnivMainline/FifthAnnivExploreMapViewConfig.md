# FifthAnnivExploreMapViewConfig

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `FifthAnnivExploreLineView _lineViewPrefab`

- `Color _colorNormalShadow`

- `Color _colorNormal`

- `Color _colorNormalNode`

- `Color _colorSuccessShadow`

- `Color _colorSuccess`

- `Color _colorFailShadow`

- `Color _colorFail`


## Properties

- `FifthAnnivExploreLineView lineViewPrefab`

- `Color normalLineColor`

- `Color normalNodeColor`

- `Color successColor`

- `Color failColor`

- `Color normalShadowColor`

- `Color successShadowColor`

- `Color failShadowColor`


## Methods

- `FifthAnnivExploreLineView get_lineViewPrefab()`

- `Color get_normalLineColor()`

- `Color get_normalNodeColor()`

- `Color get_successColor()`

- `Color get_failColor()`

- `Color get_normalShadowColor()`

- `Color get_successShadowColor()`

- `Color get_failShadowColor()`

- `FifthAnnivExploreAbstractNodeView GetNodeViewPrefab(FifthAnnivNodeType, Boolean)`

- `FifthAnnivExploreNodeShadowView GetNodeShadowViewPrefab(FifthAnnivNodeType, Boolean)`

- `FifthAnnivExploreMapNodeShowType _GetNodeShowTypeByNodeType(FifthAnnivNodeType, Boolean)`

- `Boolean _TryGetNodeViewPrefab(FifthAnnivExploreMapNodeShowType, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreMapViewConfig : ScriptableObject, IHotfixable
{
	private List`1 _nodeViewDataList; // 0x18
	private FifthAnnivExploreLineView _lineViewPrefab; // 0x20
	private Color _colorNormalShadow; // 0x28
	private Color _colorNormal; // 0x38
	private Color _colorNormalNode; // 0x48
	private Color _colorSuccessShadow; // 0x58
	private Color _colorSuccess; // 0x68
	private Color _colorFailShadow; // 0x78
	private Color _colorFail; // 0x88
	private Dictionary`2 m_nodeViewPrefabDict; // 0x98
	private static DelegateBridge __Hotfix0_get_lineViewPrefab; // 0x0
	private static DelegateBridge __Hotfix0_get_normalLineColor; // 0x8
	private static DelegateBridge __Hotfix0_get_normalNodeColor; // 0x10
	private static DelegateBridge __Hotfix0_get_successColor; // 0x18
	private static DelegateBridge __Hotfix0_get_failColor; // 0x20
	private static DelegateBridge __Hotfix0_get_normalShadowColor; // 0x28
	private static DelegateBridge __Hotfix0_get_successShadowColor; // 0x30
	private static DelegateBridge __Hotfix0_get_failShadowColor; // 0x38
	private static DelegateBridge __Hotfix0_GetNodeViewPrefab; // 0x40
	private static DelegateBridge __Hotfix0_GetNodeShadowViewPrefab; // 0x48
	private static DelegateBridge __Hotfix0__GetNodeShowTypeByNodeType; // 0x50
	private static DelegateBridge __Hotfix0__TryGetNodeViewPrefab; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public FifthAnnivExploreLineView lineViewPrefab { get; }
	public Color normalLineColor { get; }
	public Color normalNodeColor { get; }
	public Color successColor { get; }
	public Color failColor { get; }
	public Color normalShadowColor { get; }
	public Color successShadowColor { get; }
	public Color failShadowColor { get; }

	// RVA: 0x29231f0 VA: 0x7594f3b1f0
	public FifthAnnivExploreLineView get_lineViewPrefab() { }
	// RVA: 0x29247e0 VA: 0x7594f3c7e0
	public Color get_normalLineColor() { }
	// RVA: 0x2924848 VA: 0x7594f3c848
	public Color get_normalNodeColor() { }
	// RVA: 0x29248b0 VA: 0x7594f3c8b0
	public Color get_successColor() { }
	// RVA: 0x2924918 VA: 0x7594f3c918
	public Color get_failColor() { }
	// RVA: 0x2924980 VA: 0x7594f3c980
	public Color get_normalShadowColor() { }
	// RVA: 0x29249e8 VA: 0x7594f3c9e8
	public Color get_successShadowColor() { }
	// RVA: 0x2924a50 VA: 0x7594f3ca50
	public Color get_failShadowColor() { }
	// RVA: 0x2924ab8 VA: 0x7594f3cab8
	public FifthAnnivExploreAbstractNodeView GetNodeViewPrefab(FifthAnnivNodeType nodeType, Boolean isCurrent) { }
	// RVA: 0x29224f8 VA: 0x7594f3a4f8
	public FifthAnnivExploreNodeShadowView GetNodeShadowViewPrefab(FifthAnnivNodeType nodeType, Boolean isCurrent) { }
	// RVA: 0x2924b7c VA: 0x7594f3cb7c
	private FifthAnnivExploreMapNodeShowType _GetNodeShowTypeByNodeType(FifthAnnivNodeType nodeType, Boolean isCurrent) { }
	// RVA: 0x2924c28 VA: 0x7594f3cc28
	private Boolean _TryGetNodeViewPrefab(FifthAnnivExploreMapNodeShowType nodeShowType, out NodeViewPrefabData nodeViewPrefabData) { }
	// RVA: 0x2924ea8 VA: 0x7594f3cea8
	public Void .ctor() { }
}
```