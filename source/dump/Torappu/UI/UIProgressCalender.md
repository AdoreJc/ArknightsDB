# UIProgressCalender

**Namespace:** `Torappu.UI`


## Fields

- `HorizontalLayoutGroup _layout`

- `NodeView _nodePrefab`

- `NodeView _startNodePrefab`

- `NodeView _endNodePrefab`


## Methods

- `Void Render(Param)`

- `ViewModel _CalcViewModel(Param)`

- `Void _ResetViewsIfNecessary(IList`1)`

- `Void _UpdateViewLayouts(ViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIProgressCalender : MonoBehaviour, IHotfixable
{
	private HorizontalLayoutGroup _layout; // 0x18
	private NodeView _nodePrefab; // 0x20
	private NodeView _startNodePrefab; // 0x28
	private NodeView _endNodePrefab; // 0x30
	private List`1 m_tempCacheList; // 0x38
	private List`1 m_views; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__CalcViewModel; // 0x8
	private static DelegateBridge __Hotfix0__ResetViewsIfNecessary; // 0x10
	private static DelegateBridge __Hotfix0__UpdateViewLayouts; // 0x18
	private static DelegateBridge __Hotfix0__ReadIndexDayFromTs; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x223865c VA: 0x759485065c
	public Void Render(Param param) { }
	// RVA: 0x2238724 VA: 0x7594850724
	private ViewModel _CalcViewModel(Param param) { }
	// RVA: 0x2238cd0 VA: 0x7594850cd0
	private Void _ResetViewsIfNecessary(IList`1 nodeModels) { }
	// RVA: 0x2239074 VA: 0x7594851074
	private Void _UpdateViewLayouts(ViewModel viewModel) { }
	// RVA: 0x2239324 VA: 0x7594851324
	private static DateTime _ReadIndexDayFromTs(Int64 ts) { }
	// RVA: 0x22397b4 VA: 0x75948517b4
	public Void .ctor() { }
}
```