# BuildingFloatTradingView

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `Text _textGoldName`

- `Text _textDiamondName`

- `Text _textCompoundName`

- `Text _textGoldOrderNum`

- `Text _textDiamondOrderNum`

- `Text _textCompoundOrderNum`

- `Text _textOrderNum`

- `Text _textMaxOrderNum`

- `FillProgressBar _progress`

- `GameObject _panelEmpty`

- `GameObject _panelNonEmpty`

- `GameObject _panelAchieving`

- `String m_curSlotId`


## Methods

- `Void OnEnable()`

- `Void Render(RoomSlotModel, TradingInfoViewStruct)`

- `IEnumerator _UpdateAutoLayoutCoroutine()`

- `Void EventOnOpenPage()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatTradingView : MonoBehaviour, IHotfixable
{
	private Text _textGoldName; // 0x18
	private Text _textDiamondName; // 0x20
	private Text _textCompoundName; // 0x28
	private Text _textGoldOrderNum; // 0x30
	private Text _textDiamondOrderNum; // 0x38
	private Text _textCompoundOrderNum; // 0x40
	private Text _textOrderNum; // 0x48
	private Text _textMaxOrderNum; // 0x50
	private FillProgressBar _progress; // 0x58
	private GameObject _panelEmpty; // 0x60
	private GameObject _panelNonEmpty; // 0x68
	private GameObject _panelAchieving; // 0x70
	private RectTransform[] _autoLayouts; // 0x78
	private String m_curSlotId; // 0x80
	private static DelegateBridge __Hotfix0_OnEnable; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__UpdateAutoLayoutCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_EventOnOpenPage; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3e2ef68 VA: 0x7596446f68
	private Void OnEnable() { }
	// RVA: 0x3e2428c VA: 0x759643c28c
	public Void Render(RoomSlotModel slotModel, TradingInfoViewStruct tradingInfo) { }
	// RVA: 0x3e2efe0 VA: 0x7596446fe0
	private IEnumerator _UpdateAutoLayoutCoroutine() { }
	// RVA: 0x3e2f0b4 VA: 0x75964470b4
	public Void EventOnOpenPage() { }
	// RVA: 0x3e2f1a4 VA: 0x75964471a4
	public Void .ctor() { }
}
```