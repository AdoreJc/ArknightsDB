# CrisisV2MapNodeViewHolder

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `RectTransform _nodeContainer`

- `UIAnimationLocation _animFocus`

- `CrisisV2NodeSlotType m_slotType`

- `CrisisV2MapNodeViewBase m_nodeView`

- `AnimationSwitchTween m_focusSwitchTween`

- `UIStateFinder m_stateFinder`


## Methods

- `Void _SetPos(Vector2)`

- `Void Init(Vector2)`

- `Void Render(CrisisV2MapNodeModel, CrisisV2MapNodeStatus, Boolean, Boolean, Boolean, String)`

- `CrisisV2MapNodeViewBase _GetNodeView(CrisisV2MapNodeModel)`

- `Void _EnsureFocusSwitchTween()`

- `CrisisV2MapNodeViewBase _FindNodeViewPrefab(CrisisV2NodeSlotType)`

- `Void _OnNodeClick(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapNodeViewHolder : MonoBehaviour, IHotfixable
{
	private RectTransform _nodeContainer; // 0x18
	private CrisisV2MapNodeViewBase[] _nodeViewPrefabs; // 0x20
	private UIAnimationLocation _animFocus; // 0x28
	private CrisisV2NodeSlotType m_slotType; // 0x38
	private CrisisV2MapNodeViewBase m_nodeView; // 0x40
	private AnimationSwitchTween m_focusSwitchTween; // 0x48
	private UIStateFinder m_stateFinder; // 0x50
	private static DelegateBridge __Hotfix0__SetPos; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__GetNodeView; // 0x18
	private static DelegateBridge __Hotfix0__EnsureFocusSwitchTween; // 0x20
	private static DelegateBridge __Hotfix0__FindNodeViewPrefab; // 0x28
	private static DelegateBridge __Hotfix0__OnNodeClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2c070c8 VA: 0x759521f0c8
	private Void _SetPos(Vector2 pos) { }
	// RVA: 0x2bfe190 VA: 0x7595216190
	public Void Init(Vector2 pos) { }
	// RVA: 0x2bfe404 VA: 0x7595216404
	public Void Render(CrisisV2MapNodeModel nodeModel, CrisisV2MapNodeStatus nodeStatus, Boolean isExclusion, Boolean isNodeFocus, Boolean isNodeHighLight, String tutorialKey) { }
	// RVA: 0x2c07250 VA: 0x759521f250
	private CrisisV2MapNodeViewBase _GetNodeView(CrisisV2MapNodeModel nodeModel) { }
	// RVA: 0x2c07168 VA: 0x759521f168
	private Void _EnsureFocusSwitchTween() { }
	// RVA: 0x2c074e4 VA: 0x759521f4e4
	private CrisisV2MapNodeViewBase _FindNodeViewPrefab(CrisisV2NodeSlotType slotType) { }
	// RVA: 0x2c0762c VA: 0x759521f62c
	private Void _OnNodeClick(String nodeId) { }
	// RVA: 0x2c07728 VA: 0x759521f728
	public Void .ctor() { }
}
```