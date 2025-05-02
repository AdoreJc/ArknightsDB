# Main12RecordRewardBuffBtnView

**Namespace:** `Torappu.UI.Stage.ZoneRecord.Main12`


## Fields

- `RectTransform _timeContainer`

- `Single _timeScaler`

- `UIAtlasImage _back`

- `Single _emptyAlphaBack`

- `GameObject _newObj`

- `GameObject _rightDescObj`

- `GameObject _lightYellow`

- `GameObject _lightBlack`

- `GameObject _todayCanUse`

- `GameObject _todayNoUse`

- `GameObject _itemNameDes`

- `GameObject _arrow`

- `Text _itemUseTimeNum`

- `String m_itemId`

- `Boolean m_isInited`

- `UIItemTimeCountDown m_timeOut`

- `ZoneRewardBuffViewModel m_cachedViewModel`

- `Options m_options`

- `Action <onTimeOut>k__BackingField`


## Properties

- `Action onTimeOut`


## Methods

- `Action get_onTimeOut()`

- `Void set_onTimeOut(Action)`

- `Void Render(Options)`

- `Void _InitIfNot()`

- `Void _OnTimeOut()`

- `Void ShowRewardBuffDialog()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.ZoneRecord.Main12
public class Main12RecordRewardBuffBtnView : MonoBehaviour, IHotfixable
{
	private RectTransform _timeContainer; // 0x18
	private Single _timeScaler; // 0x20
	private UIAtlasImage _back; // 0x28
	private Single _emptyAlphaBack; // 0x30
	private GameObject _newObj; // 0x38
	private GameObject _rightDescObj; // 0x40
	private GameObject _lightYellow; // 0x48
	private GameObject _lightBlack; // 0x50
	private GameObject _todayCanUse; // 0x58
	private GameObject _todayNoUse; // 0x60
	private GameObject _itemNameDes; // 0x68
	private GameObject _arrow; // 0x70
	private Text _itemUseTimeNum; // 0x78
	private String m_itemId; // 0x80
	private Boolean m_isInited; // 0x88
	private UIItemTimeCountDown m_timeOut; // 0x90
	private ZoneRewardBuffViewModel m_cachedViewModel; // 0x98
	private Options m_options; // 0xa0
	private Action <onTimeOut>k__BackingField; // 0xa8
	private static DelegateBridge __Hotfix0_get_onTimeOut; // 0x0
	private static DelegateBridge __Hotfix0_set_onTimeOut; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__OnTimeOut; // 0x20
	private static DelegateBridge __Hotfix0_ShowRewardBuffDialog; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action onTimeOut { get; set; }

	// RVA: 0x2fd26e0 VA: 0x75955ea6e0
	private Action get_onTimeOut() { }
	// RVA: 0x2fd2748 VA: 0x75955ea748
	public Void set_onTimeOut(Action value) { }
	// RVA: 0x2fd27cc VA: 0x75955ea7cc
	public Void Render(Options options) { }
	// RVA: 0x2fd2bf8 VA: 0x75955eabf8
	private Void _InitIfNot() { }
	// RVA: 0x2fd2d58 VA: 0x75955ead58
	private Void _OnTimeOut() { }
	// RVA: 0x2fd2e14 VA: 0x75955eae14
	public Void ShowRewardBuffDialog() { }
	// RVA: 0x2fd2f7c VA: 0x75955eaf7c
	public Void .ctor() { }
}
```