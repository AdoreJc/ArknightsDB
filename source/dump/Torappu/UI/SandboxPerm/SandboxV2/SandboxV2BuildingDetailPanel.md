# SandboxV2BuildingDetailPanel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _pnlTipList`

- `UIRecycleLayoutGroup _content`

- `GameObject _pnlEmptyTip`

- `Text _textTitle`

- `Text _textEmptyTip`

- `UIAtlasImage _imgBkg`

- `SandboxV2BuildingTipView _tipViewPrefab`

- `Single _tipViewHeight`

- `SandboxV2BuildingInfoView _infoViewPrefab`

- `Single _infoViewHeightWithoutTitle`

- `Single _infoViewHeightWithTitle`

- `Boolean m_isInited`

- `Adapter m_adapter`

- `ISandboxV2BuildingDetail m_cachedBuildingDetailModel`


## Methods

- `Void _InitIfNot()`

- `Void SetParams(Param)`

- `Void Render(ISandboxV2BuildingDetail)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2BuildingDetailPanel : MonoBehaviour, IHotfixable
{
	private static readonly SandboxV2ConstructTipType[] CONCERNED_TIPS; // 0x0
	private GameObject _pnlTipList; // 0x18
	private UIRecycleLayoutGroup _content; // 0x20
	private GameObject _pnlEmptyTip; // 0x28
	private Text _textTitle; // 0x30
	private Text _textEmptyTip; // 0x38
	private UIAtlasImage _imgBkg; // 0x40
	private SandboxV2BuildingTipView _tipViewPrefab; // 0x48
	private Single _tipViewHeight; // 0x50
	private SandboxV2BuildingInfoView _infoViewPrefab; // 0x58
	private Single _infoViewHeightWithoutTitle; // 0x60
	private Single _infoViewHeightWithTitle; // 0x64
	private Boolean m_isInited; // 0x68
	private Adapter m_adapter; // 0x70
	private ISandboxV2BuildingDetail m_cachedBuildingDetailModel; // 0x78
	private Action`1 m_onClicked; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_SetParams; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x24fc254 VA: 0x7594b14254
	private Void _InitIfNot() { }
	// RVA: 0x24fc3c8 VA: 0x7594b143c8
	public Void SetParams(Param param) { }
	// RVA: 0x24fc4a0 VA: 0x7594b144a0
	public Void Render(ISandboxV2BuildingDetail buildingDetailModel) { }
	// RVA: 0x24fc808 VA: 0x7594b14808
	public Void .ctor() { }
	// RVA: 0x24fc89c VA: 0x7594b1489c
	private static Void .cctor() { }
}
```