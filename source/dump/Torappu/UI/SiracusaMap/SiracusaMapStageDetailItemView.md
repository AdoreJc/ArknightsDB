# SiracusaMapStageDetailItemView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `GameObject _objLevelPart`

- `Text _txtLevelName1`

- `Text _txtLevelName2`

- `StageRankView _stageRankView`

- `GameObject _objAvgPart`

- `Text _txtAvgName1`

- `Text _txtAvgName2`

- `GameObject _objAvgState`

- `Text _txtAvgState`

- `GameObject _objSelectPart`

- `GameObject _objExploreMoreTips`

- `GameObject _objSplitLine`

- `GameObject _objClickArea`

- `Boolean m_isSelecting`

- `String m_cachedItemId`

- `Boolean m_inited`


## Methods

- `Void set_selectChanged(Action`1)`

- `Void Render(SiracusaMapStageDetailInfoViewModel)`

- `Void _InitIfNot()`

- `Void _RefreshStageRank(Boolean, Int32)`

- `Void _RefreshSelectState(Boolean)`

- `Void OnDetailItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapStageDetailItemView : MonoBehaviour, IHotfixable
{
	private GameObject _objLevelPart; // 0x18
	private Text _txtLevelName1; // 0x20
	private Text _txtLevelName2; // 0x28
	private StageRankView _stageRankView; // 0x30
	private GameObject _objAvgPart; // 0x38
	private Text _txtAvgName1; // 0x40
	private Text _txtAvgName2; // 0x48
	private GameObject _objAvgState; // 0x50
	private Text _txtAvgState; // 0x58
	private GameObject _objSelectPart; // 0x60
	private GameObject _objExploreMoreTips; // 0x68
	private GameObject _objSplitLine; // 0x70
	private GameObject _objClickArea; // 0x78
	private Boolean m_isSelecting; // 0x80
	private String m_cachedItemId; // 0x88
	private Boolean m_inited; // 0x90
	private Action`1 <selectChanged>k__BackingField; // 0x98
	private static DelegateBridge __Hotfix0_get_selectChanged; // 0x0
	private static DelegateBridge __Hotfix0_set_selectChanged; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__RefreshStageRank; // 0x20
	private static DelegateBridge __Hotfix0__RefreshSelectState; // 0x28
	private static DelegateBridge __Hotfix0_OnDetailItemClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Action`1 selectChanged { get; set; }

	// RVA: 0x23e238c VA: 0x75949fa38c
	public Action`1 get_selectChanged() { }
	// RVA: 0x23e23f4 VA: 0x75949fa3f4
	public Void set_selectChanged(Action`1 value) { }
	// RVA: 0x23e2478 VA: 0x75949fa478
	public Void Render(SiracusaMapStageDetailInfoViewModel viewModel) { }
	// RVA: 0x23e2740 VA: 0x75949fa740
	private Void _InitIfNot() { }
	// RVA: 0x23e27cc VA: 0x75949fa7cc
	private Void _RefreshStageRank(Boolean isAvg, Int32 stageRank) { }
	// RVA: 0x23e2898 VA: 0x75949fa898
	private Void _RefreshSelectState(Boolean select) { }
	// RVA: 0x23e2924 VA: 0x75949fa924
	public Void OnDetailItemClick() { }
	// RVA: 0x23e29cc VA: 0x75949fa9cc
	public Void .ctor() { }
}
```